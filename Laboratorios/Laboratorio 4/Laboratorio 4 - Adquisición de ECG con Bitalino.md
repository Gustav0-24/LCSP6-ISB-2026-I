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

<div align="center">

| **Toma en reposo** |
|:----------------------:|
| <video src="https://github.com/user-attachments/assets/2fe97060-3664-4a90-8fc4-54cd0fdfc871" controls></video> |

</div>


**2. Respiracion**

<div align="center">
 
| **Toma 1** | **Toma 2** | **Toma 3** |
|:-----------------------:|:--------------------------:|:--------------------------:|
| <video src="https://github.com/user-attachments/assets/c5b884d1-5d74-4a28-a469-7fa17b167426" controls></video> | <video src="https://github.com/user-attachments/assets/df090e1b-4910-4459-b294-98deaa62d301" controls></video> | <video src="https://github.com/user-attachments/assets/d6b1aafb-9f1e-40aa-adf7-4eebcfd8355e" controls></video> |

</div>


**3. Actividad Física**

<div align="center">

| **Toma después de la Actividad Física** |
|:---------------------------:|
| <video src="https://github.com/user-attachments/assets/c87118a6-4fe0-4e38-ad03-b1fcf1e8c033" controls></video> |


</div>


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
|Ploteo   |<img width="700" height="235" alt="Captura de pantalla 2026-05-01 172021" src="https://github.com/user-attachments/assets/ec059952-142f-4f60-afde-c78ff03b0b65" />|<img width="1045" height="332" alt="Captura de pantalla 2026-05-01 172234" src="https://github.com/user-attachments/assets/30348cad-f635-47ea-b566-3a75fdaa3f27" />|
|  FFT  |<img width="1098" height="487" alt="Captura de pantalla 2026-05-01 172453" src="https://github.com/user-attachments/assets/44a28499-1428-4faa-b6e9-daf0722e2ddf" />| <img width="1103" height="477" alt="Captura de pantalla 2026-05-01 172543" src="https://github.com/user-attachments/assets/1a2898c7-c23c-4f06-8bbd-a553929de358" />|
|  FFT [dB]    |<img width="1112" height="488" alt="Captura de pantalla 2026-05-01 172613" src="https://github.com/user-attachments/assets/04216147-a66a-4607-bfab-498a6e8128e0" />|<img width="1127" height="512" alt="Captura de pantalla 2026-05-01 172638" src="https://github.com/user-attachments/assets/c7a9b919-8b22-4cf7-8ef2-f38e6c9c0f5c" />|

### 5.2 Mantenimiento de la respiracion por 10 segundos

**Toma 1:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
|Ploteo  |<img width="1117" height="362" alt="Captura de pantalla 2026-05-01 172759" src="https://github.com/user-attachments/assets/fceba875-1bd6-465c-a423-02f3c18dadf4" />|<img width="1113" height="358" alt="Captura de pantalla 2026-05-01 173128" src="https://github.com/user-attachments/assets/36a1ee0f-bec8-4c6f-a8dc-614d8a465b88" />|
| FFT    |<img width="1142" height="487" alt="Captura de pantalla 2026-05-01 172842" src="https://github.com/user-attachments/assets/a4ced52a-09dc-465f-a957-293b4ce7d55f" />| <img width="1152" height="482" alt="Captura de pantalla 2026-05-01 173139" src="https://github.com/user-attachments/assets/d5c7f026-2898-4f68-b3aa-083ac6034df1" />|
|  FFT [dB]    |<img width="1151" height="491" alt="Captura de pantalla 2026-05-01 173006" src="https://github.com/user-attachments/assets/f6e5f0c9-fd8c-4b13-8d13-1c94fd3d8b8e" />| <img width="1108" height="485" alt="Captura de pantalla 2026-05-01 173152" src="https://github.com/user-attachments/assets/05262476-1bca-44b9-a258-511f8ae8c624" />|

**Toma 2:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
|Ploteo  | <img width="1111" height="373" alt="Captura de pantalla 2026-05-01 173405" src="https://github.com/user-attachments/assets/cb07e4f4-0ecd-4f08-b8cd-308c71832aa1" />|<img width="1138" height="402" alt="Captura de pantalla 2026-05-01 173605" src="https://github.com/user-attachments/assets/20a17bac-f5f0-4813-83da-d7629840daec" />|
| FFT    |<img width="1117" height="490" alt="Captura de pantalla 2026-05-01 173420" src="https://github.com/user-attachments/assets/7c5e846e-b644-4c68-bad7-159ba75010be" />|<img width="1131" height="497" alt="Captura de pantalla 2026-05-01 173616" src="https://github.com/user-attachments/assets/8001a212-a51e-452f-910a-1607a6a219bd" />|
|  FFT [dB] | <img width="1162" height="498" alt="Captura de pantalla 2026-05-01 173433" src="https://github.com/user-attachments/assets/7a54d3ab-7106-4982-bcce-29fa308b67f6" />|<img width="1138" height="500" alt="Captura de pantalla 2026-05-01 173707" src="https://github.com/user-attachments/assets/7b3642aa-f289-43fe-acef-18dd56d8ca80" />|

**Toma 3:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo |<img width="968" height="335" alt="Captura de pantalla 2026-05-01 201131" src="https://github.com/user-attachments/assets/6c2b7b86-cfc5-44f7-9067-8793e6aeb615" />|<img width="943" height="307" alt="Captura de pantalla 2026-05-01 201500" src="https://github.com/user-attachments/assets/85c684bf-6d4a-4d9a-9b4d-e1ab96ced9e5" />|
|  FFT    |<img width="941" height="417" alt="Captura de pantalla 2026-05-01 201148" src="https://github.com/user-attachments/assets/31900fee-0d71-4dcf-a24b-e57a8ec31f54" />|<img width="937" height="405" alt="Captura de pantalla 2026-05-01 201521" src="https://github.com/user-attachments/assets/f5ceeacb-e75e-4466-a8ca-915b9c718f50" />|
| FFT [dB] |<img width="935" height="426" alt="Captura de pantalla 2026-05-01 201201" src="https://github.com/user-attachments/assets/696ed765-4bc0-4e58-8514-271a82f24e42" />|<img width="927" height="420" alt="Captura de pantalla 2026-05-01 201536" src="https://github.com/user-attachments/assets/1df251eb-af50-4768-a212-762f339725b8" />|

### 5.3 Reposo basal después del mantenimiento de la respiración
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo |<img width="923" height="311" alt="Captura de pantalla 2026-05-01 201814" src="https://github.com/user-attachments/assets/9e139836-fd53-47cf-8100-ad8f467a1de6" />|<img width="965" height="317" alt="Captura de pantalla 2026-05-01 202030" src="https://github.com/user-attachments/assets/b9edf8d7-215d-4810-915a-4adc7fb4d459" />|
|  FFT    |<img width="952" height="410" alt="Captura de pantalla 2026-05-01 201846" src="https://github.com/user-attachments/assets/68667608-2880-4d3a-b131-dc113faa9c32" />|<img width="958" height="422" alt="Captura de pantalla 2026-05-01 202047" src="https://github.com/user-attachments/assets/87564f52-65da-4c01-8ce3-c731d5122592" />|
| FFT [dB] |<img width="955" height="422" alt="Captura de pantalla 2026-05-01 201901" src="https://github.com/user-attachments/assets/600106eb-5550-40ce-9069-4c41b7b6e32c" />|<img width="997" height="457" alt="Captura de pantalla 2026-05-01 202101" src="https://github.com/user-attachments/assets/4f2c166d-014a-4e7f-8ea0-391da3e5ca2f" />|

## 5.4 Respiración después de actividad aeróbica

**Toma 1:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo |<img width="927" height="312" alt="Captura de pantalla 2026-05-01 202514" src="https://github.com/user-attachments/assets/9fbdcddb-c5f2-464c-8246-b8bc6b486709" />| <img width="942" height="307" alt="Captura de pantalla 2026-05-01 202901" src="https://github.com/user-attachments/assets/990d22c8-6e9b-4340-a385-7e4c26f608bd" />|
|  FFT    |<img width="958" height="413" alt="Captura de pantalla 2026-05-01 202539" src="https://github.com/user-attachments/assets/621ebd2f-c9e2-4a69-a13d-3e74a02f91a9" />| <img width="952" height="397" alt="Captura de pantalla 2026-05-01 202915" src="https://github.com/user-attachments/assets/3a4d6252-f2ce-43df-8e79-96a954a8969b" />|
| FFT [dB] |<img width="960" height="415" alt="Captura de pantalla 2026-05-01 202553" src="https://github.com/user-attachments/assets/ff248c27-a728-4f9e-ac3f-22d8ba30c10d" />| <img width="960" height="422" alt="Captura de pantalla 2026-05-01 202937" src="https://github.com/user-attachments/assets/fe447245-2ce3-4893-a136-0ce5db329bec" />|

**Toma 2:**
| Tipo                 | Señal original | Señal filtrada                         |
|-------------------------|----------|---------------------------------|
| Ploteo |<img width="952" height="297" alt="Captura de pantalla 2026-05-01 203124" src="https://github.com/user-attachments/assets/08a98072-5396-4530-9f41-6e3b07b5e7f5" />| <img width="901" height="306" alt="Captura de pantalla 2026-05-01 203405" src="https://github.com/user-attachments/assets/fdee620c-0c29-46b7-aaa8-5192ece62150" />|
|  FFT    |<img width="957" height="416" alt="Captura de pantalla 2026-05-01 203136" src="https://github.com/user-attachments/assets/6dedcb46-5fc1-41bc-962f-1e53ce728914" />| <img width="947" height="413" alt="Captura de pantalla 2026-05-01 203419" src="https://github.com/user-attachments/assets/9e9dd92c-e3c9-4f73-8b70-22addb3bb63e" />|
| FFT [dB] |<img width="943" height="418" alt="Captura de pantalla 2026-05-01 203153" src="https://github.com/user-attachments/assets/6255baed-2b39-4f5e-b8ff-215ba0bd3e96" />|<img width="971" height="422" alt="Captura de pantalla 2026-05-01 203433" src="https://github.com/user-attachments/assets/a348b405-83ea-4a24-b558-1c974df9052d" />|


## 6. Discusión y resultados <a name="#resultados-y-limitaciones"></a> 
- **Reposo basal**: El registro del ECG en reposo representa la actividad cardíaca en condiciones normales sin influencia de movimiento o esfuerzo físico. Se observan picos ascendentes (propios de la primera derivada). El complejo QRS positivo corresponde a la despolarización ventricular que es la activación eléctrica de las fibras cardíacas que generan la contracción principal del corazón que impulsa la sangre hacia la circulación sistémica y pulmonar. En la FFT se ve que la señal ECG concentra su energía a frecuencias menores a 40 Hz y que las frecuencias mayores son atenuadas. En la FFT de la señal filtrada se puede observar mejor las atenuaciondes de frecuencias.
- **Mantenimiento de la respiración por 10 segundos**: En los primeros segundos de la señal se presenta una distancia del intervalo R-R corta debido a la "adaptación fisiológica" inicial que se produce al aguantar la respiración. También se observa una disminución progresiva en la amplitud de los picos R en comparación al reposo basal, debido a que la apnea voluntaria genera una menor oxigenación y cambios en la presión intratorácica, lo cual altera la dinámica cardíaca y se manifiesta como una reducción progresiva en la amplitud de los picos del ECG.
- **Reposo basal después del mantenimiento de la respiración**: Al reanudar la respiración tras la apnea voluntaria, se observa la reaparición de la deriva de la línea base y una recuperación de los intervalor R-R, asociada al reinicio del ciclo respiratorio. Aun así, las variaciones de los intervalos R-R son irregulares, característicos de una arritmia sinusal, lo cual tiene sentido ya que esta corresponde a una variación fisiológica a causa de la apnea.
- **Respiración post actividad física**: Después de realizar una actividad aeróbica por 10 minutos, en ambas tomas se puede observar que hay más picos QRS por segundo en comparación con el reposo basal y una reducción de los intervalos R-R, lo que significa que el corazón late más rápido por el esfuerzo físico. Esto se traduce al aumento de la frecuencia cardíaca que conforme pasa el tiempo se va estabilizando tanto los picos como los intervalos R-R. También se observan variaciones en la amplitud de los picos a causa de la fluctuación del retorno venoso y el volumen sistólico.


## 7. Cuestionario de la guía

**a. What are the most typical types of noise sources affecting ECG?** 
Las fuentes de ruido más comunes son los artefactos por movimiento, la interferencia muscular, el ruido de la red eléctrica, la mala adherencia de los electrodos y las variaciones en la impedancia de la piel. Los artefactos por movimiento ocurren cuando el sujeto se desplaza o los electrodos pierden contacto estable con la piel, mientras que la actividad muscular cercana puede superponerse a la señal cardíaca lo que dificulta su interpretación. La interferencia eléctrica proveniente de equipos cercanos puede introducir ruido periódico y factores como el sudor o el desgaste de los electrodos afectan la calidad de la adquisición. 

**b. Why does the change of the positioning of the sensors (lead I-III) change the ECG signal components? How do the components change?** 
El cambio en la posición de los sensores modifica los componentes del ECG debido a que cada derivación mide la actividad eléctrica del corazón desde una orientación distinta. La señal registrada corresponde a la proyección del vector eléctrico cardíaco sobre el eje definido por los electrodos. Así que variar su posición significa que se puedan producir variaciones en la amplitud de las ondas, cambios en su polaridad (positiva o negativa) y ligeras modificaciones en la morfología del complejo QRS y otras ondas. Esto refleja que la actividad eléctrica del corazón es tridimensional y su representación depende del punto de observación. 

**c. Describe if there are major differences in the signal when acquiring the signal from different body locations (e.g., wrist / collarbone / chest). What could be the cause? Did you expect such changes in the signal?**
A pesar de que en la experiencia se tomaron las muestras desde la muñeca, se espera que sí existan diferencias en la señal ECG al adquirirla desde distintas ubicaciones del cuerpo. Generalmente, cuando los electrodos se colocan en el pecho, la señal presenta mayor amplitud y claridad debido a la cercanía con el corazón. En cambio, al ubicarlos en las muñecas o clavículas, la señal puede verse atenuada y más susceptible al ruido. Estas diferencias se deben principalmente a la distancia entre el corazón y los electrodos, la presencia de tejidos intermedios como músculo o grasa, y la mayor probabilidad de movimiento en las extremidades.

**d. The cardiac and the respiratory systems are well interconnected as is well known. Do you expect that different types of breathing (e.g. faster, deeper) to influence the ECG signals? Show screenshots of ECG signals in different respiratory circumstances and described the variations if there are any**
Sí, en las señales analizadas se evidencia que los cambios en la respiración influyen en el ECG. Durante las fases de mantenimiento de la respiración, la señal se mantiene relativamente estable. En contraste, durante condiciones posteriores a la actividad aeróbica, donde la respiración es más rápida y profunda, se observa un aumento en la frecuencia cardíaca y una mayor variabilidad en la señal. Además, se aprecian pequeñas variaciones en la amplitud, lo cual puede estar asociado al movimiento del tórax y a cambios en la posición relativa entre el corazón y los electrodos. Estos resultados confirman la interacción entre el sistema respiratorio y cardiovascular. 

**e. In Home-Guide #1 you have seen that different amounts of force produced in the muscle generated signals with different amplitudes. How does movement influence your ECG signal?** 
El movimiento tiene un impacto evidente en la señal ECG observada. En las etapas posteriores a la actividad aeróbica, la señal presenta mayor ruido y menor estabilidad en la línea base en comparación con el reposo basal. Asimismo, se observa que los complejos QRS, aunque siguen siendo identificables, están acompañados de fluctuaciones adicionales que dificultan su análisis preciso. Esto se debe tanto al desplazamiento de los electrodos como a la interferencia de la actividad muscular que introduce componentes de alta frecuencia en la señal de manera que se reduce la calidad de la señal y complica su interpretación. 

**f. To the best of your knowledge, how can you detect bradycardia and tachycardia in the ECG signal?** 
La bradicardia y la taquicardia se pueden detectar observando la distancia entre los picos R del ECG. Cuando los picos R están más separados significa que el corazón late más lento lo que podría indicar bradicardia. En cambio, cuando los picos R están más juntos indica que el corazón late más rápido lo que correspondería a taquicardia. También se puede estimar la frecuencia cardíaca contando los latidos en un intervalo de tiempo. En las señales analizadas, después de la actividad física se puede notar que los picos están más seguidos, lo que indica un aumento de la frecuencia cardíaca.




