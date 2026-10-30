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
