# Ejercicio 2 — Descripción PEAS de agentes inteligentes

### 1. Asistente virtual de voz

- **Performance:** Precisión de reconocimiento de voz, nivel de satisfacción del usuario, indice de acierto en la ejecución de acciones.
- **Environment:** Ruido ambiental, modismos locales, idioma de la persona, conectividad a otros dispositivos o internet.
- **Actuators:**  Protocolos de comunicación de red, reproducción de sonido.
- **Sensors:** Micrófono, altavoz, tarjeta de red.
- **AIMA:** El agente se puede considerar dinámico dado que las instrucciones pueden cambiar mientras este está procesando la misma, de igual forma se puede decir que es estocástico debido a la natural ambigüedad en el lenguaje ya sea por modismos, acentos, rapidez al hablar y entonación.

### 2. Robot aspirador doméstico

- **Performance:** Rapidez de limpieza, porcentaje de polvo en el suelo, número de veces que choca con un objeto, consumo de batería con respecto a la zona limpiada.
- **Environment:** Tomando en cuenta un ambiente de una casa podemos encontrar personas, mascotas y muebles, desnivel si se opera bajo un segundo piso, muros de habitación, objetos en el suelo, diferentes tipos de suelo, objetos regados por el suelo, cables de electrodomésticos.
- **Actuators:** Succionar, avanzar, girar, detenerse.
- **Sensors:** Sensor de proximidad, camara, giroscopio, acelerometro, sensor de desnivel. 
- **AIMA:** El agente se puede describir como dinámico por el simple hecho de que el ambiente cambia en función de si existe algún ser vivo, como lo puede ser una persona o una mascota, ya que este puede llegar a ponerse en el camino trazado por el agente, igualmente podemos clasificarlo como parcialmente observable dado que desconoce el estado de otras zonas del hogar mientras se encuentra en una habitación.


### 3. Sistema de recomendación de streaming

- **Performance:** Número de clicks en las recomendaciones, tiempo de reproducción de la recomendación.
- **Environment:** UI de plataforma, perfil del usuario, limitaciones geográficas y de ley ante contenido, metadatos del contenido.
- **Actuators:** Ordenar las recomendaciones, enviar notificaciones o correos con recomendaciones, personalización de títulos o thumbnails para más enganche (como hace Youtube)
- **Sensors:** Registro de interacción del usuario (click sobre la recomendación, solicitud de mostrar más o menos contenido similar), historial de reproducción, tipo de dispositivo, tendencias con perfiles similares.
- **AIMA:** El agente es parcialmente observable ya que aunque cuente con todos los datos del contenido de la plataforma, no cuenta con la información de la persona pues esta puede querer ver contenido dependiendo de su estado emocional, edad, genero u otras variables, además es estocástico ya que nada asegura que la recomendación sea aceptada por el usuario o siquiera realice alguna interacción con ella.


### 4. Vehículo autónomo en ciudad

- **Performance:** Llego al destino esperado, tomo la ruta más corta posible, nivel de satisfacción de los clientes transportados
- **Environment:** Carretera de la ciudad, peatones, señalizaciones, semáforos, otros vehículos, baches, carriles confinados, 
- **Actuators:** Acelerar el motor, frenado, girar a la izquierda, girar a la derecha, encender direccionales e intermitentes, encender aire acondicionado o calefactor, prender los faros del vehículo.
- **Sensors:** Cámara, sensor de proximidad, micrófono, sistema de navegación, sistema radar, sensores naturales de un vehículo (velocímetro, calentamiento del motor, cinturón de seguridad, sensor de lluvia, etc.)
- **AIMA:** El agente es claramente dinámico ya que el tráfico vehicular cambia de forma rápida y constante mientras este se encuentra procesando la información, igualmente podemos decir que es continuo ya que las operaciones como rotación y aceleración operan bajo una medición continua y no puntual y por ultimo es multiagente ya que opera con los diferentes agentes de sus sensores para tomar una decisión.


### 5. Agente de trading algorítmico en bolsa.

- **Performance:** Cantidad de retorno con respecto a la inversión, viabilidad de estrategias generadas.
- **Environment:** Mercado de bolsa, brokers, noticias financieras, sistemas de gráficas de vela en tiempo real, volatilidad de activos.
- **Actuators:** Compra y venta de activos, establecimiento de mínimo de beneficio y máximo de perdida, generación de estrategia.
- **Sensors:** Sistemas de mercado para gráficos de vela, disponibilidad de cartera en brokers, sistema de procesamiento de lenguaje natural.
- **AIMA:** El sistema es multiagente ya que se requiere de otro agente que se encargue del procesamiento de las noticias, asi mismo al trabajar en el sistema de valores existe una gran incertidumbre asi como cambios de forma rápida y continua por lo que podemos decir que es estocástico y dinámico.

### 6. Sistema de diagnóstico médico asistido por IA.

- **Performance:** Precisión de diagnostico, porcentaje de falsos positivos, porcentaje de falsos negativos.
- **Environment:** Hospital o clínica medica, interactúa con médicos, enfermeros y pacientes, sistema de registro medico.
- **Actuators:** Recomendaciones de diagnostico o pruebas adicionales, generación de informe médico, reproducción de sonido, toma de signos vitales.
- **Sensors:** Sensores de signos vitales (ritmo cardíaco, nivel de oxigenación en sangre), visión por computadora en radiografías, sistema de procesamiento de lenguaje natural para el historial medico.
- **AIMA:** El agente cumple se puede clasificar de la siguiente manera: parcialmente observable ya que habra signos o síntomas que no son notables a menos que se hagan ciertas pruebas, dinámico ya que el cuerpo humano puede verse afectado rápidamente por factores ambientales incluso en un hospital, secuencial debido a que un diagnostico puede agravar o mejorar la salud de la persona lo que afecta las decisiones futuras.


### 7. Dron de inspección de infraestructura.

- **Performance:** Precisión en la detección de problemas estructurales, tiempo de vuelo.
- **Environment:** Construcción civil, condiciones climáticas adversas, cables de electricidad, poca o mucha iluminación
- **Actuators:** Acelerado y frenado de motores de vuelo, transmisión de imágenes, rotación y enfoque de camara, sistema de iluminación auxiliar.
- **Sensors:** Camara, sensor de proximidad, GPS, giroscopio, acelerometro.
- **AIMA:** Claramente un dron es parcialmente observable ya que este podría observar unicamente los errores estructurales que son notables por fuera y no los que se encuentran de forma interna, a su vez, pertenece al ámbito dinámico ya que la percepción puede variar debido a que una estructura se encuentra ante la intemperie en donde los cambios son constantes, de igual forma, el tiene una característica AIMA continua ya que la percepción del agente cambia en función de su posición y dirección en el espacio.

### 8. Agente jugador de ajedrez (con tablero físico)

- **Performance:** Tiempo de reacción, número de movimientos antes de ganar, tasa de victorias, cumplimiento de las reglas.
- **Environment:** Brazo robótico, un contrincante, reloj de tiempo, variaciones en el nivel de iluminación.
- **Actuators:** Abrir o cerrar pinzas del brazo, mover el brazo, apretar botón del reloj.
- **Sensors:** Camara, sensor de presión para detectar la correcta sujeción de una pieza.
- **AIMA:** En este caso el agente es secuencial debido a que el movimiento de una pieza afecta y limita los posibles estados futuros asimismo es discreto ya que la cantidad de movimientos que pueden partir de un estado son finitos, por otro lado, es estático ya que el ambiente no cambia hasta que el agente realice su acción.

