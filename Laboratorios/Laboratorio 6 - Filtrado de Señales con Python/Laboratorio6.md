# Filtros Digitales Utilizados en Señales EMG, ECG/EKG y EEG
Las señales biomédicas como EMG, ECG/EKG y EEG suelen verse afectadas por diferentes tipos de ruido e interferencias que pueden alterar el análisis clínico y el procesamiento digital. Por ello, los filtros digitales son fundamentales para mejorar la calidad de las señales y permitir una interpretación adecuada. A continuación, se describen algunos de los filtros más utilizados en bioinstrumentación y procesamiento de señales biomédicas.
## 1. Filtro Pasa Bajos (Low-Pass Filter) 
El filtro pasa bajos permite el paso de frecuencias inferiores a una frecuencia de corte determinada y atenúa las frecuencias altas. Es ampliamente utilizado en ECG, EEG y EMG para reducir el ruido de alta frecuencia.
### Tipo de ruido que elimina
- Ruido electrónico
- Interferencia electromagnética
- Artefactos musculares de alta frecuencia
- Ruido térmico
### Frecuencias involucradas
- ECG: normalmente se usa una frecuencia de corte entre 35 Hz y 150 Hz . [1]
- EEG: frecuencias de corte cercanas a 30–70 Hz. [2]
- EMG: puede utilizarse hasta 400–500 Hz dependiendo del análisis. [3]

Por ejemplo, en ECG muchas veces se usa un corte cercano a 40 Hz para eliminar ruido muscular y preservar la morfología de la señal cardíaca.
### Aplicaciones
- Suavizado de señales biomédicas
- Eliminación de ruido de alta frecuencia
- Procesamiento previo al análisis clínico


## 2. Filtro Pasa Altos (High-Pass Filter)
El filtro pasa altos permite el paso de frecuencias altas y atenúa las bajas frecuencias. Es utilizado principalmente para eliminar desplazamientos lentos de la línea base.
### Tipo de ruido que elimina
- Baseline wander
- Movimiento del paciente
- Variaciones lentas por respiración
- Deriva de electrodos
### Frecuencias involucradas
- ECG: generalmente entre 0.05 Hz y 0.5 Hz. [4]
- EEG: alrededor de 0.5 Hz. [5]
- EMG: frecuencias de corte cercanas a 10–20 Hz. [6]

En ECG el movimiento respiratorio puede generar componentes de baja frecuencia menores a 0.5 Hz, por lo que este filtro ayuda a estabilizar la línea base.
### Aplicaciones
- Corrección de línea base
- Mejora de estabilidad de señal
- Eliminación de artefactos lentos

## 3. Filtro Notch (Band-Stop o Rechazo de Banda)
El filtro notch elimina una banda muy estrecha de frecuencias específicas. Su aplicación más común es eliminar la interferencia de la red eléctrica.
### Tipo de ruido que elimina
- Ruido de línea eléctrica
- Interferencia electromagnética de 50 Hz o 60 Hz
### Frecuencias involucradas
- 50 Hz en muchos países de Europa y Latinoamérica
- 60 Hz en Estados Unidos y otros países
  
Esta interferencia aparece debido al acoplamiento eléctrico de cables, equipos biomédicos y el ambiente.
### Aplicaciones
- ECG clínico [7]
- EEG de laboratorio [8]
- Sistemas EMG de adquisición superficial [9]


## 4. Filtro Pasa Banda (Band-Pass Filter)
El filtro pasa banda combina un filtro pasa altos y un pasa bajos para permitir únicamente un rango específico de frecuencias útiles.
### Tipo de ruido que elimina
- Ruido de baja frecuencia
- Ruido de alta frecuencia
- Interferencias fuera del rango fisiológico
### Frecuencias involucradas
- ECG [10]: Aproximadamente 0.5 Hz – 40 Hz
- EEG [11]: Aproximadamente 0.5 Hz – 50 Hz
- EMG [12]: Aproximadamente 20 Hz – 450 Hz
  
En EMG este filtro es muy importante porque la actividad muscular útil se encuentra principalmente entre 20 Hz y 450 Hz.
### Aplicaciones
- Extracción de señales fisiológicas útiles
- Preprocesamiento biomédico
- Sistemas de monitoreo en tiempo real


## 5. Filtro Butterworth
El filtro Butterworth es uno de los filtros digitales más utilizados en bioseñales debido a que presenta una respuesta suave y plana en la banda pasante.
### Tipo de ruido que elimina
Depende de su configuración:
- Ruido muscular
- Interferencia eléctrica
- Baseline wander
- Ruido de alta frecuencia
### Frecuencias involucradas
**Puede diseñarse como:**
- pasa bajos
- pasa altos
- pasa banda
- notch
  
**Por ejemplo:**
- ECG: 0.5–40 Hz [13]
- EEG: 0.5–50 Hz [14]
- EMG: 20–450 Hz [15]
### Aplicaciones
- Procesamiento digital biomédico
- Sistemas embebidos
- MATLAB y Python para bioseñales


## Conclusión
Los filtros digitales son herramientas fundamentales en el procesamiento de señales biomédicas debido a que permiten eliminar diferentes tipos de ruido y mejorar la calidad de las señales EMG, ECG y EEG. Dependiendo del tipo de señal y del ruido presente, se seleccionan filtros específicos como pasa bajos, pasa altos, notch, pasa banda o Butterworth. Estos filtros permiten obtener señales más limpias y confiables para aplicaciones médicas, diagnóstico clínico e investigación biomédica.


## Referencias:
[1] S. Basu and S. Mamud, "Comparative Study on the Effect of Order and Cut off Frequency of Butterworth Low Pass Filter for Removal of Noise in ECG Signal," 2020 IEEE 1st International Conference for Convergence in Engineering (ICCE), Kolkata, India, 2020, pp. 156-160, doi: 10.1109/ICCE50343.2020.9290646. keywords: {IIR filters;Electrocardiography;Low-pass filters;Chebyshev approximation;Finite impulse response filters;Signal to noise ratio;Adaptive filters;ECG;Butterworth Filter;cutoff frequency;order;noise removal

[2] Kaushik, P., & Jain, M. (2018). Design of low power CMOS low pass filter for biomedical application. International Journal of Electrical Engineering & Technology (IJEET), 9(5).

[3] A. E. Gygi and G. S. Moschytz, "Low-pass filter effect in the measurement of surface EMG," Proceedings of Computer Based Medical Systems, Maribor, Slovenia, 1997, pp. 183-188, doi: 10.1109/CBMS.1997.596431. keywords: {Low pass filters;Electromyography;Muscles;Current distribution;Resistors;Electric variables measurement;Organisms;Velocity measurement;Electrodes;Intelligent networks},

[4]Keselbrener, L., Keselbrener, M., & Akselrod, S. (1997). Nonlinear high pass filter for R-wave detection in ECG signal. Medical engineering & physics, 19(5), 481-484.

[5] I. Winkler, S. Debener, K. -R. Müller and M. Tangermann, "On the influence of high-pass filtering on ICA-based artifact reduction in EEG-ERP," 2015 37th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), Milan, Italy, 2015, pp. 4101-4105, doi: 10.1109/EMBC.2015.7319296. keywords: {Signal to noise ratio;Electroencephalography;Accuracy;Electrooculography;Filtering;Standards;Independent component analysis},

[6] Potvin, J. R., & Brown, S. H. (2004). Less is more: high pass filtering, to remove up to 99% of the surface EMG signal power, improves EMG-based biceps brachii muscle force estimates. Journal of Electromyography and Kinesiology, 14(3), 389-399.

[7] Bai, Y. W., Chu, W. Y., Chen, C. Y., Lee, Y. T., Tsai, Y. C., & Tsai, C. H. (2004, May). Adjustable 60Hz noise reduction by a notch filter for ECG signals. In Proceedings of the 21st IEEE Instrumentation and Measurement Technology Conference (IEEE Cat. No. 04CH37510) (Vol. 3, pp. 1706-1711). IEEE.

[8] Olguin, D. O., Bouchereau, F., & Martinez, S. (2005, March). Adaptive notch filter for EEG signals based on the LMS algorithm with variable step-size parameter. In Proceedings of the 39th International Conference on Information Sciences and Systems. Citeseer.

[9] Pilkar, R., Yarossi, M., Ramanujam, A., Rajagopalan, V., Bayram, M. B., Mitchell, M & Forrest, G. (2016). Application of empirical mode decomposition combined with notch filtering for interpretation of surface electromyograms during functional electrical stimulation. IEEE transactions on Neural Systems and Rehabilitation Engineering, 25(8), 1268-1277. 

[10] Altay, Y. A., Kremlev, A. S., Zimenko, K. A., & Margun, A. A. (2019). The effect of filter parameters on the accuracy of ECG signal measurement. Biomedical Engineering, 53(3), 176-180. 

[11] Baranowski, J., & Piątek, P. (2017). Fractional band-pass filters: design, implementation and application to EEG signal processing. Journal of Circuits, Systems and Computers, 26(11), 1750170.

[12] Javvaji, V., & Musala, S. (2019, August). 0. 4V, Low Power G m C Integrator And Bandpass Filter Design For EMG Bio Medical Signal Processing. In 2019 2nd International Conference on Power and Embedded Drive Control (ICPEDC) (pp. 441-444). IEEE.

[13] Salsekar, B., & Wadhwani, A. (2012). Filtering of ECG signal using butterworth filter and its feature extraction. Int. J. Eng. Sci. Technol, 4(2). 

[14] Deo, A., Pandey, S. K., Joshi, A., Sharma, S. K., & Shrimali, H. (2018, June). Design of a Third Order Butterworth G m-C Filter for EEG Signal Detection Application. In 2018 25th International Conference" Mixed Design of Integrated Circuits and System"(MIXDES) (pp. 361-365). IEEE.

[15] Mello, R. G., Oliveira, L. F., & Nadal, J. (2007). Digital Butterworth filter for subtracting noise from low magnitude surface electromyogram. Computer methods and programs in biomedicine, 87(1), 28-35.

