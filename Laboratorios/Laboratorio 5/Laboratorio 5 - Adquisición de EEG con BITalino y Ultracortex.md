# **LABORATORIO 5: Adquisicion de señales EEG con BITalino y Ultracortex**


## **1. Introducción** <a name="id1"></a>
La electroencefalografía (EEG) es una técnica de monitoreo no invasiva utilizada para registrar la actividad eléctrica cerebral mediante electrodos colocados sobre el cuero cabelludo. Las señales EEG reflejan la actividad neuronal del cerebro y se caracterizan por presentar diferentes bandas de frecuencia, las cuales se asocian con diversos estados fisiológicos, cognitivos y emocionales [1,2]. Entre las principales se encuentran las ondas delta (0–4 Hz), relacionadas con el sueño profundo y procesos de recuperación; las ondas theta (4–8 Hz), asociadas con estados de relajación, somnolencia y memoria; las ondas alfa (8–12 Hz), presentes principalmente durante estados de calma y relajación con ojos cerrados; las ondas beta (12–25 Hz), vinculadas con la atención, concentración y actividad mental activa; y las ondas gamma (>25 Hz), relacionadas con funciones cognitivas superiores como el aprendizaje y el procesamiento de información [2,3].



En el presente laboratorio se empleará el sistema BITalino junto con el casco OpenBCI Ultracortex para adquirir y analizar señales EEG bajo diferentes condiciones experimentales. Las pruebas incluirán estados de reposo, concentración visual, resolución de tareas cognitivas y exposición a estímulos auditivos como música y sonidos modulados en frecuencias alfa y beta. El análisis de estas condiciones permitirá observar cambios en la actividad cerebral y reconocer la predominancia de determinadas bandas de frecuencia dependiendo del nivel de relajación, atención o estimulación mental del participante.
<p align="center"> <img src="https://i.pinimg.com/736x/18/18/8f/18188fdb48dd3a434b2b5e0472f7bcc3.jpg" alt="Ondas cerebrales EEG" width="450"><br> <em>

## **Electroencefalograma** <a name="id2"></a> 

En el registro electroencefalográfico, los electrodos se distribuyen siguiendo el sistema internacional 10-20, que asigna nombres según la región cerebral: frontopolar (Fp), frontal (F), central (C), temporal (T), parietal (P) y occipital (O). Para diferenciar la lateralidad, se emplean números: los impares (1, 3, 5, 7) corresponden al hemisferio izquierdo, mientras que los pares (2, 4, 6, 8) se colocan en el hemisferio derecho [4]. 

<p align="center"> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSr1ZnUnIs5k6OW3BSKt5xHgdYpOe-XpAUKQw&s" alt="Ondas cerebrales EEG" width="450"><br> <em>

  
## **2. Objetivos de la práctica** <a name="id2"></a>
- Registrar la señal EEG de un integrante del grupo durante la exposición a diferentes estímulos.
- Configurar de manera adecuada el dispositivo BiTalino.
- Representar gráficamente las señales EEG utilizando el software OpenSignals (r)evolution.
- Interpretar y analizar los datos obtenidos a partir del registro.
  
## **3. Materiales e instrumentos** <a name="id3"></a>
| Materiales                                   | Cantidad | Imagen                          |
|----------------------------------------------|----------|---------------------------------|
| Batería 3.7V                                 | 1        | ![bateria](https://github.com/user-attachments/assets/25fe9643-a7fa-4bd9-85ad-e1ce78a926ab) |
| Software OpenSignals                         | 1        | ![opensignals](https://github.com/user-attachments/assets/270de790-173f-42fc-9960-5b12a7fff042) |
| Electrodos de superficie descartables        | 3        | ![electrodos (1)](https://github.com/user-attachments/assets/2e58ad27-7c4a-4336-9fdf-fe54129be397) |
| Cable de los 3 electrodos                    | 1        | ![cable](https://github.com/user-attachments/assets/2d397e32-3ec4-4982-91fe-0d6855e3aec0) |
| Kit BITalino                                 | 1        | ![bitalino](https://github.com/user-attachments/assets/a60c127f-27c2-4a03-b852-454d23f54163) |
| Laptop                                       | 1        | ![laptop](https://github.com/user-attachments/assets/c1394461-1a65-41fc-b6f4-8d8ae5b3b37b) |


## Descripción de materiales: 
- **Batería 3.7V:** Fuente de alimentación portátil para el funcionamiento del kit BiTalino.
- **Software OpenSignals:** Herramienta utilizada para la adquisición y visualización de las señales EEG.
- **Software OpenBCI:** Programa de apoyo para la configuración y análisis de registros neurofisiológicos.
- **Electrodos de superficie descartables:** Dispositivos que permiten captar la actividad eléctrica cerebral de manera no invasiva.
- **Cable de los 3 electrodos:** Conector necesario para enlazar los electrodos con el sistema de registro.
- **Kit BiTalino:** Plataforma biomédica empleada para la adquisición de señales EEG y otros biosignales.
- **UltraCortex:** Casco con electrodos secos que facilita la colocación en posiciones específicas del sistema 10-20.
- **Laptop:** Equipo de cómputo utilizado para ejecutar el software de registro, almacenamiento y análisis de datos.

