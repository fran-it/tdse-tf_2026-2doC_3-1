# Propuesta de proyecto: Juego de reflejos con pulsadores retroiluminados

## 1. Descripción del juego
El proyecto consiste en el desarrollo de un juego electrónico de destreza y velocidad de reacción, inspirado en la mecánica del clásico Whac-A-Mole. La propuesta consiste en reemplazar los elementos mecánicos tradicionales por un conjunto de pulsadores retroiluminados, distribuidos sobre un panel de juego.

La dinámica se basa en la activación aleatoria de los pulsadores mediante señales luminosas. El jugador deberá identificar cuál de ellos se encuentra encendido y presionarlo en el menor tiempo posible para obtener puntos. Una vez registrada la respuesta, el sistema generará un nuevo estímulo, continuando la secuencia durante el tiempo establecido para cada partida.

El objetivo principal será conseguir la mayor cantidad de puntos posibles antes de que finalice el tiempo disponible. La dificultad estará determinada por la velocidad de aparición de los estímulos y el tiempo máximo permitido para responder.

Cada partida comenzará mediante un pulsador de inicio y finalizará automáticamente al agotarse el tiempo. Al concluir, se mostrará el puntaje total obtenido por el jugador.

## 2. Reglas de puntuación
El sistema contará con un mecanismo de puntuación que permitirá evaluar el desempeño del jugador durante cada partida.

Las reglas iniciales propuestas son:
* Respuesta correcta: presionar el pulsador iluminado dentro del tiempo establecido. Se sumará un punto al marcador.
* Respuesta incorrecta: presionar un pulsador diferente al que se encuentra iluminado. No se sumarán puntos y se podrá aplicar una penalización.
* Tiempo agotado: si el jugador no responde antes de que finalice el intervalo asignado al estímulo, la oportunidad se considerará perdida y se continuará con una nueva secuencia.
* Finalización de partida: una vez cumplido el tiempo total de juego, se detendrá la generación de estímulos y se visualizará el puntaje acumulado.

## 3. Implementación propuesta (MVP)

Para la primera versión funcional del proyecto (MVP), se plantea implementar un sistema electrónico compuesto por los siguientes elementos:

Unidad de control: será responsable de administrar la lógica del juego, seleccionar aleatoriamente los pulsadores que se activarán, registrar las respuestas y gestionar los tiempos y la puntuación.

Pulsadores retroiluminados: constituirán la interfaz principal de interacción con el usuario. Cada pulsador contará con un indicador luminoso que permitirá identificar visualmente el estímulo activo. Además, permitirán registrar las acciones del jugador.

Display de visualización: se incorporará un display digital para mostrar el puntaje acumulado durante la partida y el resultado final una vez concluida.

Pulsador de inicio: permitirá iniciar una nueva partida y habilitar la secuencia de juego.

Sistema de alimentación: proporcionará las tensiones necesarias para el funcionamiento de la unidad de control, los indicadores luminosos y los dispositivos de visualización.

## 4. Alcance del proyecto

El alcance de esta primera etapa estará limitado al desarrollo de un prototipo funcional que permita ejecutar partidas individuales y registrar el desempeño del jugador.

Se consideran incluidas las siguientes funcionalidades:

* Diseño y montaje del panel de juego con pulsadores retroiluminados.

* Implementación del sistema de control y generación aleatoria de estímulos.

* Detección de las pulsaciones y validación de las respuestas.

* Gestión de los tiempos de juego y de respuesta.

* Implementación del sistema de puntuación.

* Visualización del puntaje mediante un display digital.

* Inicio y finalización automática de las partidas.

Se buscará obtener un dispositivo autónomo, de funcionamiento intuitivo y que permita demostrar la integración entre hardware y software mediante una aplicación interactiva.

Quedarán fuera del alcance inicial funcionalidades adicionales como la conexión entre múltiples dispositivos, los modos multijugador, el almacenamiento permanente de récords, la configuración avanzada de dificultad y la incorporación de una interfaz gráfica compleja. Estas características podrán considerarse como posibles ampliaciones en futuras etapas del proyecto.
