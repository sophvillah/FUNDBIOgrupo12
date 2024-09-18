### ENTREGABLE N°1
# ALTO RIESGO DE SUFRIR CAÍDAS DEBIDO A LA PÉRDIDA DE EQUILIBRIO Y MOVILIDAD POR LA EDAD

### OBJETIVO

El principal objetivo de este entregable es profundizar el contexto mundial y nacional de la problemática escogida, alto riesgo de sufrir caídas debido a la pérdida de equilibrio y movilidad por la edad. Para ello, se han consultado diversos artículos científicos, estado del arte científico, que han permitido establecer un panorama más claro para analizar la implementación de un Open Hardware como propuesta de solución.

### PALABRAS CLAVE

1. **Giroscopio:** Mide la rotación y orientación de un objeto basándose en el principio de conservación del momento angular [1].
2. **Acelerómetro:** Detecta cambios en la aceleración lineal y en la inclinación del dispositivo respecto a la gravedad, por lo que proporciona datos sobre la velocidad y la orientación en un eje específico [2].
3. **LIDAR:** Sensor que utiliza pulsos de luz láser para medir la distancia a objetos y crear mapas 3D detallados de su entorno, proporcionando información precisa sobre la forma y la posición de los objetos [3].
4. **Bastón inteligente:** Ayuda a mejorar la movilidad y seguridad de personas mayores o con discapacidad al detectar y alertar sobre obstáculos y cambios en el terreno [4].

### DESARROLLO DE LA TEMÁTICA

El hardware abierto u open hardware, son aquellos cuyos diseños de dispositivos electrónicos son liberados de manera que se pueda estudiar, modificar, fabricar y distribuir el dispositivo de manera libre. En síntesis, se trata de tecnología a la que cualquiera puede acceder y compartir sin restricciones, una suerte de software de código abierto. Con el fin de calificar como open hardware, existen ciertos requisitos que deben cumplirse. En primer lugar, el proyecto debe mostrar toda la documentación que permita a otras personas comprender y trabajar con el diseño, sea este físico o virtual. Adicionalmente, debe quedar claro qué aspecto del diseño está siendo liberado. Si el hardware involucra software, este debe ser de código abierto. La licencia con la cual el hardware será compartido debe permitir modificaciones y distribución sin compartir regalías, aunque sí puede requerir atribuciones. No debe haber discriminación de clase y derechos de redistribución para aquellos que compartan el hardware [5].

### CONTEXTO MUNDIAL Y NACIONAL

Hasta 2021, se registraron 761 millones de personas mayores de 65 años a nivel mundial, según datos de la ONU. En Perú, el INEI reportó que para 2023 había casi 4.6 millones de personas mayores de 60. Estos datos hacen dar cuenta que existe un gran porcentaje de adultos mayor tanto en el mundo como en el Perú. 

A medida que las personas van llegando a la tercera edad empiezan a padecer diferentes dolencias que afectan radicalmente su estilo de vida. Entre las cuales se encuentran principalmente la pérdida de audición, visión y movilidad. Además, las caídas pueden ser críticas en su cuerpo, siendo una de las principales causas de mortalidad y morbilidad, adicionalmente casi la tercera parte de adultos mayores al menos sufre de una caída al año [6]. Estás caídas pueden generar lesiones muy graves que agravan aún más su estilo de vida.

Teniendo en cuenta lo anterior, es por ello que las personas de tercera edad se apoyan de un bastón que ayuda tanto a aliviar el peso o a ser un apoyo extra al momento de andar. Sin embargo, de acuerdo con un estudio se observó que las personas no saben cómo usar correctamente el bastón [7]. Además en Perú, lamentablemente existen muchos baches o partes elevadas con las que uno fácilmente se puede tropezar por lo que solamente un bastón simple no necesariamente puede ser de gran ayuda. 

Existe otro tipo de bastón llamado bastón blanco que es una guía para personas con discapacidad visual que ayuda a detectar objetos al momento que la persona esté andando. En la actualidad existen varios prototipos que le añaden sensores ultrasónicos [6], [8], [9] para que sin la necesidad de que el bastón haga contacto puede detectar objetos relativamente cercanos. 

Este proyecto lo que busca es un bastón que combine la característica principal de un bastón, apoyo, y que adicionalmente tenga sensores ultrasónicos para la detección de baches que un adulto mayor no pueda detectarlo a simple vista o simplemente no lo vea. 

### ESTADO DEL ARTE CIENTÍFICO

- #### Un bastón inteligente con biorretroalimentación vibrotáctil mejora la carga del bastón para personas con osteoartritis de rodilla 

  **Autor principal**: Evan Schuster\
  **Fecha de publicación**: 2019\
  **Resumen**: Es un diseño de bastón con biorretroalimentación háptica con la finalidad de reducir el momento de aducción de la rodilla (KAM) para personas que padecen de osteoartritis [10].


- #### S-Cane: Bastón inteligente con sensor ultrasónico para personas con discapacidad visual

  **Autor principal**: Amelia Ulfá\
  **Fecha de publicación**: 2024\
  **Resumen**: Desarrollo de un bastón inteligente de bajo costo con el objetivo de detectar obstáculos como baches o charcos de agua mediante sensores ultrasónicos y alertar mediante un vibrador [11].


- #### Bastón EVAL: un bastón inteligente basado en IoT para la evaluación de la marcha y el entorno

  **Autor principal**: Ting Wang\
  **Fecha de publicación**: 2021\
  **Resumen**: Es una propuesta de bastón inteligente basado en IoT multifuncional que puede analizar la caminata de la persona, detectar objetos y esos datos enviar a una pantalla lcd para el posterior análisis [12].

### DIAGRAMA DE ISHIKAWA

![Gráfico Diagrama de Ishikawa Profesional Azul-3](https://github.com/user-attachments/assets/27c1edc6-4eba-417f-85a7-f0d736c3cdac)

Información extraída de [13].

### DEFINICIÓN DEL PROBLEMA

A medida que las personas envejecen, su equilibrio, movilidad y capacidad de reacción ante situaciones de riesgo tienden a disminuir. Esto crea un mayor riesgo de caídas, lo cual respecta una las principales causas de lesiones graves e ingresos hospitalarios entre las personas mayores. Estas caídas pueden provocar fracturas, pérdida de confianza al caminar y, en muchos casos, disminución de la independencia, con un impacto negativo en la calidad de vida. Además, consecuencias emocionales como el miedo a volver a caer pueden provocar aislamiento social. Por ello, es fundamental desarrollar soluciones innovadoras que avisen tempranamente de posibles caídas, aportando seguridad y apoyo.

El alto riesgo de caídas en las personas mayores está influenciado por varios factores que interactúan entre sí. Aunque los problemas articulares, como la artrosis y la osteoporosis, afectan a la movilidad; es la debilidad muscular, consecuencia del sedentarismo y una nutrición inadecuada, la que agrava aún más la situación. Asimismo, las deficiencias visuales causadas por cataratas o glaucoma reducen la capacidad de percibir el entorno; así como, los trastornos neurológicos como el Parkinson y las consecuencias del accidente cerebrovascular que también limitan las respuestas físicas y motoras. A esto se suma la pérdida del equilibrio, donde los reflejos ralentizados por la edad contrastan con la necesidad de independencia, generando el miedo a caer que, en lugar de proteger, refuerza la inseguridad al caminar [13].

### BIBLIOGRAFÍA
[1] S. Reif-Acherman, "Juguetes como instrumentos de enseñanza en ingeniería: los casos del péndulo de Newton y el giroscopio," Ingeniería y competitividad, vol. 16, no. 2, pp. 189-198, 2014.

[2] M. J. Aguilar Cordero, A. M. Sánchez López, G. Barrilao, R. Rodríguez Blanque, J. Noack Segovia, y P. Cano, "Descripción del acelerómetro como método para valorar la actividad física en los diferentes periodos de la vida: revisión sistemática," Nutrición hospitalaria, vol. 29, no. 6, pp. 1250-1261, 2014.

[3] R. T. H. Collis, "Lidar," Applied Optics, vol. 9, no. 8, pp. 1782-1788, 1970.

[4] O. A. Murillo Cordoba and C. A. Serna Franco, "Prototipo de bastón inteligente para personas con limitación visual," 2017.

[5] Isaac, “Open Hardware: todo lo que necesitas saber - Profesional Review. https://www.profesionalreview.com/2022/07/16/open-hardware/

[6] O. Appiah y W. Elmannai, «A Smart Cane with Fall Detection System for People with Visual Impairments», nov. 2023, pp. 1010-1015. doi: 10.1109/DASC/PiCom/CBDCom/Cy59711.2023.10361350.

 [7] E. Schuster et al., «A Novel Walking Cane with Haptic Biofeedback Reduces Knee Adduction Moment in the Osteoarthritic Knee», J Biomech, vol. 114, p. 110150, ene. 2021, doi: 10.1016/j.jbiomech.2020.110150.

[8] I. Vineeth, Y. H. V. S. Sharan, Y. Karthik, y B. K. Priya, «Smart Cane for Visually Impaired Person», en 2021 International Conference on Intelligent Technologies (CONIT), jun. 2021, pp. 1-6. doi: 10.1109/CONIT51480.2021.9498563.

[9]  Y. Niitsu, T. Taniguchi, y K. Kawashima, «Detection and notification of dangerous obstacles and places for visually impaired persons using a smart cane», en 2014 Seventh International Conference on Mobile Computing and Ubiquitous Networking (ICMU), ene. 2014, pp. 68-69. doi: 10.1109/ICMU.2014.6799060.

[10] 

[11] A. Ulfa, A. A. Rosspertiwi, A. Sahroni, y S. Murnani, «S-Cane: Ultrasonic Sensor-Based Smart Cane for the Visually Impaired», en 2023 IEEE International Biomedical Instrumentation and Technology Conference (IBITeC), nov. 2023, pp. 7-11. doi: 10.1109/IBITeC59006.2023.10390939.

[12] T. Wang, R. Grobler, y E. Monacelli, «EVAL Cane: An IoT based Smart Cane for the Evaluation of Walking Gait and Environment», en 2020 IEEE International Symposium on Broadband Multimedia Systems and Broadcasting (BMSB), oct. 2020, pp. 1-4. doi: 10.1109/BMSB49480.2020.9379468.

[13] O. Appiah and W. Elmannai, "A Smart Cane with Fall Detection System for People with Visual Impairments," 2023 IEEE Intl Conf on Dependable, Autonomic and Secure Computing, Intl Conf on Pervasive Intelligence and Computing, Intl Conf on Cloud and Big Data Computing, Intl Conf on Cyber Science and Technology Congress (DASC/PiCom/CBDCom/CyberSciTech), Abu Dhabi, United Arab Emirates, 2023, pp. 1010-1015, doi: 10.1109/DASC/PiCom/CBDCom/Cy59711.2023.10361350.

