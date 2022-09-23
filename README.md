# EY Front Challenge

## Descripción
En este documento se presentan los requerimientos necesarios para realizar el desafío practico frontend.

## Desafío
Se requiere re-crear el clásico juego de Buscaminas. El objetivo del juego es despejar un campo de minas sin detonar ninguna.

## Reglas del juego
El juego consiste en despejar todas las celdas de un tablero que no oculten una mina.

Algunas celdas tienen un número, el cual indica la cantidad de minas que hay en las celdas circundantes. Así, si una celda tiene el número 3, significa que de las ocho celdas que hay alrededor (si no es en una esquina o borde) hay 3 celdas con minas y 5 celdas sin minas.

Si se descubre una celda sin número indica que ninguna de las celdas vecinas tiene mina y éstas se descubren automáticamente.

Si se descubre una celda con una mina se pierde la partida.

[opcional]
Se puede poner una marca en las celdas que el jugador piensa que hay minas para ayudar a descubrir las que están cerca.

## Restricciones
- El tablero de juego debe ser una cuadricula de 10x10 celdas.
- Deben haber al menos 10 minas ocultas aleatoriamente en el tablero.
- Las minas deben estar inicialmente ocultas.
- Se deben respetar todas las reglas del juego.
- Una celda puede contener una bomba, un numero o un espacio vacío.
- Se debe utilizar el click izquierdo sobre una celda para validar si existe bomba.
- Se debe implementar pruebas unitarias a la lógica del juego.
- El juego finaliza si se despeja todo el tablero de minas sin detonar ninguna.
- El juego finaliza si la celda activada es una bomba.

## Restricciones técnicas
- Presentar el código con un nivel de calidad de Producción.
- Presentar la solución en un repositorio (Github).
- Pruebas unitarias.

## Bien recibido
- Frameworks de estilos css.
- Linting.
- Librerías de externos.
- README con descripción e información para compilar, probar y testear la aplicación.
- Metodologías para aplicar pruebas.
