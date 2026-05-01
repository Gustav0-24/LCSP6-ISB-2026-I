# **LABORATORIO 4: Uso de BITalino para ECG**

## **1. Introducción**

La electrocardiografía (ECG) es una técnica no invasiva ampliamente utilizada para registrar la actividad eléctrica del corazón mediante sensores colocados en la superficie corporal. Esta señal se genera como consecuencia de los procesos de despolarización y repolarización del músculo cardíaco, los cuales permiten la contracción coordinada del corazón y, por tanto, el adecuado bombeo de sangre hacia los diferentes tejidos del organismo.

El origen de esta actividad eléctrica se encuentra en el nodo sinoauricular (SA), considerado el marcapasos natural del corazón, desde donde se inician los potenciales de acción que se propagan a través del sistema de conducción cardíaco. Esta propagación eléctrica da lugar a patrones característicos en el ECG, como la onda P, el complejo QRS y la onda T, los cuales representan las distintas fases del ciclo cardíaco y permiten analizar el funcionamiento del corazón en condiciones normales y alteradas .

El análisis de la señal electrocardiográfica no solo permite determinar parámetros básicos como la frecuencia cardíaca, sino también evaluar la respuesta del sistema cardiovascular frente a distintos estímulos fisiológicos. Factores como la respiración, el nivel de actividad física y los cambios en la demanda metabólica del organismo pueden generar variaciones significativas en la dinámica cardíaca, reflejándose en modificaciones en la frecuencia y en la morfología del ECG .

En este sentido, el estudio del ECG en diferentes condiciones experimentales constituye una herramienta fundamental para comprender la adaptación del sistema cardiovascular. En el presente trabajo, se analizaron registros electrocardiográficos obtenidos en distintas fases: reposo, hiperventilación, ejercicio físico y recuperación. Estas condiciones permiten observar cómo el corazón responde a cambios en la oxigenación y en la demanda energética, evidenciando variaciones en la actividad eléctrica cardíaca




## **3. Materiales y equipos**

| Materiales                                   | Cantidad | Imagen                          |
|----------------------------------------------|----------|---------------------------------|
| Batería 3.7V                                 | 1        | ![bateria](https://github.com/user-attachments/assets/25fe9643-a7fa-4bd9-85ad-e1ce78a926ab) |
| Software OpenSignals                         | 1        | ![opensignals](https://github.com/user-attachments/assets/270de790-173f-42fc-9960-5b12a7fff042) |
| Electrodos de superficie descartables        | 3        | ![electrodos (1)](https://github.com/user-attachments/assets/2e58ad27-7c4a-4336-9fdf-fe54129be397) |
| Cable de los 3 electrodos                    | 1        | ![cable](https://github.com/user-attachments/assets/2d397e32-3ec4-4982-91fe-0d6855e3aec0) |
| Kit BITalino                                 | 1        | ![bitalino](https://github.com/user-attachments/assets/a60c127f-27c2-4a03-b852-454d23f54163) |
| Laptop                                       | 1        | ![laptop](https://github.com/user-attachments/assets/c1394461-1a65-41fc-b6f4-8d8ae5b3b37b) |

## **4. Procedimiento** 
1. Seleccionar la zona de medición (región cardíaca) y limpiar la piel con alcohol; de preferencia, evitar áreas con vello para mejorar la conductividad de los electrodos.
2. Colocar 3 electrodos (positivo, negativo y referencia) según la derivación de Einthoven elegida; por ejemplo, para Lead I: positivo en la clavícula izquierda, negativo en la clavícula derecha y referencia en la cresta ilíaca.
3. Conectar el sensor ECG al BITalino y sincronizar el dispositivo con la computadora mediante Bluetooth utilizando el software OpenSignals previamente instalado.
4. Realizar la adquisición de datos en distintas condiciones: en reposo (línea base), durante control respiratorio (inhalación y exhalación) y después de actividad física, registrando las variaciones de la señal ECG en cada caso.

### 4.1. ECG 

En primer lugar, se configura el sistema de adquisición utilizando el software OpenSignals (r)evolution junto con el dispositivo BITalino, verificando que la conexión Bluetooth y el sensor ECG funcionen correctamente para la visualización de la señal en tiempo real.
A continuación, se prepara al sujeto con el fin de mejorar la calidad de la señal. Para ello, se limpia la piel con alcohol en las zonas donde se colocarán los electrodos, reduciendo la impedancia. Luego, se colocan tres electrodos de superficie siguiendo una derivación de Einthoven (por ejemplo, Lead I): el electrodo positivo en la clavícula izquierda, el negativo en la clavícula derecha y el electrodo de referencia en una zona ósea como la cresta ilíaca.
Una vez colocados los electrodos, se inicia la adquisición de la señal ECG en el software. En primer lugar, se registra una línea base en reposo durante aproximadamente 30 segundos, procurando que el sujeto esté relajado y con respiración normal. Posteriormente, se realizan pruebas controladas de respiración (inhalación, retención y exhalación) para observar la variación de la señal. Luego, se incluye una fase de actividad física (por ejemplo, ejercicios como burpees) con el objetivo de analizar los cambios en la frecuencia cardíaca antes, durante y después del esfuerzo.
Finalmente, se detiene la adquisición y se almacenan los datos obtenidos. Las señales registradas pueden ser procesadas posteriormente mediante filtrado para reducir el ruido y facilitar su análisis. Se comparan las variaciones entre las condiciones de reposo, respiración controlada y actividad física, evaluando parámetros como la frecuencia cardíaca y la morfología de la señal ECG para su correcta interpretación.

A continuación, presentamos el material audiovisual tomado de la prueba del ECG:


**1. Reposo**

https://github.com/user-attachments/assets/28f5e9f0-a83b-4cdb-9ff1-9df40d6ecb73

**2. Respiracion**



**3. Actividad Física**



## 5. Procesamiento de datos <a name="procesamiento-de-datos"></a>
Para los resultados haremos uso del archivo "CodigosECG.ipynb" que se encuentra en el mismo folder. El cual contiene todos los codigos hechos para la visualización de las gráficas de las señales adquiridas. Asi como su respectivo filtrado y análisis de frecuencia.

### a) Importar Librerías  <a name="importar-librerías"></a>
Se importan las librerías a utilizar para graficar las señales.
```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.signal import butter, filtfilt, iirnotch
```
### b) Cargar archivos  <a name="cargar-archivos"></a>
Se cargan los archivos .txt que contienen las señales obtenidas del software OpenSignals.
```python
#Abrimos el archivo sin incluir las filas que inician con"#"
with open("reposo1.txt", "r") as f:
    lineas = f.readlines()

datos_limpios = [line.strip().split() for line in lineas if not line.startswith("#")]
datos = np.array(datos_limpios, dtype=float)
```

### c) Aplicación de filtros <a name="aplicación-de-filtros"></a>
El ECG es una señal bioeléctrica débil, muy suceptible al ruido de diversas fuentes, tanto internas como externas (al cuerpo del paciente). Los movimientos, las señales eléctricas de otros músculos, la mala conexión de electrodos pueden generar una lectura de ECG borrosa, por lo que es necesario aplicar un filtrado para mitigar esa interferencia[5]. Para este laboratorio se aplicaron los siguientes filtros:
- **Pasa-banda (0.5 Hz-40 Hz):** Filtrado suave para entornos ruidosos. Se usa principalmente para detectar la frecuencia cardiaca[6].
- **Filtro Notch:** Reduce la interferencia de la red eléctrica.
Gracias a este proceso de filtrado se logró resaltar mejor las ondas características del ECG, especialmente el complejo QRS y las ondas P y T.
<p align="center">
<img width="1226" height="458" alt="image" src="https://github.com/user-attachments/assets/6de69508-ae97-4735-96c8-4afbec3bcf4a" />
<em>Figura 5. Señales ECG con  intervalos y segmentos .</em>
</p>

### d) Ploteo de las señales <a name="visualización"></a>
Se realizó el ploteo de las señales crudas y filtradas, así como de sus respectivos FFT en amplitud y dB.

### 5.1 Reposo Basal 
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="1176" height="393" alt="image" src="https://github.com/user-attachments/assets/b2c2dca0-7358-46a5-aa63-d6ce0e82821d" />| <img width="1176" height="393" alt="image" src="https://github.com/user-attachments/assets/39f6cdd8-1efd-4e27-b2c4-591c0947b314" />|
|  FFT  |<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/bbd23322-c2ed-42d3-a326-d5831dd23b1b" />| <img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/783de173-f79f-4697-a5a2-5a9d56381e62" />|
|  FFT [dB]    |<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/9b18516b-4030-44d6-bf95-e41b87800e3f" />| <img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/77f01de9-a001-482e-bf06-a2213c149ce3" />|

### 5.2 Mantenimiento de la respiracion por 10 segundos

**Toma 1:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
|Ploteo  |<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/e6f90235-bfc6-4cf1-937f-dd2064d9f32d" />|<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/46e23738-7fe3-4ea2-90ab-fede75e82290" />|
| FFT    |<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/e25e1ef1-6bc0-4085-9969-1b48682d8b38" />| <img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/95174037-8dc7-4e58-a64f-1e0705a40add" />|
|  FFT [dB]    |<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/4478e1f3-8077-4925-8150-8e3f2ec0502b" />| <img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/c4ea490d-836e-4337-85dc-2bc5826e72b3" /> |

**Toma 2:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
|Ploteo  | <img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/133ee2e6-3d0c-49bc-b48b-367ece025ded" />|<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/09a252a1-3959-40be-bc9a-c24b6efad8cf" />|
| FFT    |<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/b4f3533f-bf81-41a5-8950-318bcce70978" />|<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/40d73983-a147-4585-a7f9-0cc015ec6ca3" />|
|  FFT [dB] | <img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/75f320db-90cb-4e0f-86ce-446040a534ca" />|<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/579310e4-d6b1-4fd4-ab3e-85db13bc43db" />|

**Toma 3:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo |<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/dd74eca2-5f5b-47ca-be8c-82cbbcf4c3ec" />|<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/2e221153-96af-42f2-a432-93ec00accf71" />|
|  FFT    |<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/cad0c7bb-7095-4317-9320-9a4d4f2c4ed6" />|<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/48f35fb8-efe0-4433-917b-4c2d89d121fd" />|
| FFT [dB] |<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/ea460a99-f9c8-4b14-9dd5-452fddbe5ca2" />|<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/e568ea60-58bc-4c92-89f6-627c3c939aef" />|

### 5.3 Reposo basal después del mantenimiento de la respiración
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo |<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/0f2d2a8f-da31-433f-9061-d6766b7bcb8b" />|<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/40cdc42d-7edf-4cbc-9c64-9733e1e5ca8c" />|
|  FFT    |<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/8d3f3d3c-c48e-4bd0-b4e1-99f9013f6c03" />|<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/ec60511d-8a85-4c48-94e9-cb56a812950d" />  |
| FFT [dB] |<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/3f4105ff-829e-43da-bc7f-445bb87346e6" />|<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/5e8625e8-1fbd-4dc1-9e4a-8cfe64dda7f9" />|

## 5.4 Respiración después de actividad aeróbica

**Toma 1:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo |<img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/b8781c16-a99c-421b-b028-91c948924a3c" />| <img width="1181" height="393" alt="image" src="https://github.com/user-attachments/assets/fe244dd1-e0a5-411b-a7bf-73cfd20082ef" />|
|  FFT    |<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/97916780-29e4-43a1-9b92-65571d309891" />| <img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/cfbbee03-6025-4f23-a8e6-0e0d3ca797a5" /> |
| FFT [dB] |<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/67dc52c0-9974-4905-b46b-6a3643fcd504" />| <img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/92e53a6d-a594-467f-b9d2-f91a2889169e" />|

**Toma 2:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo | <img width="1180" height="393" alt="image" src="https://github.com/user-attachments/assets/ce0eab54-39a1-43e6-b826-ef05aa667458" />| <img width="1172" height="393" alt="image" src="https://github.com/user-attachments/assets/425fd7bc-6df7-40c3-9bc6-ad8ffb92a9a3" />|
|  FFT    |<img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/aa504f13-9ece-463e-9923-4b8b6626be14" />| <img width="890" height="393" alt="image" src="https://github.com/user-attachments/assets/356141c7-24a3-4886-a438-ddf95a892c76" />|
| FFT [dB] |<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/1485a92b-c995-4058-813f-ebd4e8e71f92" />|<img width="875" height="393" alt="image" src="https://github.com/user-attachments/assets/24456f84-7600-42a4-b699-0f02def51abb" />|


## 6. Discusión y resultados <a name="#resultados-y-limitaciones"></a> 
- **Reposo basal**: El registro del ECG en reposo representa la actividad cardíaca en condiciones normales sin influencia de movimiento o esfuerzo físico. Se observan picos ascendentes (propios de la primera derivada). El complejo QRS positivo corresponde a la despolarización ventricular que es la activación eléctrica de las fibras cardíacas que generan la contracción principal del corazón que impulsa la sangre hacia la circulación sistémica y pulmonar. En la FFT se ve que la señal ECG concentra su energía a frecuencias menores a 40 Hz y que las frecuencias mayores son atenuadas. En la FFT de la señal filtrada se puede observar mejor las atenuaciondes de frecuencias.
- **Mantenimiento de la respiración por 10 segundos**: En los primeros segundos de la señal se presenta una distancia del intervalo R-R corta debido a la "adaptación fisiológica" inicial que se produce al aguantar la respiración. También se observa una disminución progresiva en la amplitud de los picos R en comparación al reposo basal, debido a que la apnea voluntaria genera una menor oxigenación y cambios en la presión intratorácica, lo cual altera la dinámica cardíaca y se manifiesta como una reducción progresiva en la amplitud de los picos del ECG.
- **Reposo basal después del mantenimiento de la respiración**: Al reanudar la respiración tras la apnea voluntaria, se observa la reaparición de la deriva de la línea base y una recuperación de los intervalor R-R, asociada al reinicio del ciclo respiratorio. Aun así, las variaciones de los intervalos R-R son irregulares, característicos de una arritmia sinusal, lo cual tiene sentido ya que esta corresponde a una variación fisiológica a causa de la apnea.
- **Respiración post actividad física**: Después de realizar una actividad aeróbica por 10 minutos, en ambas tomas se puede observar que hay más picos QRS por segundo en comparación con el reposo basal y una reducción de los intervalos R-R, lo que significa que el corazón late más rápido por el esfuerzo físico. Esto se traduce al aumento de la frecuencia cardíaca que conforme pasa el tiempo se va estabilizando tanto los picos como los intervalos R-R. También se observan variaciones en la amplitud de los picos a causa de la fluctuación del retorno venoso y el volumen sistólico.






