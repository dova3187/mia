# Descripción PEAS de agentes inteligentes

### Asistente virtual de voz 

- **Performance:** Ejecutar la tarea especifica que solicita el usuario, de manera que satisfaga sus necesidades.
- **Environment:** Dispositivo electrónico.
 _Parcialmente observable:_ El asistente no tiene acceso al estado mental, emociones o intenciones reales del usuario; solo percibe la señal de audio de los comandos verbalizados.
- **Actuators:** Buscar o llamar a algún contacto del directorio, reproducir algúna canción, programar alguna alarma o recordatorio, enviar algún mensaje, solicitar el pronóstico del tiempo.
- **Sensors:** Micrófono, altavoz, horario, lecturas via internet.

### Robot aspirador doméstico 

- **Performance:** Recolección precisa de polvo y desechos encontrados en el área recorrida.
- **Environment:** Pisos de habitaciones y oficinas.
 _Dinámico:_ Las personas y mascotas se mueven en tiempo real, cambiando la configuración del entorno físico mientras el robot está navegando.
- **Actuators:** Recolectar desechos.
- **Sensors:** Sensor de distancia, sensor de colisión y parachoques, sensor de superficie, sensor infrarojo.

### Sistema de recomendación de streaming

- **Performance:** Que el usuario reproduzca el contenido sugerido; y dicho contenido debe ser de acuerdo a sus preferencias. 
- **Environment:** Plataforma de streaming.
 _Estocástico:_ El comportamiento humano es probabilístico y no determinista; la mejor sugerencia basada en el perfil del usuario puede ser rechazada arbitrariamente en cualquier momento.
- **Actuators:** Mostrar contenido.
- **Sensors:** Cantidad de reproducciones, busquedas, contenido relacionado, likes.

### Vehículo autónomo en ciudad

- **Performance:** Llegar al destino del usuario con presición y bajo costo.
- **Environment:** Las calles de la ciudad.
_Parcialmente observable:_ La geometría vial puede estar obstruida por edificios, camiones grandes o curvas cerradas; el agente no puede saber qué hay detrás de un camión o de una esquina hasta que tiene línea de visión.
- **Actuators:** Busqueda de ruta.
- **Sensors:** Sensor de distancia, sensor de colisión y parachoques, sensor de superficie, sensor infrarojo.

### Agente de trading algorítmico en bolsa

- **Performance:** Comprar y vender en la bolsa al mejor precio, tiempo y volumen.
- **Environment:** Plataforma del algoritmo.
_Dinámico:_ Las órdenes de los competidores se emparejan, los precios cambian y las cotizaciones fluctúan en milisegundos mientras el algoritmo procesa si ejecutar una compra o una venta.
- **Actuators:** Comprar y vender acciones, alertas informativas o reportes al usuario.
- **Sensors:** Monitor de datos del mercado en tiempo real, bases de datos historicas, monitor del estado de cuenta propio.

### Sistema de diagnóstico médico asistido por IA

- **Performance:** Precisión de diagnóstico, detectar patologías en etapas tempranas, reducción de falsos positivos, minimizar los costos para el paciente.
- **Environment:** Hospitales, laboratorios.
_Estocástico:_ La manifestación de los síntomas de una enfermedad presenta variaciones individuales impredecibles, y la respuesta biológica exacta del cuerpo humano a un tratamiento es probabilística.
- **Actuators:** Despliegue en pantalla de resultados de diagnósticos, sugerencias de pruebas de laboratorio, recomendar tratamientos clinicos.
- **Sensors:** Expendientes clínicos, pruebas de laboratorio, monitoreo en tiempo real de signos vitales.

### Dron de inspección de infraestructura 

- **Performance:** Porcentaje de área del lugar a mapear, precisión en la detección de las estructuras.
- **Environment:** Entorno exterior o interios de la estructura.
_Parcialmente observable:_ El dron no tiene acceso visual a las anomalías de la infraestructura que se encuentran ocultas bajo tierra, cubiertas por vegetación pesada o en el lado opuesto de las vigas hasta que realiza la aproximación de vuelo respectiva.
- **Actuators:** Control óptico, servomotores, reguladores de velocidad.
- **Sensors:** Sensor GPS, altimetro barómetrico, cámaras de visión, sensores térmicos.

### Agente jugador de ajedrez

- **Performance:** Tasa neta de victorias, cumplimiento de las reglas del juego, eficiencia en la búsqueda de jugadas.
- **Environment:** Tablero de ajedrez digital, piezas del ajedrez.
_Estático:_ La configuración de las piezas en el tablero no sufre alteraciones ajenas mientras el agente se encuentra ejecutando su cálculo para decidir la siguiente jugada.
- **Actuators:** Visualización gráfica de la jugada, generación de jugadas.
- **Sensors:** Percepción visual de movimientos, lecturas de tiempo para las jugadas.
