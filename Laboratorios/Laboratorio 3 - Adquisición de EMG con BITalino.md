



# **LABORATORIO 3: Uso de BITalino para EMG**

## **1. Introducción**

La electromiografía es una técnica utilizada para evaluar la actividad eléctrica de los músculos de manera no invasiva. Tiene como fundamento el reconocimiento de los potenciales eléctricos que son producidos por las fibras musculares durante su activación y por medio de ella se puede obtener información sobre la intensidad, duración y patrón de activación muscular. [1] Es importante mencionar que las señales obtenidas presentan amplitudes bajas, por lo cual se necesita acondicionarla para su lectura y análisis. Es por ello que se pueden utilizar sistemas como el Bitalino Revolution, pues permite la lectura por medio de electrodos e integra tanto la etapa de amplificación, digitalización, visualización y almacenamiento a través del software Open Signals. [2]

En este trabajo se analizaron las señales EMG de los músculo bicep braquial, y el trapecio superior. El primero se encarga principalmente de la flexión del codo y la potente supinación del antebrazo, ademas de la elevacion del hombro. [3], mientras que el trapecio superior se encuentra localizado en la región dorsal y cervical y permite acciones como la elevación de los hombros y la estabilización de la escápula, lo cual resulta fundamental en movimientos posturales y de carga. [4]

El estudio de ambos músculos es significativo debido a los roles que cumplen en las funciones biomecánicas y sus respectivos niveles de activación, lo que permite realizar un análisis comparativo de cómo varían las señales electromiográficas en distintas regiones del cuerpo. El análisis en condiciones de reposo y contracción muscular puede proporcionar información sobre la relación entre la actividad eléctrica y la función muscular.

De esta manera, en el presente documento se detallarán la adquisición y análisis de señales EMG de los músculos biceps braquial y trapecio superior utilizando un sistema de adquisición biomédica para observar el comportamiento de la actividad muscular en distintos estados de activación y en diferentes grupos musculares.



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
1. Se debe seleccionar el músculo a evaluar y limpiar la zona. De ser posible seleccionar una zona sin vellos para mejorar la impedancia de los electródos.
2. Colocar 2 electrodos (Positivo y Negativo) en el músculo objetivo y un tercer electrodo de referencia sobre una región electricamente muerta. En el presente laboratorio se eligio poner el electrodo en la cresta hiliaca (hueso de la cadera).
3. Sincronizar mediante protocolo Bluetooth el BITalino y la computadora con el software previamente instalado
4. Realizar las mediciones con el software de 3 diferentes ejercicios para cada músculo: en reposo, fuerza leve sin oposición y fuerza con oposición.

### **4.1. EMG - Biceps Braquial**
En primer lugar, se ajusta el sistema de adquisición mediante el software OpenSignals Revolution y el dispositivo BITalino. Se comprueba que la conexión y configuración del sensor EMG sean las adecuadas para obtener datos en tiempo real.

A continuación, se prepara al sujeto. Para disminuir la impedancia y optimizar la calidad de la señal, se limpia el área del bíceps braquial con alcohol. Después, se colocan los electrodos de superficie: dos electrodos activos se sitúan en la parte muscular del bíceps braquial (siguiendo el sentido de las fibras musculares) y uno de referencia, en un sitio óseo próximo, como el codo. [5] 

Cuando los electrodos están instalados, se comienza a captar la señal en OpenSignals. Para empezar, se registra la actividad muscular en reposo durante algunos segundos, garantizando que el músculo esté totalmente relajado. A continuación, el individuo debe realizar una contracción del bíceps (como por ejemplo, flexionando el codo contra resistencia) en un intervalo controlado y se registra la señal correspondiente. Este procedimiento tiene la posibilidad de repetirse varias veces para conseguir datos coherentes.

Por último, se almacenan y procesan las señales obtenidas, utilizando filtros (por ejemplo, de paso-banda o eliminación de ruido) con el fin de optimizar su calidad. A continuación, se examinan las diferencias entre las señales de reposo y contracción, llevando a cabo una valoración de la actividad eléctrica y de la amplitud del músculo para su interpretación adecuada. [6]

<img width="641" height="550" alt="image" src="https://github.com/user-attachments/assets/3b785460-04fd-43c8-9163-934d44616a94" />

A continuación, presentamos el material audiovisual del EMG en entranamiento con el biceps braquial:





### **4.3. EMG - Triceps** <a name="id6"></a>
En la literatura más reciente sobre electromiografía de superficie (EMG), se ha señalado la importancia de mantener protocolos estandarizados de colocación de electrodos en músculos como el bíceps y el tríceps. Un estudio publicado en 2025 destacó que, aunque las recomendaciones clásicas como las del proyecto SENIAM siguen siendo la base de la práctica actual, el foco de los nuevos trabajos está puesto en la integridad de los datos y la consistencia de los registros, más que en proponer cambios sustanciales en la ubicación de los electrodos [11]. Esto implica que la posición en el vientre muscular del tríceps continúa siendo válida, siempre y cuando se respete una correcta orientación y separación de los electrodos.
Del mismo modo, otra revisión también de 2025, aunque centrada en el tríceps sural, ofrece conclusiones relevantes que pueden extrapolarse al tríceps braquial. Este trabajo subraya la necesidad de reducir el crosstalk o interferencia de músculos adyacentes, así como de minimizar la variabilidad espacial en los registros EMG. Para lograrlo, recomienda mantener los electrodos alineados con las fibras musculares y situarlos en el vientre del músculo, lo que asegura un registro más selectivo y confiable [12].

<img width="654" height="476" alt="image" src="https://github.com/user-attachments/assets/581a91c7-ce45-4b64-a8a4-f2987a88e074" />

***Fig. 4.** Ubicación de electrodos para la realización de ejercicios [12]*

A continuación, presentamos el material audiovisual del EMG en entranamiento con el triceps:

<div align="center">
 
|  **Triceps en reposo**  | **Triceps sin oposición** | **Triceps con oposición** |
|:----------------------:|:------------------------:|:------------------------:|
| <video src="https://github.com/user-attachments/assets/122f538e-1267-4ab4-ba6d-a0584519151f" controls></video> | <video src="https://github.com/user-attachments/assets/5412d4e4-d70a-40e8-b306-6c804fc63fcb" controls></video> | <video src="https://github.com/user-attachments/assets/dc13e13e-e735-4437-a025-f35a0cd603c7" controls></video> |

</div>


## **5. Resultados** <a name="id7"></a>

Para los resultados haremos uso del archivo "CodigosEMG.ipynb" que se encuentra en el mismo folder. El cual contiene todos los codigos hechos para la visualización de las gráficas de las señales adquiridas. Asi como su respectivo filtrado y análisis de frecuencia.

### **5.1. Procesamiento y visualización de gráficas con python**
### a) Importar librerias
Importamos las librerias a utilizar que son comunes para el codigo de cada señal graficada.
```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.signal import butter, filtfilt, welch, iirnotch
```
### b) Cargar el archivo
Cargamos el archivo .txt según la ruta en la que este almacenada en el ordenador local (Se muestra el ejemplo para la señal del músculo Biceps Braquial en reposo)
```python
ruta = r"D:\IB PUCP - UPCH 2022\7mo Semestre\Introducción a las Señales Biomédicas\Lab 3 - Adquisicion EMG\pythoooooon\Biceps\Reposo\reposo1_biceps.txt"
datos = np.loadtxt(ruta, comments="#")
emg = datos[:, -1]  # señal EMG en la última columna
```
### c) Definimos variables de la señal para la visualización
```python
fs = 1000  # frecuencia de muestreo
tiempo = np.linspace(0, len(emg) / fs, len(emg))
```
### d) Graficamos la señal original
```python
plt.figure(figsize=(10, 4))
plt.plot(tiempo, emg, color="#00008B", linewidth=0.4)
plt.title("Señal EMG original - Biceps reposo")
plt.xlabel("Tiempo (s)")
plt.ylabel("Amplitud (uV)")
plt.grid()
plt.show()
```
### e) Filtramos la señal
```python
# Función filtro pasa-banda
def filtro_pasabanda(señal, f_muestreo, frec_baja=20.0, frec_alta=450.0, orden=4):
    nyquist = 0.5 * f_muestreo  
    bajo = frec_baja / nyquist
    alto = frec_alta / nyquist
    b, a = butter(orden, [bajo, alto], btype="band")
    return filtfilt(b, a, señal)

# Función filtro notch (60 Hz)
def filtro_notch(señal, f_muestreo, frec_notch=60.0, Q=30.0):
    """
    frec_notch = frecuencia a eliminar (Hz)
    Q = factor de calidad (entre más alto, más selectivo es el notch)
    """
    nyquist = 0.5 * f_muestreo
    w0 = frec_notch / nyquist
    b, a = iirnotch(w0, Q)
    return filtfilt(b, a, señal)
# Aplicacion de filtros
emg_filtrada = filtro_pasabanda(emg, fs)
emg_filtrada = filtro_notch(emg_filtrada, fs, frec_notch=60.0, Q=30.0)
```
### f) Graficamos la señal filtrada
```python
plt.figure(figsize=(10, 4))
plt.plot(tiempo, emg_filtrada, color="#006400", linewidth=0.4)
plt.title("Señal EMG filtrada - Biceps reposo")
plt.xlabel("Tiempo (s)")
plt.ylabel("Amplitud (uV)")
plt.grid()
plt.show()
```
### g) Graficamos el Periodograma de Welch
```python
frecs, psd = welch(emg_filtrada, fs, nperseg=1024)
plt.figure(figsize=(10, 4))
plt.semilogy(frecs, psd, color="purple")
plt.title("Densidad espectral de potencia (Welch) - Biceps reposo")
plt.xlabel("Frecuencia (Hz)")
plt.ylabel("PSD (uV²/Hz)")
plt.grid()
plt.show()
```
### h) Graficamos el Espectro de Frecuencias
```python
fft_vals = np.fft.rfft(emg_filtrada)
fft_freqs = np.fft.rfftfreq(len(emg_filtrada), 1/fs)
plt.figure(figsize=(10, 4))
plt.plot(fft_freqs, np.abs(fft_vals), color="darkred", linewidth=0.6)
plt.title("Espectro de frecuencias (FFT) - Biceps reposo")
plt.xlabel("Frecuencia (Hz)")
plt.ylabel("Amplitud")
plt.xlim(0, 500)
plt.grid()
plt.show()
```
### **5.2. EMG - Biceps Braquial**

| Entrenamiento                                   | Señal original | Señal filtrada                         |
|----------------------------------------------|----------|---------------------------------|
| Reposo                              | <img width="867" height="391" alt="image" src="https://github.com/user-attachments/assets/c16b9bc8-bdce-4fcc-9b4e-b33b1bd82a2a" />| <img width="847" height="391" alt="image" src="https://github.com/user-attachments/assets/b9769556-36ce-4faf-9fad-55ae2ef1dd7e" /> |
| Movimiento leve sin oposición                        | <img width="850" height="391" alt="image" src="https://github.com/user-attachments/assets/1d1b1b80-523d-46ac-918b-7e19b1e89abb" /> | <img width="853" height="391" alt="image" src="https://github.com/user-attachments/assets/2513ad6d-c603-49da-af74-559656b3eeae" /> |
| Movimiento acelerado       | <img width="850" height="391" alt="image" src="https://github.com/user-attachments/assets/ab4ae997-9c47-49a4-9402-0260dc1e01c1" />        | <img width="862" height="391" alt="image" src="https://github.com/user-attachments/assets/9aa04e88-00ff-4c14-98a7-cc5472db8d07" /> |
| Movimiento fuerte con oposición                   | <img width="859" height="391" alt="image" src="https://github.com/user-attachments/assets/c204fa2b-b28d-4d90-b56a-a35dd35ffcdc" />       | <img width="862" height="391" alt="image" src="https://github.com/user-attachments/assets/989336a7-0473-4f46-bf8f-6259bf8d8ff8" />|

| Entrenamiento                                   | Densidad Espectral de Potencia (Welch) | Espectro de Frecuencias (FFT)                         |
|----------------------------------------------|----------|---------------------------------|
| Reposo                              | <img width="863" height="391" alt="image" src="https://github.com/user-attachments/assets/a741e1e4-d86f-45d0-802d-435acf621f8b" />| <img width="873" height="391" alt="image" src="https://github.com/user-attachments/assets/10c59fd3-8c53-442b-a690-0fa0b30d3f50" /> |
| Movimiento leve sin oposición                        | <img width="877" height="391" alt="image" src="https://github.com/user-attachments/assets/8733ebf4-c1ed-431a-a688-7f636fb43460" /> | <img width="881" height="391" alt="image" src="https://github.com/user-attachments/assets/f03569db-0d55-448f-9c7e-0396bbf3a853" /> |
| Movimiento acelerado       | <img width="876" height="391" alt="image" src="https://github.com/user-attachments/assets/f0f058c3-9897-4a7b-8134-85a50fbe4643" />        | <img width="881" height="391" alt="image" src="https://github.com/user-attachments/assets/c7508e1b-b9ac-4116-95da-5e094450e5e7" /> |
| Movimiento fuerte con oposición                   | <img width="876" height="392" alt="image" src="https://github.com/user-attachments/assets/a72e87e1-6e37-48c1-bc20-15f5219cfa99" />       | <img width="890" height="392" alt="image" src="https://github.com/user-attachments/assets/857d8d64-e927-4129-8148-f0dddcf1b9e3" />|

### 5.3. EMG - Triceps
| Entrenamiento                                   | Señal original | Señal filtrada                         |
|----------------------------------------------|----------|---------------------------------|
| Reposo                              | <img width="850" height="391" alt="image" src="https://github.com/user-attachments/assets/8676c769-ad5d-4631-9343-7881bbf88504" /> | <img width="853" height="391" alt="image" src="https://github.com/user-attachments/assets/5b390bc0-006f-4f8d-8d59-d11abfa55797" /> |
| Movimiento leve sin oposición                        | <img width="850" height="391" alt="image" src="https://github.com/user-attachments/assets/b9d306f2-59c4-4a3e-9159-d60378883d1a" /> | <img width="853" height="391" alt="image" src="https://github.com/user-attachments/assets/d690bf7d-f351-428c-ba18-119ffb22c6a9" /> |
| Movimiento acelerado       | <img width="859" height="391" alt="image" src="https://github.com/user-attachments/assets/a97481da-37c2-4b32-b61d-0e9313cfd1f1" /> | <img width="862" height="391" alt="image" src="https://github.com/user-attachments/assets/f35858c7-14c3-4e0c-9362-41c60bbf696e" /> |
| Movimiento fuerte con oposición                   | <img width="850" height="391" alt="image" src="https://github.com/user-attachments/assets/5b7c9897-2e83-4b18-9700-099d2cd50754" /> | <img width="862" height="391" alt="image" src="https://github.com/user-attachments/assets/1e16657f-b5b2-4e3b-8c0a-a6034a05b19b" /> |

| Entrenamiento                                   | Densidad Espectral de Potencia (Welch) | Espectro de Frecuencias (FFT)                         |
|----------------------------------------------|----------|---------------------------------|
| Reposo                              | <img width="877" height="392" alt="image" src="https://github.com/user-attachments/assets/7cc4b043-3ee0-48c4-8065-6fbf648c6d52" />| <img width="873" height="392" alt="image" src="https://github.com/user-attachments/assets/2da0f01f-ec5e-4205-8f7b-758eee32db53" /> |
| Movimiento leve sin oposición                        | <img width="877" height="392" alt="image" src="https://github.com/user-attachments/assets/504d6ff9-d42e-44a7-8cf4-b540af2a7c40" /> | <img width="873" height="392" alt="image" src="https://github.com/user-attachments/assets/72d0e011-828b-4513-926a-c9ae3acea198" /> |
| Movimiento acelerado       | <img width="877" height="392" alt="image" src="https://github.com/user-attachments/assets/7029c01f-06fb-4403-bb20-a33ab30fa462" />        | <img width="881" height="392" alt="image" src="https://github.com/user-attachments/assets/9992f657-a7b7-4143-bcbb-5ae628fefdcb" /> |
| Movimiento fuerte con oposición                   | <img width="876" height="392" alt="image" src="https://github.com/user-attachments/assets/9d814273-61af-46de-a0de-1387bbcd8f5d" />       | <img width="881" height="392" alt="image" src="https://github.com/user-attachments/assets/27880ad8-3be1-454c-8b61-72715e8ce60e" />|

## **6. Análisis y discusión** <a name="id9"></a>

## **6.1. EMG - Biceps Braquial** <a name="id9"></a>

En registros de electromiografía superficial (sEMG) del bíceps braquial, la amplitud y el espectro de la señal se relacionan directamente con el grado de activación neuromuscular [13]. Al aplicar el filtro pasabanda, eliminamos la componente DC y artefactos fuera del rango de interes. Mientras que al aplicar el filtro Notch eliminamos el ruido de red eléctrica a 60 Hz.

- **Reposo**: Presenta baja amplitud porque las fibras musculares permanecen inactivas [14]. Sin embargo notamos un pico en 300 Hz en el análisis espectral y de Welch debido a componentes armónicos de la red eléctrica, esto no afecta en nada pues solo se nota debido a la baja amplitud de la señal por estan en reposo.
- **Movimiento leve**: Aparecen descargas motoras aisladas de baja frecuencia y amplitud reducida, reflejando la activación de pocas unidades motoras de contracción lenta [14]. Por lo que la amplitud aumenta opacando la componente de ruido eléctrica a 300 Hz.
- **Movimiento fuerte con oposición**: La amplitud alcanza su máximo debido a la activación simultánea y sostenida de múltiples unidades motoras [14].

## **6.2. EMG - Triceps** <a name="id9"></a>

En el caso del tríceps braquial, la dinámica espectral y de amplitud sigue un patrón similar, aunque con particularidades relacionadas con su rol como extensor primario del codo [15].

- **Reposo**: Presenta baja amplitud porque las fibras musculares permanecen inactivas.
- **Movimiento leve**: Aparecen descargas motoras aisladas de baja frecuencia y amplitud reducida, reflejando la activación de pocas unidades motoras de contracción lenta. 
- **Movimiento fuerte con oposición**: La amplitud alcanza su máximo debido a la activación simultánea y sostenida de múltiples unidades motoras. Sim embargo, a comparación del biceps, acá notamos que el ancho del espectro de frecuencias es mayor. Lo que refleja la activación coordinada de las tres cabezas del tríceps y la necesidad de mantener fuerza sostenida para estabilizar la articulación. Esto coincide con investigaciones recientes que reportan que la amplitud y el ensanchamiento espectral del EMG en el tríceps son indicadores fiables de la carga y del reclutamiento motor durante tareas de extensión [16].
  
## **7. Referencias** 

[1]	Clínica Universidad de Navarra, “Electromiografía y electroneurografía,” Clínica Universidad	de	Navarra.	[En	línea].	Disponible	en: https://www.cun.es/enfermedades-tratamientos/pruebas-diagnosticas/electromiografia-electr oneurografia

[2]	PLUX Wireless Biosignals, “BITalino (r)evolution Home Guide #1: Electromyography (EMG)”, Lisbon, Portugal, 2021. [En línea]. Disponible en: https://bitalino.com/storage/uploads/media/bitalino-homeguide-1-emg.pdf

[3]	D. Landin, M. Thompson y M. R. Jackson, “Actions of the Biceps Brachii at the Shoulder: A Review,” Journal of Clinical Medicine Research, vol. 9, no. 8, pp. 667–670, Aug. 2017, doi: 10.14740/jocmr2901w 

[4]	Z. J. Henderson, S. Bohunicky, J. Rochon, M. Dacanay, and T. D. Scribbans, “Muscle Activation in Specific Regions of the Trapezius During Modified Kendall Manual Muscle Tests,” J Athl Train, vol. 56, no. 10, pp. 1078–1085, Oct. 2021, doi: 10.4085/545-20.


[5] J. L. Fernández-Sáez, M. T. Pérez-García y J. M. Sebastián, “Hand gesture recognition based on a novel EMG decomposition method,” Procedia Engineering, vol. 63, pp. 111–118, 2013, doi: 10.1016/j.proeng.2013.08.073.

[6] Autor(es). “Título del artículo,” Nombre de la revista, vol., no., pp., año. Disponible en: https://dialnet.unirioja.es/servlet/articulo?codigo=9866155








