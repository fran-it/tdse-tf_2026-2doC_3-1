# **Juego de reflejos con pulsadores retroiluminados**
## **Informe de Avances**


**Autores: Santander, Cristian; Flores Quiroga, Tobías; Itria, Franco**

**Padrones: 112.109; 111.546; 110.191**

**Fecha: 2do cuatrimestre 2026**

A continuación se detalla el informe de avances del proyecto a partir de los requerimientos establecidos.

| Estado | Descripción                 |
| ------ | --------------------------- |
| 🟢     | Ya implementado             |
| 🟡     | En proceso de implementarse |
| 🔴     | No se implementará          |

#### **Lógica y Control**  

| Req ID | Descripción | Estado | 
|--------|-------------|--------|  
| 1.1    | El sistema contará con una unidad de control que seleccionará de forma aleatoria qué pulsador debe activarse. | 🟡 |  
| 1.2    | El sistema gestionará la velocidad de aparición de los estímulos y el tiempo máximo de respuesta para determinar la dificultad. | 🟡 |  
| 1.3    | El inicio y finalización de las partidas se realizará de forma automática en base a un tiempo de juego preestablecido. | 🟡 |  

#### **Interfaz de Usuario**  

| Req ID | Descripción                                                                                                                        | Estado |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------- | ------ |
| 2.1    | El panel de juego estará compuesto por pulsadores físicos que incluirán indicadores luminosos para identificar el estímulo activo. | 🟡     |
| 2.2    | El sistema contará con un pulsador de inicio dedicado exclusivamente para habilitar una nueva secuencia de juego.                  | 🟡     |
| 2.3    | Se incorporará un display digital que mostrará el puntaje acumulado durante la partida y el resultado al finalizar.                | 🟡     |

#### **Puntuación y Reglas**  

| Req ID | Descripción                                                                                                                  | Estado |
| ------ | ---------------------------------------------------------------------------------------------------------------------------- | ------ |
| 3.1    | Respuesta correcta: Si el jugador presiona el pulsador iluminado a tiempo, se registrará y sumará un punto.                  | 🟡     |
| 3.2    | Respuesta incorrecta: Si el jugador presiona un pulsador apagado, el sistema registrará el error y no sumará puntos.         | 🟡     |
| 3.3    | Tiempo agotado: Si expira el intervalo del estímulo sin respuesta, la oportunidad se pierde y se genera una nueva secuencia. | 🟡     |

#### **Energía**  

| Req ID | Descripción                                                                                                                     | Estado |
| ------ | ------------------------------------------------------------------------------------------------------------------------------- | ------ |
| 4.1    | El sistema de alimentación proporcionará tensiones estables para la unidad de control, los LEDs de los pulsadores y el display. | 🟡     |

#### **Escalabilidad (Post-MVP)**
| Req ID | Descripción                                                                                                                     | Estado |
| ------ | ------------------------------------------------------------------------------------------------------------------------------- | ------ |
| 5.1    | Memoria externa (EEPROM): El sistema almacenará los mejores puntajes históricos incluso al apagarse.                            | 🟡     |
| 5.2    | Módulo de Audio (Buzzer): El sistema emitirá sonidos de acierto, error y fin de partida.                                        | 🟡     |
| 5.3    | Sensor LDR: El brillo de los pulsadores y el display se ajustará automáticamente según la luz ambiente.                         | 🟡     |
| 5.4    | Módulo BLE/Wi-Fi: Permitirá enviar los puntajes a una aplicación móvil.                                                         | 🟡     |
| 5.5    | Enlace multijugador: Permitirá conectar dos consolas para partidas competitivas simultáneas.                                    | 🔴     |
