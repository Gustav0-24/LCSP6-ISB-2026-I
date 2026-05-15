# **LABORATORIO 5: Adquisicion de señales EEG con BITalino y Ultracortex**


## **1. Introducción** <a name="id1"></a>
La electroencefalografía (EEG) es una técnica no invasiva que permite registrar la actividad eléctrica del cerebro mediante electrodos colocados en el cuero cabelludo. Esta actividad se organiza en diferentes ritmos u ondas cerebrales, clasificados según su frecuencia y asociados a distintos estados fisiológicos y cognitivos [1,2]. Las ondas delta (0–4 Hz) predominan durante el sueño profundo y se relacionan con procesos de descanso y recuperación. Las ondas theta (4–8 Hz) se vinculan a estados de somnolencia y a la memoria de trabajo. Las ondas alfa (8–12 Hz) aparecen en condiciones de reposo y relajación, especialmente con los ojos cerrados, y se asocian a la atención y la meditación. Por su parte, las ondas beta (12–25 Hz) reflejan estados de alerta, concentración activa y control motor. Finalmente, las ondas gamma (>25 Hz) se relacionan con el procesamiento cognitivo rápido, la memoria y la resolución de problemas [2,3]. En este laboratorio se busca registrar y analizar señales EEG en diferentes condiciones: reposo, fijación de la mirada en un punto, resolución de preguntas cognitivas y exposición a estímulos auditivos, tanto de música de preferencia personal como de sonidos modulados en frecuencias características de ondas alfa y beta. Estas variaciones permiten identificar cómo el cerebro responde a distintos estados de atención, relajación o activación, así como reconocer la predominancia de determinadas bandas de frecuencia en cada escenario.
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

