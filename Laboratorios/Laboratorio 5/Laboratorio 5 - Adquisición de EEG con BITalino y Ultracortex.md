
# **LABORATORIO 5: Adquisicion de señales EEG con BITalino y Ultracortex**


## **1. Introducción** 
La electroencefalografía (EEG) es una técnica de monitoreo no invasiva utilizada para registrar la actividad eléctrica cerebral mediante electrodos colocados sobre el cuero cabelludo. Las señales EEG reflejan la actividad neuronal del cerebro y se caracterizan por presentar diferentes bandas de frecuencia, las cuales se asocian con diversos estados fisiológicos, cognitivos y emocionales [1,2]. Entre las principales se encuentran las ondas delta (0–4 Hz), relacionadas con el sueño profundo y procesos de recuperación; las ondas theta (4–8 Hz), asociadas con estados de relajación, somnolencia y memoria; las ondas alfa (8–12 Hz), presentes principalmente durante estados de calma y relajación con ojos cerrados; las ondas beta (12–25 Hz), vinculadas con la atención, concentración y actividad mental activa; y las ondas gamma (>25 Hz), relacionadas con funciones cognitivas superiores como el aprendizaje y el procesamiento de información [2,3].



En el presente laboratorio se empleará el sistema BITalino junto con el casco OpenBCI Ultracortex para adquirir y analizar señales EEG bajo diferentes condiciones experimentales. Las pruebas incluirán estados de reposo, concentración visual, resolución de tareas cognitivas y exposición a estímulos auditivos como música y sonidos modulados en frecuencias alfa y beta. El análisis de estas condiciones permitirá observar cambios en la actividad cerebral y reconocer la predominancia de determinadas bandas de frecuencia dependiendo del nivel de relajación, atención o estimulación mental del participante.
<p align="center"> <img width="1685" height="1345" alt="brain-waves-bitbrain_0" src="https://github.com/user-attachments/assets/ddb90b99-b756-4b94-b532-a437c052222c" />


  
</p>


## **Electroencefalograma**

El electroencefalograma (EEG) es el registro gráfico de la actividad eléctrica generada por las neuronas del cerebro. Esta actividad se obtiene mediante electrodos colocados sobre el cuero cabelludo, los cuales detectan pequeñas diferencias de potencial producidas principalmente por la actividad sincrónica de las neuronas corticales. Debido a que las señales EEG poseen amplitudes muy pequeñas, generalmente del orden de microvoltios, es necesario emplear sistemas de adquisición y amplificación adecuados para poder registrarlas y analizarlas correctamente.

Las señales EEG se caracterizan por presentar diferentes bandas de frecuencia, cada una asociada a determinados estados fisiológicos y cognitivos. Las ondas delta predominan durante el sueño profundo, las theta aparecen en estados de somnolencia o relajación, las alfa se observan principalmente cuando la persona está relajada con los ojos cerrados, mientras que las beta se relacionan con estados de alerta y concentración. Asimismo, las ondas gamma suelen asociarse con procesos cognitivos complejos como el aprendizaje y el procesamiento de información.

El EEG es ampliamente utilizado en aplicaciones médicas y de investigación debido a que permite evaluar la actividad cerebral de manera no invasiva y en tiempo real. Entre sus principales aplicaciones se encuentran el diagnóstico de trastornos neurológicos, el monitoreo del sueño, el análisis de epilepsia, la evaluación cognitiva y el desarrollo de interfaces cerebro-computadora (BCI). En este laboratorio, el EEG permitirá analizar cómo varía la actividad cerebral frente a diferentes estímulos y tareas cognitivas utilizando BITalino y OpenBCI Ultracortex como sistemas de adquisición de señales.

<p align="center"> <img width="275" height="183" alt="images" src="https://github.com/user-attachments/assets/489942ed-d315-4489-a2db-11cd73814282" />
</p>


  
## **2. Objetivos de la práctica** 
- Registrar la señal EEG de un integrante del grupo durante la exposición a diferentes estímulos.
- Configurar de manera adecuada el dispositivo BiTalino.
- Representar gráficamente las señales EEG utilizando el software OpenSignals (r)evolution.
- Interpretar y analizar los datos obtenidos a partir del registro.
  
## **3. Materiales e instrumentos** 

- **Batería 3.7V:** Fuente de alimentación portátil para el funcionamiento del kit BiTalino.
- **Software OpenSignals:** Herramienta utilizada para la adquisición y visualización de las señales EEG.
- **Software OpenBCI:** Programa de apoyo para la configuración y análisis de registros neurofisiológicos.
- **Electrodos de superficie descartables:** Dispositivos que permiten captar la actividad eléctrica cerebral de manera no invasiva.
- **Cable de los 3 electrodos:** Conector necesario para enlazar los electrodos con el sistema de registro.
- **Kit BiTalino:** Plataforma biomédica empleada para la adquisición de señales EEG y otros biosignales.
- **UltraCortex:** Casco con electrodos secos que facilita la colocación en posiciones específicas del sistema 10-20.
- **Laptop:** Equipo de cómputo utilizado para ejecutar el software de registro, almacenamiento y análisis de datos.


## **4. Metodología**
Para adquirir las señales EEG el participante realizó una secuencia de activades con el fin de observar variaciones en la actividad cerebral acorde a las tareas que realizaba. El experimento fue en un ambiente controlado con los electrodos EEG conectados al sistema Bitalino para ser visualizados en el software OpenSignals.

### Secuencia de actividades 
**1. Estado Basal:** La persona debe tener los ojos y oídos tapados, asimismo debe evitar el movimiento facial. Se registra 1 minuto esta señal.

**2. Punto Fijo:** Se desprende la venda de los ojos del sujeto para que mire a un punto fijo durante 1 minuto y se registra esa señal emitida.

**3. Estado Basal:** Se pone al sujeto bajo las condiciones del primer estado y se registra esta señal por 30 segundos.

**4. Parpadeo y masticación:** Se le solicita al sujeto que mastique y parpadee 2 veces con un espacio de 2 segundos entre cada evento. Esta señal debe ser registrada durante 30 segundos 

**5. Estado Basal:** Se pone al sujeto bajo las condiciones del primer estado y se registra esta señal por 30 segundos.

**6. Musica:** El participante es expuesto a música relajante y estresante durante 1 minuto y se registra esa señal.

**7. Estado Basal:** Se pone al sujeto bajo las condiciones del primer estado y se registra esta señal por 30 segundos.

**8. Preguntas:** Se le realiza 3 preguntas sencillas a la persona y se toma la primera señal en el espacio de tiempo que demore el interrogatorio. Luego, se le realizan 3 preguntas complejas y se registra una segunda señal.

### Secuencia de actividades 
**1. Colocación de electrodos:** Se limpia la zona de colocación de electrodos (zona superior a la ceja).

**2. Registro de la señal:** Con ayuda del módulo Bitalino se adquiere la señal EEG que podran ser visualizadas en OpenSignals con la configuración correcta.

<p align="center"> c<img width="162" height="200" alt="ELECTRODOS" src="https://github.com/user-attachments/assets/d7e88d92-b304-4792-a6f0-ce1c183a4265" />

<p align="center"> Posicionamiento de electrodos

**1. Reposo**  
| **Toma en estado basal** |
|:------------------:|
| <video src="https://github.com/user-attachments/assets/a7f11d15-dee7-4687-8d2e-20ecfa87e194" controls></video> |

---


**2. Mirada fija**  
| **Video** |
|:----------:|
| <video src="https://github.com/user-attachments/assets/ab0c3054-fd72-4db9-aec0-4b515b6e10a5" controls></video> | 


---



**3. Parpadeo y masticación**  
| **Toma 1** | 
|:----------:|
| <video src="https://github.com/user-attachments/assets/64debdcc-d5cd-4d4f-a3a3-3b461f2b2232" controls></video> | 


---



**4. Música relajante**  
| **Toma 1** |
|:----------:|
| <video src="https://github.com/user-attachments/assets/f9fdfee1-38ca-4d3c-ab32-e3ce8b9ccee1" controls></video> | 

---
**5. Música estresante**  
| **Toma 1** | 
|:----------:|
| <video src="https://github.com/user-attachments/assets/3415fea3-d826-46c6-b3b1-5e36822ddc11" controls></video> | 

## **5. Procesamiento de datos** 
En lo que respecta a los resultados utilizaremos el archivo "CodigosEEG_BITalino.ipynb", el cual se encuentra dentro del mismo folder. El archivo "CodigosEEG_BITalino.ipynb" es el que tiene todos los códigos hechos para la visualización de las gráficas de las señales adquiridas. También incluye su correspondiente filtrado y análisis de frecuencia. 
### a)Importamos las Librerías
Se importan las librerías a utilizar para graficar las señales.
```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.signal import butter, filtfilt, iirnotch
```

### b) Cargamos los archivos
Se cargan los archivos .txt que contienen las señales obtenidas del software OpenSignals.
```python
datos = np.loadtxt("resta1.txt", delimiter=None, comments="#")
eeg = datos[:, 5] #La señal se encuentra en la 5 columna

fs = 1000  
t = np.arange(len(eeg)) / fs
```

### c) Aplicación de filtros
La señal EEG refleja la suma de potenciales postsinápticos de grandes poblaciones neuronales y se caracteriza por ser compleja, dinámica y de baja amplitud, con componentes que se distribuyen principalmente en un rango de frecuencias entre 1 y 30 Hz.
- Pasa-banda (0.5 Hz-40Hz): Este rango permite preservar las oscilaciones cerebrales de interés (δ, θ, α, β y parte de γ), mientras se atenúan artefactos de baja frecuencia (movimientos, sudoración y derivas lentas de electrodos) y de alta frecuencia (actividad muscular e interferencia electromagnética). De este modo, se mejora la relación señal-ruido y se garantiza que los análisis en dominios de tiempo y frecuencia se centren en la actividad cerebral relevante [a].
- Filtro Notch: Reduce la interferencia de la red eléctrica.
### d) Ploteo de las señales
Se realizó el ploteo de las señales crudas y filtradas, así como de sus respectivos FFT en amplitud y dB, análisis Welch y PSP.

#### d.1 Señales obtenidas con sensor EEG con SnapBIT-DUO
##### 1. Reposo basal
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="827" height="582" alt="image" src="https://github.com/user-attachments/assets/6eb1273f-e9d8-4e76-9ed5-edd4de4fdf46" />|<img width="827" height="657" alt="Captura de pantalla 2026-05-17 224029" src="https://github.com/user-attachments/assets/09860e05-736b-4802-992e-ba37ba45a1e1" />|
| PSD  |<img width="512" height="257" alt="image" src="https://github.com/user-attachments/assets/247dadfd-ba93-4303-8e6a-6973a9cf7e11" />|<img width="852" height="422" alt="Captura de pantalla 2026-05-17 224049" src="https://github.com/user-attachments/assets/6a03334b-a0f5-4493-87f3-c533e88dce5d" />|

##### 2. Mirada fija
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="752" height="611" alt="Captura de pantalla 2026-05-17 223715" src="https://github.com/user-attachments/assets/1c1e8f96-492c-4e2a-b5c1-edcb0df47e49" />|<img width="821" height="642" alt="image" src="https://github.com/user-attachments/assets/e53b65e4-d429-4918-825b-62e37aa8a7e7" />|
| PSD  |<img width="861" height="392" alt="image" src="https://github.com/user-attachments/assets/b59cfbbb-8a6e-418b-9887-740f24478afd" />|<img width="831" height="432" alt="image" src="https://github.com/user-attachments/assets/aad4eda8-2f70-481f-a4e8-5756f41f5950" />|

##### 3. Segundo reposo basal con ojos cerrados
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="652" height="466" alt="image" src="https://github.com/user-attachments/assets/b49e28bc-bb5f-49f2-9ef2-dd85c8f28c07" />|<img width="637" height="442" alt="image" src="https://github.com/user-attachments/assets/b46942f2-9a0c-4998-a2f7-b99d92d849fb" />|
| PSD  |<img width="607" height="287" alt="image" src="https://github.com/user-attachments/assets/8fcce4b2-5b93-4556-a500-ffee1eb82dfa" />|<img width="532" height="260" alt="image" src="https://github.com/user-attachments/assets/580a1a6f-ec1d-4176-b523-8baf8f961f21" />|

##### 4. Artefactos: parpadeo y masticación. Segundo reposo basal con ojos cerrados
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="832" height="685" alt="image" src="https://github.com/user-attachments/assets/3581aa00-23eb-4fce-b2ec-a73a5b382413" />|<img width="842" height="642" alt="image" src="https://github.com/user-attachments/assets/257da837-f754-4fc5-8f8c-1adc4b3b0107" />|
| PSD  |<img width="836" height="406" alt="image" src="https://github.com/user-attachments/assets/fed5aa63-cfb1-4508-b331-37a5bcc8a3af" />|<img width="852" height="401" alt="image" src="https://github.com/user-attachments/assets/8c3916bb-c2a4-4f60-a199-c4be39c4a0e7" />|

##### 5. Tercer reposo basal con ojos cerrados
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="742" height="547" alt="image" src="https://github.com/user-attachments/assets/79436202-0096-4b60-924c-342a7b2f8d7a" />|<img width="835" height="640" alt="image" src="https://github.com/user-attachments/assets/af6a5ccf-f0b6-4fa1-9e8c-8066ad6fd534" />|
| PSD  |<img width="847" height="402" alt="image" src="https://github.com/user-attachments/assets/22f71824-842c-46fa-bacf-115d03d97025" />|<img width="837" height="372" alt="image" src="https://github.com/user-attachments/assets/462a162d-4c70-4092-96a2-642e862fddb0" />|

##### 6. Tarea cognitiva / preguntas sencillas
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="832" height="625" alt="image" src="https://github.com/user-attachments/assets/4b308e4c-99b3-47ce-97f2-42d770cb6ced" />|<img width="847" height="652" alt="image" src="https://github.com/user-attachments/assets/febb6891-77df-4adf-b8e1-72de60dcf2ec" />|
| PSD  |<img width="832" height="407" alt="image" src="https://github.com/user-attachments/assets/91958484-25c3-49e3-b7e5-0038efa3124c" />|<img width="821" height="392" alt="image" src="https://github.com/user-attachments/assets/72c79879-58d8-44bd-887d-b4ef5f737f72" />|

##### 7. Tarea cognitiva / preguntas complejas
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="852" height="762" alt="image" src="https://github.com/user-attachments/assets/015c11e9-d053-4f58-92cd-d89547a5af26" />|<img width="821" height="590" alt="image" src="https://github.com/user-attachments/assets/b9caaa7e-5363-4453-b5ca-505d33606fd1" />|
| PSD  |<img width="840" height="405" alt="image" src="https://github.com/user-attachments/assets/2beeb9d9-eb13-4ee7-9090-da592eff3787" />|<img width="862" height="397" alt="image" src="https://github.com/user-attachments/assets/da48ba1a-c91f-4c8b-812a-8b204536986b" />|

##### 8.  Actividad libre: música relajante
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="837" height="472" alt="image" src="https://github.com/user-attachments/assets/196d187e-5b44-45f0-9e16-ea16f14d1682" />|<img width="857" height="577" alt="image" src="https://github.com/user-attachments/assets/2af02e09-c3db-4089-a5a1-347ac5ea7106" />|
| PSD  |<img width="741" height="347" alt="image" src="https://github.com/user-attachments/assets/4ddeebcd-f8bc-40d1-b345-b94ed47982c2" />|<img width="662" height="312" alt="image" src="https://github.com/user-attachments/assets/bfc7c89d-24c7-4958-a033-4e86d0fe42d9" />|

##### 9.  Actividad libre: música estresante
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="837" height="640" alt="image" src="https://github.com/user-attachments/assets/016cc8fa-df9b-44ab-a515-701addd0259a" />|<img width="847" height="647" alt="image" src="https://github.com/user-attachments/assets/1d09fcdf-6c80-4b78-8167-20db47082b6e" />|
| PSD  |<img width="852" height="412" alt="image" src="https://github.com/user-attachments/assets/cb1f713d-a052-488a-91e8-56865fb8b9cb" />|<img width="837" height="395" alt="image" src="https://github.com/user-attachments/assets/0fef8fd4-5fd8-4c10-a484-e3e997e0550e" />|

#### d.2 Señales obtenidas con electrodos adhesivos
##### 1. Reposo basal
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="572" height="450" alt="image" src="https://github.com/user-attachments/assets/61919007-216c-44c0-bdaa-965e061dcb54" />|<img width="797" height="610" alt="image" src="https://github.com/user-attachments/assets/64c6c457-02c6-4c5f-85e0-d64082a0e84d" />|
| PSD  |<img width="617" height="300" alt="image" src="https://github.com/user-attachments/assets/04c6b084-1cdd-498d-80f9-dcf8e772d547" />|<img width="595" height="275" alt="image" src="https://github.com/user-attachments/assets/e4ef1e20-aa83-4bfe-aa4a-e96920ec5830" />|

##### 2. Mirada fija
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="656" height="487" alt="image" src="https://github.com/user-attachments/assets/dd7ce928-43fc-46c0-83bc-6c18470ed58f" />|<img width="695" height="477" alt="image" src="https://github.com/user-attachments/assets/6481c2ad-8447-48eb-9018-cdff7f8d27f2" />|
| PSD  |<img width="657" height="297" alt="image" src="https://github.com/user-attachments/assets/972c29fb-34ee-4144-afa9-d0757343bf55" />|<img width="617" height="305" alt="image" src="https://github.com/user-attachments/assets/147ac4fe-9726-4348-9cd1-bab297ca35e7" />|

##### 3. Segundo reposo basal con ojos cerrados
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="715" height="556" alt="image" src="https://github.com/user-attachments/assets/ce471b80-66aa-4e9e-bb73-018168b6555e" />|<img width="857" height="642" alt="image" src="https://github.com/user-attachments/assets/a6ec7c48-2418-4fcd-a77e-2b2754c61aa3" />|
| PSD  |<img width="576" height="281" alt="image" src="https://github.com/user-attachments/assets/051fe22e-18a8-4c33-9195-82c05965dd12" />|<img width="832" height="396" alt="image" src="https://github.com/user-attachments/assets/da88af17-0201-42df-9158-cdfb8e797212" />|

##### 4. Artefactos: parpadeo y masticación. Segundo reposo basal con ojos cerrados
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="542" height="397" alt="image" src="https://github.com/user-attachments/assets/813b8a73-044e-423f-ae58-01cc0e7b2910" />|<img width="862" height="627" alt="image" src="https://github.com/user-attachments/assets/2cc160a9-88d9-4ae1-842e-bbe6b1a835da" />|
| PSD  |<img width="707" height="335" alt="image" src="https://github.com/user-attachments/assets/684e79fa-3c5a-4243-a3fb-78074f4c5020" />|<img width="702" height="330" alt="image" src="https://github.com/user-attachments/assets/b757cdeb-4f5e-4334-9b0a-3dad75ab208a" >|

##### 5. Tercer reposo basal con ojos cerrados
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="817" height="617" alt="image" src="https://github.com/user-attachments/assets/c7b805d5-1b94-43ca-b9bb-8c36874e4bdd" />|<img width="857" height="647" alt="image" src="https://github.com/user-attachments/assets/2e67e2d2-7ff7-4a31-972a-82d195a95764" />|
| PSD  |<img width="835" height="382" alt="image" src="https://github.com/user-attachments/assets/6f31bf05-02ca-44e5-8849-6651c40eba06" />|<img width="686" height="336" alt="image" src="https://github.com/user-attachments/assets/da43a345-5797-4951-a82f-86af8fa57758" />|

##### 6. Tarea cognitiva / preguntas sencillas
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="832" height="652" alt="image" src="https://github.com/user-attachments/assets/0b7079ac-6812-4960-a50c-0f7d8eaf45c3" />|<img width="841" height="646" alt="image" src="https://github.com/user-attachments/assets/52f5f8c6-8203-4d8a-aa67-d52175213d8d" />|
| PSD  |<img width="840" height="400" alt="image" src="https://github.com/user-attachments/assets/7e03da61-b30b-4683-b98b-7f937e4f70f6" />|<img width="852" height="397" alt="image" src="https://github.com/user-attachments/assets/9f9cf35f-49c4-4a9f-bcee-2809ae5528c9" />|

##### 7. Tarea cognitiva / preguntas complejas
| Tipo                 | Señal original | Señal filtrada    |                    
|-------------------------|----------|---------------------------------|
|Ploteo   |<img width="846" height="670" alt="image" src="https://github.com/user-attachments/assets/82d4142c-f428-45a4-b4d2-0cd57cd00f74" />|<img width="822" height="617" alt="image" src="https://github.com/user-attachments/assets/67bda3d4-5ff9-41e4-a201-4b48d80cc408" />|
| PSD  |<img width="831" height="407" alt="image" src="https://github.com/user-attachments/assets/c262dd84-2aae-4b41-94e2-ead80290a5c8" />|<img width="852" height="417" alt="image" src="https://github.com/user-attachments/assets/b8ee286a-fdd2-4b93-8acd-616ff55b1cf0" />|

##### 8.  Actividad libre: música 
| Tipo                 | Señal original | PSD    |                    
|-------------------------|----------|---------------------------------|
|Relajante  |<img width="860" height="680" alt="image" src="https://github.com/user-attachments/assets/123e5149-457a-43f9-afd2-538360fefe46" />|<img width="846" height="392" alt="image" src="https://github.com/user-attachments/assets/3b0d3d4a-844c-4026-a9c4-61b193fae691" />|
|Estresante |<img width="842" height="645" alt="image" src="https://github.com/user-attachments/assets/4e055131-815e-49f1-9196-073f7007ec43" />|<img width="832" height="395" alt="image" src="https://github.com/user-attachments/assets/b1ae429e-27d5-41eb-b700-505462363248" />|

## **6. Discusión y resultados**
- Reposo: En la gráfica de PSD se observa que tanto en la señal cruda como filtrada, la banda delta presenta mayor potencia, seguida de beta y theta. Lo ideal sería que al estar en reposo la banda theta presente mayor potencia ya que está asociada a la somnolencia ligera y relajación, no obstante se ve mayor potencia en delta y beta, la cual está relacionada con estados de alerta y tensión mental, lo que indica que la persona evaluada mantenía un nivel de tensión mental a pesar del intento de mantener la calma. Por parte de la banda gamma, se ve reducida considerablemente ya que es clave en la atención de tareas complejas donde se involucra el razonamiento; resultado esperado ya que el voluntario se encontraba en reposo.
- Mirada Fija: En ambas tomas se observa que predomina la potencia en las bandas theta,beta y alfa respectivamente. El predominio de theta puede indicar cierto nivel de fatiga, somnolencia o baja activación, podría deberse a artefactos relacionados con el parpadeo o el movimiento ocular. La banda beta está asociada a procesos de atención y concentración, que son necesarios para mantener la mirada fija sin distraerse mientras que la presencia de alfa en menor medida es coherente ya que esta banda normalmente predomina con ojos cerrados y se reduce cuando el sujeto abre los ojos o dirige su atención a estímulos visuales, fenómeno conocido como bloqueo alfa o desincronización alfa.
- Ojos cerrados (sin luz): En ambas tomas predominan en orden las bandas theta, beta y alfa. El resultado difiere a lo esperado ya que la banda que debería presentar mayor potencia debería ser la alfa, relacionada a la relajación y desconexión visual; esto podría deberse a que el sujeto no alcanzó un nivel de calma sficiente además de presentar ruidos musculares o eléctricos, lo que explicaría la presencia de las bandas beta y theta.
- Parpadeo cada 2 segundos: El parpadeo voluntario es un estímulo motor simple que suele generar actividad de corta duración y, en general, no altera de forma significativa la distribución de bandas. El predominio de theta podría indicar que el sujeto experimentó desconexión atencional o somnolencia, incluso durante la tarea. Beta en segundo lugar refleja la activación motora y sensorial asociada al parpadeo, mientras que la alfa en tercer lugar confirma que no se consolidó un estado de relajación estable durante la tarea. Este comportamiento puede deberse tanto a factores individuales (cansancio, falta de concentración) como a la presencia de artefactos musculares u oculares que enmascararon la actividad típica.
- Resta desde 100 a 0: Durante esta tarea cognitiva, el sujeto restó 7 desde el 100 al 0. El análisis espectral mostró predominio de theta, beta y alfa, mientras que gamma se mantuvo mucho menor en comparación con las demás bandas. Beta está asociada al esfuerzo mental y a la concentración, así como gamma, vinculada al procesamiento cognitivo de alto nivel y la integración de información. Sin embargo, en este caso el predominio de la theta podría reflejar fatiga mental o distracción, lo que difiere con lo esperado. La baja expresión de alfa es coherente, ya que la tarea demanda atención sostenida y evita estados de relajación. En cuanto a la gamma, su marcada reducción puede indicar que el sujeto no alcanzó un nivel elevado de procesamiento cortical sincronizado, ya sea por la dificultad de la tarea,o por la presencia de ruido, hipótesis comprobada ya que el sujeto mencionó que le costó hacer las restas sucesivas.
- Actividad libre-Escuchar música: Durante esta actividad se reprodujeron videos que contenían ondas alfa, beta y una canción de libre elección por parte del evaluador. El resultado de las bandas fue el mismo en las 3 situaciones, predominó theta por poco sobre beta. Esta similitud de potencia puede deberse a que la música activa procecsos emocionales que generan relajo (banda theta) a la par de que requiere atención y procesamiento cognitivo (banda beta). La combinación de ambos refleja cómo el cerebro responde de manera integrada al estímulo musical favoreciendo un estado de relajación y manteniendo la atención e interpretación del estímulo. Además, se evidenció un ligero incremento en la banda gamma, lo que resulta coherente, ya que la música suele activar la sincronización cortical asociada con la integración multisensorial y la experiencia emocional.[4]
- Respondiendo preguntas: Las preguntas que se realizaron fueron de complejidad media, por lo que el resultado esperado era el predominio de la banda gamma; sin embargo la potencia fue baja en comparación al resto de bandas. Esto puede deberse a que la demanda cognitiva no fue lo suficientemente elevada como para activar con fuerza esta banda, o a que el sujeto procesó la tarea de manera más superficial explicada por la ausencia de integración cortical más profunda. El mantenimiento del predominio en theta refleja carga mental o somnolencia.

## **7. Referencias**

[1] E. Niedermeyer and F. L. da Silva, Electroencephalography: Basic Principles, Clinical Applications, and Related Fields, 5th ed. Philadelphia, PA: Lippincott Williams & Wilkins, 2004.

[2] E. Başar, C. Başar-Eroglu, S. Karakaş, and M. Schürmann, "Brain oscillations in perception and memory," International Journal of Psychophysiology, vol. 35, no. 2–3, pp. 95–124, 2000, doi: 10.1016/S0167-8760(99)00047-1.

[3] G. Buzsáki and A. Draguhn, "Neuronal oscillations in cortical networks," Science, vol. 304, no. 5679, pp. 1926–1929, 2004, doi: 10.1126/science.1099745.




