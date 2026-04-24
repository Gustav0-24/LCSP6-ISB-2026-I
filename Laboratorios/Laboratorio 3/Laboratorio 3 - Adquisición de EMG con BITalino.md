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

A continuación, presentamos el material audiovisual del EMG en entranamiento con el biceps braquial:
<img width="641" height="550" alt="bicep" src="https://github.com/user-attachments/assets/8d5969ec-392d-4610-9bfb-399dce3cd152" />


https://github.com/user-attachments/assets/28f5e9f0-a83b-4cdb-9ff1-9df40d6ecb73


### **4.3. EMG - Trapecio**

Para captar la señal EMG del trapecio adecuadamente se utilizó el protocolo del sistema Bitalino. Se empleó el cable para 3 electrodos ya que el del medio se usó como electrodo de referencia. Este fue colocado sobre la apófisis mastoides la cual es una estructura ósea situada detrás del pabellón auricular, debido a que el electrodo de referencia debe posicionarse en una zona neutra, preferentemente sobre una superficie ósea, como el codo, la frente o la cresta ilíaca [7]. 

Esta zona no presenta masa muscular activa en la realización de los movimientos que se requieren realizar para obtener la señal. 
Por otro lado, los otros 2 electrodos restantes se sitúan al 50% de la línea trazada entre el acromion y la apófisis espinosa de C7, orientados en dirección paralela a dicha línea y a lo largo de las fibras musculares, con una separación de 20 mm entre ambos [8].

A continuación, presentamos el material audiovisual del EMG en entranamiento con el Trapecio:



https://github.com/user-attachments/assets/761f8090-ce2d-4b69-ac3a-1d39ea013fcb



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
| Reposo                              | <img width="841" height="383" alt="EMG_og" src="https://github.com/user-attachments/assets/35c41ad0-377f-4fc8-9865-7a2827d5cbc2" />| <img width="827" height="362" alt="EMG_filt" src="https://github.com/user-attachments/assets/7c6e08eb-7d03-4134-b5b8-94e549efff04" /> |
| Movimiento fuerte con oposición                   | <img width="857" height="388" alt="EMGo_og" src="https://github.com/user-attachments/assets/9bd445cc-f254-41d3-b82e-476c9cddb7ac" /> | <img width="868" height="401" alt="EMGo_filt" src="https://github.com/user-attachments/assets/ed99c287-8493-4b2c-a98c-3ef9a3727b5d" />|

| Entrenamiento                                   | Densidad Espectral de Potencia (Welch) | Espectro de Frecuencias (FFT)                         |
|----------------------------------------------|----------|---------------------------------|
| Reposo                              | <img width="810" height="348" alt="Dens" src="https://github.com/user-attachments/assets/347cd598-1d3c-47b6-854f-45b4fcfeb759" />| <img width="773" height="322" alt="fft" src="https://github.com/user-attachments/assets/d39f2a2e-5bad-4c5c-8465-b9c6401bd2ad" />|
| Movimiento fuerte con oposición                   | <img width="797" height="341" alt="Dens_o" src="https://github.com/user-attachments/assets/4731b0fb-df65-4209-99c8-18df07b4d206" />|<img width="797" height="365" alt="fft_o" src="https://github.com/user-attachments/assets/70900862-d774-4c09-933a-92ff8005b62d" />|

### **5.3. EMG - Trapecio**
| Entrenamiento                                   | Señal original | Señal filtrada                         |
|----------------------------------------------|----------|---------------------------------|
| Reposo                              |<img width="716" height="432" alt="Captura de pantalla 2026-04-19 235204" src="https://github.com/user-attachments/assets/5b93cef2-d5d6-41db-b20f-fb6e5b851713" /> | <img width="737" height="432" alt="Captura de pantalla 2026-04-19 235220" src="https://github.com/user-attachments/assets/7965bdbb-e82d-4f5b-b552-c19f3001eb29" />|
| Movimiento fuerte con oposición                   | <img width="677" height="391" alt="Captura de pantalla 2026-04-19 235453" src="https://github.com/user-attachments/assets/668cf878-4bec-4a8b-afcd-2e7f7aed42f3" />| <img width="662" height="398" alt="Captura de pantalla 2026-04-19 235504" src="https://github.com/user-attachments/assets/2c8afe57-4deb-49a1-bd19-41c8e4633741" />|

| Entrenamiento                                   | Densidad Espectral de Potencia (Welch) | Espectro de Frecuencias (FFT)                         |
|----------------------------------------------|----------|---------------------------------|
| Reposo                              |<img width="732" height="423" alt="Captura de pantalla 2026-04-19 235331" src="https://github.com/user-attachments/assets/c5d7f33e-2005-4407-af85-9b0c8b202872" />| <img width="762" height="447" alt="Captura de pantalla 2026-04-19 235342" src="https://github.com/user-attachments/assets/81e9a6b1-9526-4c99-99ee-c5ac53b024c3" />|
| Movimiento fuerte con oposición                   | <img width="682" height="393" alt="Captura de pantalla 2026-04-19 235516" src="https://github.com/user-attachments/assets/6cd60146-ce3f-44e7-8419-8039a61cafde" />| <img width="683" height="403" alt="Captura de pantalla 2026-04-19 235528" src="https://github.com/user-attachments/assets/546a8bc2-84ec-41ae-a8e6-a9551e270d02" />|

## **6. Análisis y discusión** <a name="id9"></a>

## **6.1. EMG - Biceps Braquial** <a name="id9"></a>

En los registros de electromiografía superficial (sEMG) del bíceps braquial en los brazos, la amplitud y el contenido espectral de la señal se encuentran en relación directa con el nivel de activación neuromuscular [9]. Para su procesado, fue utilizado un filtro pasa- banda (20–450Hz), que permitió eliminar la componente DC y artefactos fuera del rango de interés, y un filtro notch a 60Hz que sirve para reducir el ruido de fondo de la red eléctrica. Para el análisis : se realizaron los 2 segmentos de señal : 1 minuto en reposo y ,1 minuto en contracción de oposición. 
En la condición de reposo, la señal es de baja amplitud y de acuerdo con el escaso reclutamiento de fibras musculares [10].La señal, en el análisis espectral (FFT y Welch), la energía es reducida y también podemos observar algunos picos de ruido residual , los cuales se hacen más notorios debido a la baja amplitud de la señal.
En la parte en la que nos encontramos con movimiento fuerte y oposición, la señal sí presenta una clara amplitud, ya que se están enviando muchas unidades motoras [10]. También podemos observarlo en el dominio de la frecuencia, donde se incrementa el contenido energético y se puede ver también el característico rango de la señal EMG activa, que se encuentra con frecuencia entre 20 y 150 Hz [11]. 


## **6.2. EMG - Trapecio** <a name="id9"></a>
En los registros de electromiografía superficial del músculo trapecio, la amplitud y el contenido espectral de la señal se relacionan directamente con el nivel de activación neuromuscular. Para poder procesar las señales, éstas fueron filtradas mediante la aplicación de un filtro pasa-banda de 20–450 Hz y un filtro notch a 60 Hz eliminando así la componente DC y la red eléctrica, y de esta forma poder conservar el rango fisiológicamente relevante de la EMG.
En la condición de reposo, la señal presenta baja amplitud, lo cual es consistente con un reclutamiento mínimo de unidades motoras. En el análisis espectral (FFT y Welch), el espectro de densidad de potencia es bajo encontrándose algunos picos siempre asociados al ruido residual que se hacen acentuar por la baja energía total de la señal. Este comportamiento es característico de bajos niveles de activación muscular, por debajo del 20% de la contracción voluntaria máxima (MVIC) [12].
Por el contrario, la condición de movimiento (oposición) muestra una clara amplitud de la señal debido a un mayor reclutamiento y sincronización de unidades motoras, aspecto que concuerda con estudios donde ejercicios como la retracción escapular son capaces de conseguir niveles de activación del trapecio moderados-altos [12].En el dominio de la frecuencia, se observa un aumento del contenido energético, concentrado principalmente en el rango característico de la EMG activa (20–150 Hz), evidenciando la participación funcional del músculo en la estabilización escapular.

## **7. Cuestionario**
1. Which are the significant frequencies for EMG acquisitions? Are they the same in all body areas such as facial area?

Las señales presentaron información relevante en el rango de 20 Hz a 450 Hz (intervalo
fisiológicamente relevante de la actividad muscular), pues en este se concentra la mayor
parte de la energía de la señal. Esto se debe a que, por ejemplo, las frecuencias más bajas
a 20 Hz están relacionadas con ruido o artefactos de movimiento o desplazamiento de los
electrodos y las mayores a 450 Hz pueden asociarse a ruido del sistema o interferencias.
Por lo cual se aplica un filtro que limita el análisis a dicho intervalo.
El comportamiento de las frecuencias no es igual en todas las regiones del cuerpo. Los
músculos grandes, como el bíceps y el trapecio, presentan mayor amplitud y un contenido
energético más grande debido al mayor número de fibras musculares activadas. A pesar
que en el documento no se haya realizado la experiencia con los músculos faciales, se
espera que al ser más pequeños y tener un patrón de activación diferente, generen señales
con menor amplitud y con una distribución frecuencial algo distinta. Es decir, aunque el
rango general se mantiene la distribución de energía dentro de este varía según el tipo de
músculo.

2. Which kind of filter is essential when working with EMG signals? Why do we need to apply such a filter?

Para este tipo de procesamiento se requiere la aplicación de filtros para eliminar
componentes no deseados y preservar solo la información fisiológicamente relevante. En
este laboratorio se utilizaron tanto un filtro pasa-banda entre 20 Hz y 450 Hz como un filtro
notch a 60 Hz.
El filtro pasa-banda sirve para eliminar la componente DC, los artefactos de baja frecuencia
asociados al movimiento y el ruido de alta frecuencia. Esto busca que la señal analizada
corresponda al rango de la actividad muscular real. Por otro lado, el filtro notch tiene la fue
aplicado para eliminar la interferencia de la red eléctrica que actúa como un ruido en 60 Hz.
Esta interferencia puede distorsionar el análisis si no es removida. Gracias a estos filtros, la
señal filtrada muestra una forma más definida y menos contaminada en comparación con la
señal original.

3. How does the amplitude differ in each muscular contraction? Is there a difference for body locations?

La amplitud de la señal EMG varía directamente con el nivel de contracción muscular, lo
cual se puede observar en los resultados obtenidos.
Cuando el bíceps braquial se encuentra en reposo, la señal presenta una amplitud baja y
relativamente estable lo cual es equivalente a indicar que existe un bajo nivel de activación
muscular. Sin embargo, cuando se realiza el movimiento fuerte con oposición, la señal
incrementa significativamente su amplitud donde muestra picos pronunciados y mayor
variabilidad.
Para el trapecio, en reposo este también muestra presenta baja amplitud pero durante la
contracción se puede observar ráfagas de actividad de mayor magnitud. La señal tiende a
ser más sostenida en el tiempo lo cual hace referencia a la función postural del músculo.
Los resultados muestran que aunque ambos músculos presentan la misma tendencia en
rasgos generales, existen diferencias en el patrón de activación. El bíceps presenta
activaciones más intermitentes asociadas al movimiento, mientras que el trapecio muestra
activaciones más sostenidas. Con esto, se puede decir que la amplitud no solo va a
depender de la intensidad de contracción, sino también está relacionada con la función y
características del músculo a evaluar.

4. Show a screenshot of a relevant portion of Electromyography (EMG) data within the
experiment proposed on Section D of a facial muscle of interest. Does this signal
correspond to what you expected? Why? Which emotion and action did you perform
to trigger the muscle? Which muscle did you trigger?

Como se mencionó anteriormente, el experimento no se realizó para los músculos faciales,
sin embargo, se analizaron los otros músculos ya mencionados. Dentro a lo que respecta a
ellos, se puede decir que una porción representativa de la EMG puede observarse en las
gráficas correspondientes al movimiento fuerte con oposición del bíceps braquial y del
trapecio. En ellas se aprecia un incremento significativo en la amplitud que se acompaña de
un comportamiento irregular y no periódico.
Esto corresponde a lo esperado, ya que durante la contracción muscular se incrementa el
reclutamiento de unidades motoras y se debe generar una señal de mayor amplitud con
mayor contenido energético. La naturaleza no periódica de la señal se debe a que las fibras
de los músculos no se sincronizan para activarse.
El comportamiento observado en los músculos analizados es equivalente al esperado en
músculos como los faciales. Por ejemplo, al realizar una acción como sonreír que activa el
músculo cigomático se esperaría observar un incremento en la amplitud de la señal y un
patrón no periódico similar.

5. To the best of your knowledge, does the EMG amplitude equal to the amount of force
that you have generated with your muscle?

La amplitud de la señal EMG no es equivalente a la fuerza generada por el músculo pero si
existe una relación entre ambas variables. El aumento en la amplitud suele indicar un mayor
nivel de activación muscular lo cual suele conllevar un incremento en la fuerza.
Sin embargo, la relación no es lineal ni directa porque la señal depende de múltiples
variables como la frecuencia de activación, la posición de los electrodos, la impedancia de
la piel, el tipo de músculo, etc. En este documento se observó que la amplitud aumenta
considerablemente durante la contracción con oposición en comparación con el reposo. Es
así como la señal EMG debe interpretarse como una medida de la actividad eléctrica
muscular y no como una medición directa de la fuerza generada.

## **8. Referencias** 

[1]	Clínica Universidad de Navarra, “Electromiografía y electroneurografía,” Clínica Universidad	de	Navarra.	[En	línea].	Disponible	en: https://www.cun.es/enfermedades-tratamientos/pruebas-diagnosticas/electromiografia-electr oneurografia

[2]	PLUX Wireless Biosignals, “BITalino (r)evolution Home Guide #1: Electromyography (EMG)”, Lisbon, Portugal, 2021. [En línea]. Disponible en: https://bitalino.com/storage/uploads/media/bitalino-homeguide-1-emg.pdf

[3]	D. Landin, M. Thompson y M. R. Jackson, “Actions of the Biceps Brachii at the Shoulder: A Review,” Journal of Clinical Medicine Research, vol. 9, no. 8, pp. 667–670, Aug. 2017, doi: 10.14740/jocmr2901w 

[4]	Z. J. Henderson, S. Bohunicky, J. Rochon, M. Dacanay, and T. D. Scribbans, “Muscle Activation in Specific Regions of the Trapezius During Modified Kendall Manual Muscle Tests,” J Athl Train, vol. 56, no. 10, pp. 1078–1085, Oct. 2021, doi: 10.4085/545-20.


[5] J. L. Fernández-Sáez, M. T. Pérez-García y J. M. Sebastián, “Hand gesture recognition based on a novel EMG decomposition method,” Procedia Engineering, vol. 63, pp. 111–118, 2013, doi: 10.1016/j.proeng.2013.08.073.

[6] Autor(es). “Título del artículo,” Nombre de la revista, vol., no., pp., año. Disponible en: https://dialnet.unirioja.es/servlet/articulo?codigo=9866155

[7] M. Proença and K. Mrotzeck, "BITalino (r)evolution Home Guide #1: Electromyography (EMG)," PLUX – Wireless Biosignals, S.A., Lisbon, Portugal, Tech. Rep. OD.LB.02.07, Feb. 2021.

[8] H. J. Hermens, B. Freriks, C. Disselhorst-Klug, and G. Rau, "Development of recommendations for SEMG sensors and sensor placement procedures," Journal of Electromyography and Kinesiology, vol. 10, no. 5, pp. 361–374, Oct. 2000.

[9] D. Farina et al., Journal of Applied Physiology, 2004.

[10] S. De Luca, Journal of Applied Biomechanics, 1997.

[11] R. Merletti, P. Parker, Electromyography: Physiology, Engineering, and Non-Invasive Applications, Wiley-IEEE Press, 2004.

[12] R. A. McCabe, K. F. Orishimo, M. P. McHugh y S. J. Nicholas, “Surface electromyographic analysis of the lower trapezius muscle during exercises performed below ninety degrees of shoulder elevation in healthy subjects,” North American Journal of Sports Physical Therapy, vol. 2, no. 1, pp. 34–43, 2007.





