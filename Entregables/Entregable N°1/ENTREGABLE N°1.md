### ENTREGABLE N°1
# ESCASEZ Y ALTO COSTO DE LOS BASTONES CON SENSORES DE CARGA
![dfcb30_b82a837c42ea4b7190653340daab7b6f~mv2](https://github.com/user-attachments/assets/370eccb8-8d01-4c8b-a777-d819f2606e75)

## ÍNDICE
- [OBJETIVO](#objetivo)
- [PALABRAS CLAVE](#palabras-clave)
- [DESARROLLO DE LA TEMÁTICA](#desarrollo-de-la-temática)
- [ESTADO DEL ARTE CIENTÍFICO](#estado-del-arte-científico)
- [DIAGRAMA DE ISHIKAWA](#diagrama-de-ishikawa)
- [DEFINICIÓN DEL PROBLEMA](#definición-del-problema)
- [BIBLIOGRAFÍA](#bibliografía)
 

### OBJETIVO

El principal objetivo de este entregable es profundizar el contexto mundial y nacional de la problemática, alta demanda de pacientes con osteoartritis que no logran recuperar su marcha habitual y escasez de equipos fisioterapéuticos, precisamente, bastones de fuerza, en los centros médicos .Para ello, se han consultado diversos artículos científicos, estado del arte científico, que han permitido establecer un panorama más claro para analizar la implementación de un Open Hardware como propuesta de solución.

### PALABRAS CLAVE

1. **Giroscopio:**  Mide la rotación y orientación de un objeto basándose en el principio de conservación del momento angular [1].
2. **Acelerómetro:** Detecta cambios en la aceleración lineal y en la inclinación del dispositivo respecto a la gravedad, por lo que proporciona datos sobre la velocidad y la orientación en un eje específico [2].
3. **Osteoartritis:** Enfermedad articular degenerativa que provoca hinchazón,rigidez y dolor afectando la capacidad de una persona para desplazarse.[3] 
4. **Bastón inteligente:** Ayuda a mejorar la movilidad y seguridad de personas mayores o con discapacidad al detectar y alertar sobre obstáculos y cambios en el terreno [4].

### DESARROLLO DE LA TEMÁTICA

El hardware abierto u open hardware, son aquellos cuyos diseños de dispositivos electrónicos son liberados de manera que se pueda estudiar, modificar, fabricar y distribuir el dispositivo de manera libre. En síntesis, se trata de tecnología a la que cualquiera puede acceder y compartir sin restricciones, una suerte de software de código abierto. Con el fin de calificar como open hardware, existen ciertos requisitos que deben cumplirse. En primer lugar, el proyecto debe mostrar toda la documentación que permita a otras personas comprender y trabajar con el diseño, sea este físico o virtual. Adicionalmente, debe quedar claro qué aspecto del diseño está siendo liberado. Si el hardware involucra software, este debe ser de código abierto. La licencia con la cual el hardware será compartido debe permitir modificaciones y distribución sin compartir regalías, aunque sí puede requerir atribuciones. No debe haber discriminación de clase y derechos de redistribución para aquellos que compartan el hardware [5].

### CONTEXTO MUNDIAL Y NACIONAL

Según la OMS, hay 365 millones de personas que padecen osteoartritis [6], de ellas, 344 millones de personas presentan niveles de gravedad que podrían beneficiarse de la rehabilitación o con un soporte externo como un bastón [7].
La prescripción de un bastón es un método común de tratamiento para pacientes con osteoartritis de rodilla, pues su uso puede reducir la carga medial de la rodilla durante la marcha. Además, cuando se utiliza en la mano contralateral, se ha demostrado que disminuye el momento de aducción de la rodilla en un promedio del 10%, e incluso en algunos casos puede reducirlo hasta un 20%. Estudios recientes han evidenciado una relación dosis-respuesta entre la carga aplicada en el bastón y la reducción del momento de aducción de la rodilla, mostrando que una carga del bastón equivalente al 20% del peso corporal disminuye de manera efectiva la carga en la articulación de la rodilla [8].

La incorporación de celdas de carga en los bastones se está utilizando para proporcionar a los médicos y pacientes los datos de carga durante el uso del bastón y algunos bastones brindan retroalimentación auditiva o visual en tiempo real. Sin embargo, estos dispositivos tienen costos elevados [8]. En Perú, el precio elevado y la escasez de bastones con sensores de fuerza en los centros de salud afectan significativamente la efectividad de las terapias de rehabilitación para pacientes con osteoartritis.


### ESTADO DEL ARTE CIENTÍFICO

- #### A tactile handle for cane use monitoring

   **Autor principal**: Andrés Trujillo-León\
  **Fecha de publicación**: 2015\
  **Resumen**: Mango táctil diseñado para monitorear el uso de bastones en rehabilitación y asistencia al caminar. Este mango está equipado con sensores de presión distribuidos en sus caras, capaces de medir tanto la fuerza aplicada por el usuario como la orientación del bastón en el plano sagital. Además, incluye una unidad de medición inercial (IMU) para registrar el ángulo de inclinación del bastón y un sensor de fuerza para medir la carga total ejercida. Los datos son procesados por un microcontrolador y analizados para correlacionar el uso del bastón con las fuerzas aplicadas y su orientación [9].

- #### A Smart Cane with Vibrotactile Biofeedback Improves Cane Loading for People with Knee Osteoarthritis

  **Autores principales**: Rebecca L. Routson, Marcus Bailey, Isabelle Pumford, Joseph M. Czerniecki, y Patrick M. Aubin\
  **Fecha de publicación**: 2024\
  **Resumen**: Bastón inteligente diseñado para personas con osteoartritis de rodilla. Este bastón incluye retroalimentación vibrotáctil en tiempo real para mejorar la carga sobre el bastón, promoviendo una distribución adecuada del peso corporal. Se comprobó que el uso de esta tecnología aumenta significativamente la carga del bastón en comparación con el uso de un bastón convencional con instrucciones verbales. Los resultados sugieren que este bastón puede reducir la carga en la rodilla, disminuir el dolor y potencialmente retrasar la progresión de la osteoartritis [10].

- #### Weight-Bearing Estimation for Cane Users by Using Onboard Sensors

  **Autores principales**: Joaquin Ballesteros, Alberto Tudela, Juan Rafael Caro-Romero y Cristina Urdiales\
  **Fecha de publicación**: 2019\
  **Resumen**: Módulo económico y adaptable que puede integrarse en bastones comerciales para monitorear la carga soportada por el usuario. Diseñado para personas mayores o con discapacidad, el sistema permite evaluar la condición del usuario a través de sensores colocados en el bastón que registran la carga dinámica durante actividades diarias. Es de bajo costo, no altera la ergonomía del bastón y ofrece monitoreo continuo por largos periodos sin necesidad de recarga. Los resultados demuestran que la carga registrada correlaciona con la velocidad de marcha, proporcionando información útil para rehabilitación y cuidado preventivo [11].

### DIAGRAMA DE ISHIKAWA

<img width="1000" alt="Captura de pantalla 2024-11-26 a la(s) 23 11 44" src="https://github.com/user-attachments/assets/eb50fe9a-2855-46bb-a8c8-ae338e537860">

### DEFINICIÓN DEL PROBLEMA

La incorporación de celdas de carga en los bastones tiene costos elevados, lo que dificulta su adquisición, y la mayoría de los usuarios no reciben instrucciones adecuadas sobre cómo utilizarlos eficazmente para descargar el peso de la rodilla. Además, desconocen cuánto porcentaje de su peso está soportando el bastón. Esta situación, sumada al alto precio y la escasez de bastones con sensores de fuerza en los centros de salud del Perú, afecta significativamente la efectividad de las terapias de rehabilitación de osteoartritis, ya que estos instrumentos representan una herramienta clave en dicho proceso.

### BIBLIOGRAFÍA
[1] S. Reif-Acherman, "Juguetes como instrumentos de enseñanza en ingeniería: los casos del péndulo de Newton y el giroscopio," *Ingeniería y competitividad*, vol. 16, no. 2, pp. 189-198, 2014.

[2] M. J. Aguilar Cordero, A. M. Sánchez López, G. Barrilao, R. Rodríguez Blanque, J. Noack Segovia, y P. Cano, "Descripción del acelerómetro como método para valorar la actividad física en los diferentes periodos de la vida: revisión sistemática," *Nutrición hospitalaria*, vol. 29, no. 6, pp. 1250-1261, 2014.

[3]H. A. Wieland, M. Michaelis, B. J. Kirschbaum, and K. A. Rudolphi, "Osteoarthritis—an untreatable disease?," *Nat. Rev. Drug Discov.*, vol. 4, no. 4, pp. 331-344, 2005.

[4] O. A. Murillo Cordoba and C. A. Serna Franco, "Prototipo de bastón inteligente para personas con limitación visual," 2017.

[5] Isaac, “Open Hardware: todo lo que necesitas saber - Profesional Review. https://www.profesionalreview.com/2022/07/16/open-hardware/

[6] H. Long, Q. Liu, H. Yin, N. Diao, Y. Zhang, J. Lin, et al., "Prevalence trends of site-specific osteoarthritis from 1990 to 2019: Findings from the global burden of disease study 2019", *Arthritis Rheumatol*, vol. 74, no. 7, pp. 1172-1183, 2022.

[7] A. Cieza, K. Causey, K. Kamenow, S. Wulf Hansen, S. Chatterji, and T. Vos, "Global estimates of the need for rehabilitation based on the Global Burden of Disease study 2019: a systematic analysis for the Global Burden of Disease Study 2019," *Lancet*, vol. 396, no. 10267, pp. 2006–2017, Dec. 2020.

[8] R. L. Routson, M. Bailey, I. Pumford, J. M. Czerniecki, y P. M. Aubin, "A smart cane with vibrotactile biofeedback improves cane loading for people with knee osteoarthritis", *2016 38th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC)*, ago. 2016, pp. 3370-3373. doi: 10.1109/EMBC.2016.7591450.

[9] Andrés Trujillo-León, Wael Bachta, Fernando Vidal-Verdú, "Tactile Sensor-Based Steering as a Substitute of the Attendant Joystick in Powered Wheelchairs", *IEEE Transactions on Neural Systems and Rehabilitation Engineering*, vol.26, no.7, pp.1381-1390, 2018.

[10] Rebecca L. Routson, Marcus Bailey, Isabelle Pumford, Joseph M. Czerniecki, y Patrick M. Aubin. “A Smart Cane with Vibrotactile Biofeedback Improves Cane Loading for People with Knee Osteoarthritis”, *Annu Int Conf IEEE Eng Med Biol Soc*, pp. 3370-3373, Aug. 2016. DOI: 10.1109/EMBC.2016.7591450

[11] Joaquin Ballesteros, Alberto Tudela, Juan Rafael Caro-Romero y Cristina Urdiales. “Weight-Bearing Estimation for Cane Users by Using Onboard Sensors”, Sensors (Basel). vol. 19, no. 3, pp. 509, Jan 26. 2019, DOI: 10.3390/s19030509.

