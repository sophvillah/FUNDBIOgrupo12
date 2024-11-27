### ENTREGABLE N°3
# ESCASEZ Y ALTO COSTO DE LOS BASTONES CON SENSORES DE CARGA

### OBJETIVO
El principal objetivo de este entregable es plantear formalmente la propuesta de solución que se presentará ante la problemática establecida. Se expondrá un previo contexto de todo lo antes propuesto en los otros dos entregables pasados, para recordar conceptos e ideas que permitan una clara explicación del proyecto.

### PROBLEMÁTICA
   #### CONTEXTO 
   Según la OMS, hay 365 millones de personas que padecen osteoartritis, de ellas, 344 millones de personas presentan niveles de gravedad que podrían beneficiarse de la rehabilitación o con un soporte externo como un bastón [1].
   
La prescripción de un bastón es un método común de tratamiento para pacientes con osteoartritis de rodilla, pues su uso puede reducir la carga medial de la rodilla durante la marcha. Además, cuando se utiliza en la mano contralateral, se ha demostrado que disminuye el momento de aducción de la rodilla en un promedio del 10%, e incluso en algunos casos puede reducirlo hasta un 20%. Estudios recientes han evidenciado una relación dosis-respuesta entre la carga aplicada en el bastón y la reducción del momento de aducción de la rodilla, mostrando que una carga del bastón equivalente al 20% del peso corporal disminuye de manera efectiva la carga en la articulación de la rodilla [2].

La incorporación de celdas de carga en los bastones se está utilizando para proporcionar a los médicos y pacientes los datos de carga durante el uso del bastón y algunos bastones brindan retroalimentación auditiva o visual en tiempo real.Sin embargo, estos dispositivos tienen costos elevados [3]. En Perú, el precio elevado y la escasez de bastones con sensores de fuerza en los centros de salud afectan significativamente la efectividad de las terapias de rehabilitación para pacientes con osteoartritis.


   #### DEFINICIÓN DEL PROBLEMA
   El problema radica en la limitada disponibilidad y el alto costo de los bastones con sensores de carga en el contexto de la rehabilitación de pacientes con osteoartritis, especialmente en países como Perú. A nivel mundial, se estima que 344 millones de personas con osteoartritis de rodilla podrían beneficiarse de dispositivos de asistencia como bastones, los cuales ayudan a reducir la carga en la articulación de la rodilla y mejoran la marcha. 
   
   Sin embargo, la escasez de estos bastones con sensores de fuerza en los centros de salud, sumada a su alto costo, limita su acceso y eficacia en el tratamiento y la rehabilitación de estos pacientes algunos bastones equipados con celdas de carga pueden proporcionar datos en tiempo real sobre la carga aplicada, lo que facilita la personalización del tratamiento y la rehabilitación, estos dispositivos suelen tener un costo elevado. Esto crea una barrera significativa para su adopción generalizada, especialmente en países con recursos limitados, como Perú. La falta de acceso a estos bastones con sensores de carga afecta directamente la efectividad de las terapias, impidiendo a los pacientes obtener el máximo beneficio del tratamiento.

   #### IMPACTO
   Cuando las personas comienzan a utilizar un bastón en su vida diaria, pueden presentar dificultades para adaptarse adecuadamente; ya que no están familiarizados con su correcto uso, siendo uno de los principales problemas  la mala fuerza ejercida sobre el bastón, lo que a largo plazo puede generar problemas o accidentes.
   
El uso de un bastón inteligente no solo ayudaría a prevenir estos incidentes, sino que también mejoraría la autonomía y bienestar emocional de los ancianos, permitiéndoles llevar una vida más activa y segura.

### PROPUESTA DE SOLUCIÓN
   #### DESCRIPCIÓN DE LA SOLUCIÓN
   Sticky Cane se basa en la implementación de sensores como accesorios adaptables para los bastones existentes, midiendo el peso ejercido y generando una retroalimentación en tiempo real. Con el fin de solucionar el mal uso del bastón al aplicar una fuerza no adecuada.

   #### CARACTERÍSTICAS DEL PROTOTIPO
   #### Características:
- Herramienta de asistencia avanzada para personas con movilidad limitada.
- Podrá detectar la fuerza aplicada sobre el bastón a través del sensor de fuerza con capacidad de 100kg 
- Detectará cambios en la velocidad, aceleración, inclinación y balanceo; gracias a la incorporación de acelerómetros y giroscopios, el cual permitiría seguir los movimientos y el grado de inclinación .
- Se identificará si el usuario está usando de manera inestable el bastón, si es así, podría alertar al usuario si existe riesgo de caída o pérdida de equilibrio.
- Enviará señales de advertencia al usuario a través de un sensor de vibración, el cual notificará por medio de vibraciones de manera discreta, inmediata, independiente de los entornos ruidosos y sin ser disruptivo.

#### BENEFICIOS
- Medición de carga ejercida sobre el bastón con 100 Kg, como máximo.
- Sistema de vibración en tiempo real.
- **Económico:** Comparado con diversos productos centrados en la misma problemática, Sticky Cane resalta en el apartado económico al presentarse como un gadget adaptativo.

#### VIABILIDAD TÉCNICA
   La viabilidad técnica de Sticky Cane es alta dado el avance actual en tecnología de sensores, microcontroladores y dispositivos de retroalimentación. 
   
- **Sensores de Fuerza-FSR (hasta 100 kg):** Estos sensores son de bajo costo y se integran fácilmente en sistemas de medición
- **Acelerómetros y Giroscopios:** La integración de sensores inerciales como acelerómetros y giroscopios es factible, pues ya se emplean en numerosos dispositivos de seguimiento de movimiento y estabilización.
- **Sensor de Vibración para Retroalimentación:** El uso de sensores de vibración son dispositivos pequeños, económicos y eficaces para alertar al usuario sin interferir con su entorno. Se puede encontrar en los mandos de consolas. 
- **Microcontrolador:** Un microcontrolador como el Arduino o Arduino Nano  podría ser usado para procesar los datos de los sensores en tiempo real y generar la retroalimentación correspondiente. Estos controladores son accesibles y suficientes, además  tienen soporte para integrarse con diversos sensores.
- **Integración con Bastones Existentes:** El diseño de Sticky Cane como un accesorio adaptable a bastones existentes educe los costos de fabricación, pues no es necesario desarrollar un nuevo bastón desde cero, sino que se aprovecha una infraestructura ya disponible y ampliamente aceptada.


### COHERENCIA
   #### COHERENCIA DEL PROYECTO
  La prescripción de un bastón es un tratamiento común para pacientes con osteoartritis o que simplemente necesiten de un apoyo que pueda amortiguar su peso, ya que puede reducir la carga en la rodilla generando alivio durante la marcha 

Estudios muestran una relación directa entre la carga del bastón y la reducción del momento de aducción de la rodilla (KAM). Al aplicar una carga del 20% o mayor del peso corporal en el bastón, se logra una disminución significativa, lo que reduce el dolor y mejora la funcionalidad de la rodilla. 

Sin embargo, la mayoría de los usuarios no reciben instrucciones adecuadas sobre cómo utilizar el bastón eficazmente para descargar el peso de la rodilla. Además, no saben cuánto porcentaje de su peso está soportando el bastón. Y diseñar todo un bastón implementado puede resultar difícil de adquirir. Por ello, proponemos Sticky Cane, un dispositivo adaptable que mide la carga del bastón, ofreciendo una alternativa económica para la complementación de la rehabilitación tanto en clínicas como en el hogar mediante la telemedicina.

   #### OBJETIVOS DEL PROYECTO
   #### **Objetivo General:** 
   - Mitigar  la mala cuantificación de fuerza que deben ejercer los usuarios para un uso correcto del bastón puede generar una tensión excesiva en los músculos y a largo plazo ocasionar problemas posturales.

#### **Objetivos Específicos:**
- Implementar sensores de giroscopio y acelerómetro para detectar la aceleración inicial y la velocidad.
- Calcular la efectividad del bastón en ambientes reales, con superficies planas y condiciones ideales
- Utilizar un sensor de fuerza resistivo(FSR) para medir la carga ejercida sobre el bastón.
- Diseñar un sistema de alertas fácil de entender.

#### JUSTIFICACIÓN DEL PROTOTIPO
  La justificación para desarrollar un bastón con sensor de fuerza radica en la necesidad de mejorar la rehabilitación de pacientes con osteoartritis, quienes no reciben la orientación adecuada sobre el uso de bastones. Esto es crucial, ya que un bastón bien utilizado reduce la carga en la rodilla hasta en un 20%, lo que puede disminuir el dolor y ralentizar la progresión de la enfermedad. La propuesta de un bastón con sensores inerciales y de fuerza, basado en Open Hardware, ofrecería una solución asequible, permitiendo retroalimentación en tiempo real y registro de datos, optimizando así el seguimiento clínico y la recuperación.

#### ALINEACIÓN CON EL PROBLEMA
  Las personas de la tercera edad a menudo enfrentan dificultades significativas para moverse debido al deterioro progresivo de capacidades físicas esenciales, como la visión, el equilibrio y la fuerza. Estos problemas no solo afectan la movilidad, sino que también incrementan el riesgo de caídas y otros accidentes, lo que puede generar una disminución en la calidad de vida. Aunque existen soluciones tecnológicas disponibles en el mercado, la mayoría de estos dispositivos son costosos y difíciles de obtener, lo que hace que no sean accesibles para una gran parte de la población mayor, especialmente en entornos de bajos recursos. Además, muchas de las opciones existentes no están diseñadas para adaptarse completamente a las necesidades específicas de los usuarios, lo que limita su efectividad.

Con el objetivo de mejorar la calidad de vida de las personas mayores, se propone el desarrollo de un bastón inteligente accesible, que integre un sensor de fuerza capaz de medir la carga aplicada por el usuario. Este dispositivo alerta al usuario mediante vibraciones discretas cada vez que se detectan irregularidades en su postura o en la carga que está soportando, lo que le permite ajustar su forma de caminar y reducir el riesgo de lesiones. Además, el bastón estará diseñado para ser ligero, ergonómico y resistente, lo que facilitará su uso prolongado sin causar molestias.

Este sistema proactivo no solo mejorará la seguridad del usuario, sino que también aumentará su independencia y confianza al moverse por entornos urbanos. Al ser una solución económica y accesible, busca ofrecer una alternativa viable para muchas personas mayores que actualmente no tienen acceso a las tecnologías de asistencia más caras. Con este bastón inteligente, se espera que los adultos mayores puedan disfrutar de una mayor movilidad y calidad de vida sin preocuparse por los altos costos de las opciones existentes en el mercado.


### RESUMEN
#### Problema y Solución Propuesta: 
Las personas de la tercera edad enfrentan dificultades de movilidad debido a su progresiva pérdida de capacidades físicas como la visión y el equilibrio. La solución propuesta es un bastón inteligente equipado con sensor de fuerza que alerta al usuario mediante vibraciones discretas. Este sistema proactivo está diseñado para mejorar la seguridad y la movilidad de las personas mayores en entornos urbanos.

#### Resultados Deseados:
Los resultados esperados del desarrollo de esta solución incluyen:
1. **Mejora de la seguridad y movilidad:** El bastón inteligente proporcionará un mejor monitoreo de la calidad de uso del mismo, con ello, el usuario mejorará su rehabilitación.
2. **Confianza y autonomía:** Al recibir alertas inmediatas, los usuarios se sentirán más seguros al caminar, lo que les permitirá moverse con mayor confianza y reducir la dependencia de terceros.
3. **Innovación:** Innovar el bastón blanco tradicional al integrar sensores para aumentar su eficiencia.


#### Pruebas del Prototipo:
Para probar el prototipo del bastón inteligente, se pueden realizar las siguientes pruebas conceptuales:

**Simulaciones controladas:** Crear entornos artificiales para evaluar la capacidad del bastón para detectar la fuerza y emitir alertas efectivas.

**Pruebas de usuario:** Probar el bastón con un grupo pequeño de personas con osteoartritis en un entorno controlado, midiendo la facilidad de uso y la efectividad de las alertas.

**Pruebas de campo:** Evaluar el funcionamiento del bastón con las características comunes de infraestructuras reales, para validar su desempeño en situaciones cotidianas.


### BIBLIOGRAFÍA
- [[1]H. Long, Q. Liu, H. Yin, N. Diao, Y. Zhang, J. Lin, et al., "Prevalence trends of site-specific osteoarthritis from 1990 to 2019: Findings from the global burden of disease study 2019," *Arthritis Rheumatol*, vol. 74, no. 7, pp. 1172-1183, 2022.
- [2] A. Cieza, K. Causey, K. Kamenow, S. Wulf Hansen, S. Chatterji, and T. Vos, "Global estimates of the need for rehabilitation based on the Global Burden of Disease study 2019: a systematic analysis for the Global Burden of Disease Study 2019," *Lancet*, vol. 396, no. 10267, pp. 2006–2017, Dec. 2020.
- [3] R. L. Routson, M. Bailey, I. Pumford, J. M. Czerniecki, y P. M. Aubin, «A smart cane with vibrotactile biofeedback improves cane loading for people with knee osteoarthritis», en 2016 38th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), ago. 2016, pp. 3370-3373. doi: 10.1109/EMBC.2016.7591450.
