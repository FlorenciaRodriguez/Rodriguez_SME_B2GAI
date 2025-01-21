# Inteligencia artificial

La inteligencia artificial (IA) es la rama de la informática que estudia el desarrollo de sistemas y programas capaces de realizar tareas que normalmente requieren inteligencia humana. 
Estos sistemas pueden simular procesos cognitivos como el aprendizaje, la toma de decisiones, el reconocimiento de patrones y el procesamiento de lenguaje natural (PLN).  

Los sistemas de IA aprenden y mejoran a través de la exposición a grandes cantidades de datos, lo que permite identificar patrones y relaciones que las personas pueden pasar por alto. 
Este proceso de aprendizaje suele implicar algoritmos, que son conjuntos de reglas o instrucciones que guían el análisis y la toma de decisiones de la IA. 

## Aprendizaje automático y el aprendizaje profundo

La IA abarca el aprendizaje automático y el aprendizaje profundo. Estas disciplinas implican el desarrollo de algoritmos de IA, modelados a partir de los procesos de toma de decisiones del cerebro humano, que pueden aprender de los datos disponibles y realizar clasificaciones o predicciones cada vez más precisas.

El aprendizaje profundo (deep learning) y el aprendizaje automático (machine learning) tienden a ser utilizados indistintamente, sin embargo, no son lo mismo. De hecho, el deep learning es un subcampo del machine learning. 

La principal diferencia está en cómo aprende cada algoritmo. Aprender en este contexto quiere decir, identificar patrones complejos en millones de datos. 

Los algoritmos de machine learning aprenden datos, identificar patrones y tomar decisiones con una mínima intervención humana. Los humanos determinan la jerarquía de características para comprender las diferencias entre las entradas de datos. El deep learning automatiza gran parte de la fase de extracción de características, lo que elimina parte de la intervención humana manual necesaria y permite el uso de conjuntos de datos más grandes. 

## Inteligencia artificial generativa

En los últimos años, la inteligencia artificial generativa (IAG) ha ganado gran relevancia gracias al desarrollo de modelos avanzados como Chat GPT, Mid Journey, DALL·E y otros sistemas capaces de crear texto, imágenes, música y código con un nivel de calidad cercano al humano. Estas herramientas han revolucionado sectores como el marketing, la educación, el arte y la programación, facilitando la automatización de tareas creativas y el desarrollo de soluciones innovadoras. La IAG no solo optimiza procesos existentes, sino que también abre nuevas oportunidades de negocio, redefiniendo la forma en que interactuamos con la tecnología y la información.

En líneas generales, la inteligencia artificial generativa (IAG) se refiere a una rama de la IA que se centra en el desarrollo de sistemas que pueden crear contenido nuevo y original, en lugar de simplemente analizar o procesar información existente. Específicamente tienen capacidad para comprender y crear en el ámbito del lenguaje natural, el código y otras representaciones simbólicas como la música, la fotografía y la ilustración. 

La IAG trabaja sobre los principios del machine learning. Sin embargo, a diferencia de los modelos tradicionales que aprenden patrones y realizan predicciones o decisiones basadas en dichos patrones, la IAG da un paso dado que también crea nuevas instancias de datos que imitan las propiedades de los datos de entrada.

La IAG utiliza algoritmos de las siguientes categorías del aprendizaje automático:

Aprendizaje supervisado: son algoritmos entrenados utilizando ejemplos etiquetados, como una entrada donde se conoce el resultado deseado. El modelo de IAG se puede ajustar con datos específicos para producir un tipo específico de contenido. 

Aprendizaje no supervisado: se utiliza con datos que no tienen etiquetas. Los modelos de IAG se pueden entrenar con datos no etiquetados para generar nuevas muestras similares a la distribución de datos. Esto se hace para mejorar el rendimiento de los modelos no supervisados.

Aprendizaje por refuerzo: se utiliza en escenarios donde el proceso de generación implica una secuencia de decisiones, como generar un diálogo en un agente conversacional o acciones en un juego. El algoritmo descubre a través de ensayo y error qué acciones producen las mayores recompensas.

## Flujo de trabajo

El flujo de trabajo general para poner a trabajar la IAG es el siguiente.

Establecer el objetivo:  es vital entender el problema a resolver y cuáles son los objetivos dado las características de la empresa, así como de la data que tendremos a disposición. 

Recopilación de datos: se recopila un gran conjunto de datos que contiene ejemplos del tipo de contenido que se va a generar. Por ejemplo, un conjunto de datos de imágenes para generar imágenes realistas, o un dataset de texto para generar oraciones coherentes. Existen diversas fuentes, pero las más comunes son: Data First Party (datos propios de la empresa (ERP,CRM, etc); Data Second Party (datos que comparte una organización con sus aliados estratégicos) y Data Third Party (datos de terceros que se obtienen ya sea de forma gratuita o incurriendo en algún tipo de costo asociado).

Preparación de datos: normalmente se conoce como la limpieza de los datos o el formateo del dato. El objetivo de esta etapa es manipular y convertir la data en formas que produzcan mejores resultados. Algunos ejemplos, son eliminar o inferir datos perdidos, categorizar los valores de las variables, normalizar los valores numéricos o escalarlos para que puedan ser comparables.

Creación del modelo: el modelo se forma con el dataset para aprender los patrones y estructuras subyacentes en los datos. Para ello se divide los datos en dos conjuntos: entrenamiento y test.

Entrenamiento del modelo: el proceso de entrenamiento consiste en proporcionar al modelo datos de entrenamiento de los cuales pueda aprender.

Validar modelo: se realizará con la data de validación y se ejecuta el algoritmo y se evaluarán los resultados obtenidos.  En el caso de que los resultados no sean satisfactorios, se vuelve a la etapa de creación hasta que nuestro modelo se ajuste bien a las dos particiones (data de entrenamiento y data de validación).

Perfeccionamiento: el contenido generado es una síntesis de lo que el modelo ha aprendido de los datos de formación. Dependiendo de la tarea y la aplicación, el contenido generado puede someterse a un mayor refinamiento o post-procesamiento para mejorar su calidad o para cumplir con requisitos específicos.

Implementación en producción. Generalmente, se despliega en la nube a través de los 3 vendedores más conocidos que existen actualmente: AWS, Azure y GCP. 

## IA en las organizaciones

Uno de los mayores obstáculos para el uso de la IA es encontrar casos de uso adecuados, a pesar de que Internet está inundado de ejemplos de casi todos los sectores. La razón es que no están claros los principios operativos y las condiciones que hacen que un proyecto de inteligencia artificial tenga éxito. 

Muchas veces el caso de uso puede resolverse sin utilizar IA. Por ejemplo, en un chat de atención al cliente en línea, una persona podría responder preguntas en lugar de utilizar métodos de IA. En este caso, se deben sopesar las fortalezas y debilidades de las alternativas a corto y largo plazo. Una matriz como la siguiente puede ayudar a clarificar la prioridad de cada caso (Tabla 1).

Tabla 1. Matriz para análisis de impacto de caso de uso



Las soluciones basadas en IAG pueden conducir a la creación de nuevos modelos de negocio o transformar radicalmente las experiencias de los clientes, lo que puede no tener impactos inmediatos y directos, pero ofrece un valor significativo a largo plazo. 

Además de considerar únicamente las dimensiones de impacto y de entrada, también es importante considerar el riesgo, así como las cuestiones éticas, incluida la privacidad de los datos, las cuestiones de derechos de autor y el posible uso indebido del contenido generado. Los casos de uso con mayores riesgos éticos requieren una gobernanza y una supervisión más exhaustivas, lo que podría afectar su viabilidad y aceptación pública.

## Lienzo de trabajo

En general, no es evidente que un proyecto de IA tenga éxito o no. No todos los proyectos de IA han logrado sus objetivos, incluso si las soluciones producidas fueron muy exitosas desde un punto de vista técnico. De hecho, la razón de los fracasos está relacionada con factores ajenos a la tecnología de IA que no han recibido suficiente atención.

Una buena planificación ayuda a analizar un proyecto desde múltiples perspectivas. Además de las condiciones técnicas, se debe tener en cuenta los factores y tareas comerciales para la solución diseñada.

Para planificar ello se puede usar un lienzo de datos. El objetivo es obtener una imagen lo más realista posible de las condiciones y los riesgos para el éxito del proyecto de IA planificado antes de tomar una decisión de inversión. El uso de un lienzo ayuda a separar las buenas ideas de las malas (Tabla 2). 

En líneas generales el lienzo de IA consta de diez áreas que afectan la implementación y el uso de una solución de IA. El objetivo es describir cada caso de uso planificado en su propio lienzo, punto por punto.

La estructura del lienzo no es inamovible y los campos se pueden combinar. Lo esencial es que las cuestiones clave se puedan considerar con suficiente precisión.

Tabla 2. Lienzo de IA

Descripción de la solución y necesidad empresarial

La forma más clara de comenzar a utilizar un lienzo es describir la solución planificada, incluido el problema que resuelve, a quién afecta y cómo funciona en general. Este campo debe indicar al lector cuál es la solución y por qué es necesaria.

Retorno de la inversión

En el mundo de los negocios, las inversiones suelen tener como objetivo la productividad. Hay tres formas de analizar una inversión: rentabilidad, costos y riesgos. Este modelo también se aplica al diseño de soluciones de IA. Al evaluar los riesgos, se debe prestar especial atención a los recursos necesarios, la disponibilidad y calidad de los datos y la experiencia necesaria.

La revisión de una solución planificada puede comenzar evaluando sus beneficios, como por ejemplo, ahorro de tiempo de trabajo, aumento de ventas, reducción de costos, ahorro de energía o reducción de daños. En una situación óptima, los beneficios se pueden medir y describir numéricamente. 

Métrica 

El campo de métricas se utiliza para definir los objetivos de la solución de IA y cómo se mide el éxito. 

Partes interesadas

Durante la fase de diseño de una solución, se deben identificar las partes interesadas clave cuyo aporte es necesario para implementarla y cuyo trabajo se verá afectado por ella. Las partes interesadas varían de un proyecto a otro, por lo que no se puede crear una lista universal. 

Habilidades requeridas

Los conocimientos técnicos necesarios para los proyectos de IA varían entre las distintas soluciones. Normalmente, los proyectos tienen los siguientes roles: propietario del producto, ingeniero de datos, científico de datos y gerente de proyecto.

Datos

El elemento más importante de un lienzo de IA son los datos, porque sin datos adecuados normalmente no se puede implementar una solución. Se debe invertir en la clarificación de los datos. La disponibilidad, calidad, cantidad y posibles cambios futuros que afecten a los datos se deben discutir con todas las partes interesadas pertinentes.

Aprendizaje automático

Si bien el aprendizaje automático es el núcleo de las soluciones de IA, no es necesario profundizar en él en un lienzo de IA. 

Software e infraestructura técnica

El diseño del software de la solución incluye las herramientas que se utilizarán para la transferencia, procesamiento, almacenamiento y visualización de datos, así como para la ejecución de modelos de aprendizaje automático y el análisis de resultados. 

La infraestructura técnica se refiere a los dispositivos físicos que producen datos. Por lo general, se trata de cámaras o sensores de Internet de las cosas (IoT). La transferencia de datos desde los dispositivos al software requiere protocolos que deben aclararse en esta etapa.

El diseño no debe limitarse a las necesidades de la fase de desarrollo, sino que debe ampliarse también a su uso futuro. De este modo, se garantiza que una prueba de concepto o un proyecto piloto que hayan tenido éxito no se vean impedidos de pasar a producción porque no se dan las condiciones técnicas para ello.

Procesos

No es raro que una empresa implemente una solución de IA que ha demostrado ser técnicamente exitosa y que luego no se utilice. A menudo, esto se debe a que la solución no se ha integrado en los procesos y prácticas de la empresa. 

Ética y RGPD

La ética y el RGPD (Reglamento General de Protección de Datos) son áreas nuevas pero importantes en el ámbito de la IA. La ética de la IA y las normas del RGPD deben tenerse en cuenta, especialmente si la solución planificada implica datos personales o toma de decisiones automatizada.
Se recomienda que un experto en RGPD participe en la fase de diseño de un proyecto, ya que puede resultar difícil para una persona normal comprender el alcance y la aplicación de la legislación. 

## Desafíos de implementar IAG
Los desafíos en la implementación de IAG abarcan una serie de preocupaciones técnicas y éticas que deben abordarse a medida que la tecnología se va adoptando más ampliamente. A continuación se muestran algunos de los principales desafíos a los que se enfrentan hoy las organizaciones.

Datos: los modelos de IAG requieren una cantidad significativa de datos relevantes de alta calidad para entrenarse de manera eficaz. Adquirir dichos datos puede ser un desafío, particularmente en dominios donde son escasos, confidenciales o protegidos, como en finanzas o cuidado de la salud. Además, garantizar la diversidad y representatividad de los datos para evitar sesgos en el resultado generado puede ser una tarea compleja. 

Complejidad del entrenamiento: entrenar modelos de IAG requiere un uso intensivo de recursos de computación, consume mucho tiempo, y es costoso. Requiere cantidades significativas de recursos y expertise, lo cual puede ser una barrera para las organizaciones más pequeñas o nuevas en IA. El entrenamiento distribuido, donde el proceso se divide entre múltiples máquinas o GPU, puede ayudar a acelerarlo. Además, la transferencia del aprendizaje, una técnica donde un modelo pre entrenado se ajusta a una tarea específica, puede reducir la complejidad y los requisitos de recursos del entrenamiento.

Controlar el resultado: controlar los resultados de la IAG puede ser un desafío. Los modelos generativos pueden generar contenido no deseable o irrelevante. Por ejemplo, los modelos de IA podrían crear un texto ficticio, incorrecto, ofensivo o sesgado. Mejorar el entrenamiento del modelo brindando datos más diversos y representativos puede ayudar a resolver este problema. Además, implementar mecanismos para filtrar o verificar el contenido generado puede garantizar su relevancia y adecuación.

Preocupaciones éticas: la IAG plantea varias preocupaciones éticas, especialmente en términos de la autenticidad e integridad del contenido generado. Los deep fakes, creados por las GAN, pueden ser mal utilizados para difundir información errónea o cometer actividades fraudulentas. Se pueden emplear modelos de texto generativos para crear artículos de noticias engañosos o reseñas falsas. Es crucial establecer pautas éticas sólidas para el uso de la IA generativa. Tecnologías como la marca de agua digital o el blockchain pueden ayudar a hacer seguimiento y autenticar el contenido generado por IA. Además, desarrollar la alfabetización en IA entre el público puede mitigar los riesgos de desinformación y fraude.

Obstáculos regulatorios: faltan directrices reglamentarias claras para el uso de la IA generativa. Dado que la IA continúa evolucionando rápido, las leyes y regulaciones tienen dificultades para mantenerse al día, lo cual lleva a incertidumbres y posibles conflictos legales.

# Bibliografía

Banh, L., & Strobel, G. (2023). Generative artificial intelligence. _Electronic Markets, 33_(1), 63.

Buonamici, F., Carfagni, M., Furferi, R., Volpe, Y., & Governi, L. (2020). Generative design: an explorative study. _Computer-Aided Design and Applications, 18_(1), 144-155.

Chew, Z. X., Wong, J. Y., Tang, Y. H., Yip, C. C., & Maul, T. (2024). Generative design in the built environment. _Automation in Construction_, 166, 105638.

Helmus, T. C. (2022). Artificial intelligence, deepfakes, and disinformation. _RAND Corporation_, 1-24.

Hyunjin, C. (2020). A study on application of generative design system in manufacturing process. _In IOP Conference Series: Materials Science and Engineering_ (Vol. 727, No. 1, p. 012011). IOP Publishing.

Jovanovic, M., & Campbell, M. (2022). Generative artificial intelligence: Trends and prospects. _Computer, 55_(10), 107-112.

Lucchi, N. (2024). ChatGPT: a case study on copyright challenges for generative artificial intelligence systems. _European Journal of Risk Regulation, 15_(3), 602-624.

Njeru, F. (2023). A Review of Artificial Intelligence and its Application in Business. _Journal of Enterprise and Business Intelligence, 3_(1), 044-053.

Romero Moreno, F. (2024). Generative AI and deepfakes: a human rights approach to tackling harmful content. _International Review of Law, Computers & Technology_, 1-30.

Russell, S. J., & Norvig, P. (2016). Artificial intelligence: a modern approach. _Pearson_.

Sestino, A., & De Mauro, A. (2022). Leveraging artificial intelligence in business: Implications, applications and methods. _Technology Analysis & Strategic Management, 34_(1), 16-29.

Sharma, A. K., & Sharma, R. (2024). Generative Artificial Intelligence and Legal Frameworks: Identifying Challenges and Proposing Regulatory Reforms. _Kutafin Law Review, 11_(3), 415-451.

Shoaib, M. R., Wang, Z., Ahvanooey, M. T., & Zhao, J. (2023, November). Deepfakes, misinformation, and disinformation in the era of frontier AI, generative AI, and large AI models. In _2023 International Conference on Computer and Applications (ICCA)_ (pp. 1-7). IEEE.

Thakur, R. (2024). Introduction to artificial intelligence and its importance in modern business management. In _Leveraging AI and emotional intelligence in contemporary business organizations_ (pp. 133-165). IGI Global.

Yarovyi, A., Yarovyi, A., Kizim, S., & Ozeranskyi, V. (2024, June). Innovative trends in the field of modern artificial intelligence methodology. In ENVIRONMENT. TECHNOLOGIES. RESOURCES. _Proceedings of the International Scientific and Practical Conference_ (Vol. 2, pp. 132-137).

# Trabajo Práctico

Determinar si las sentencias son verdaderas o falsas

Al diseñar una solución de IA, es suficiente garantizar inicialmente la disponibilidad de los datos y la viabilidad técnica de la solución.

_Falso. Normalmente no es suficiente, por eso es conveniente utilizar un lienzo de IA_

Se pueden utilizar métricas no económicas para medir el éxito de los proyectos de inteligencia artificial.

_Verdadero. Por ejemplo, puede resultar difícil y hasta a veces imposible, calcular un valor monetario inmediato para una solución de IA que mejore la satisfacción laboral._

Al diseñar una solución de IA, las preguntas relacionadas con los datos se pueden responder en último lugar al completar el lienzo de inteligencia artificial.

_Falso. Sin datos no se puede implementar la solución, en cuyo caso los demás puntos tampoco son tan importantes. Por ello, es recomendable comprobar los aspectos relacionados con los datos en una fase temprana._

En la fase de planificación de un proyecto de IA, todavía no es necesario decidir el método de aprendizaje automático que se utilizará, ya que aún será posible hacerlo durante el proyecto.

_Falso. El método de aprendizaje automático que se utilizará puede estar claro en la etapa de diseño, pero esto no es necesario. En algunos proyectos de IA, se pueden probar varios métodos y analizar los resultados para determinar cuál se adapta mejor al caso en cuestión._

Una buena idea para el uso de la IA es amplia e integral, por ejemplo, “la inteligencia artificial optimiza la seguridad laboral”.

_Falso. De hecho, un buen caso de uso para la inteligencia artificial es aquel que es lo más preciso y claro posible, y para nada ambiguo. Por ejemplo, “la inteligencia artificial da una advertencia si faltan las gafas durante el paso de trabajo X” es una descripción precisa del caso de uso._

En los proyectos de inteligencia artificial, la mayor parte del trabajo generalmente se centra en crear los mejores modelos de aprendizaje automático.

_Falso. La creación de modelos de aprendizaje automático suele ser una parte relativamente pequeña de un proyecto. Por ejemplo, la creación de canales de datos y el procesamiento de datos para que se ajusten suelen ser pasos de trabajo mucho más grandes._

La experiencia requerida en proyectos de inteligencia artificial varía según el proyecto, pero el propietario del producto, el gerente del proyecto, el ingeniero de datos y el científico de datos siempre desempeñan roles clave.

_Falso. Además de estos, puede ser necesario un desarrollador de software o un experto en informes para que los pronósticos realizados por la IA sean visibles para los usuarios._

2. A continuación se presentan tres casos de uso diferentes para la inteligencia artificial. Evalúe en qué parte de la matriz se encuentra cada uno de ellos según las opciones dadas.

Un vehículo autónomo que puede transportar materiales de construcción de un lugar a otro en el sitio, reemplazando la mano de obra.

i. Bajo impacto, baja inversión

ii. Alto impacto, alta inversión

_Alto impacto, alta inversión. La solución sería sin duda útil, pero su aplicación práctica requeriría recursos considerables._

Con base en los datos del software de seguimiento del tiempo en las obras de construcción, se pronostica el número de ausencias para el próximo trimestre.

i. Bajo impacto, baja inversión

ii. Bajo impacto, alta inversión

_La respuesta correcta es bajo impacto, baja inversión. La solución probablemente sería bastante fácil de implementar ya que los datos están disponibles y el objetivo es claro. Sin embargo, el valor comercial de la solución no es alto porque el pronóstico es para un período que no ayudará a la gerencia a tomar decisiones operativas; su valor comercial sería mayor si fuera para la semana siguiente._
