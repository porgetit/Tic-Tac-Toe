# Tres en Raya (Tic-Tac-Toe) en Línea de Comandos

## Descripción del Proyecto

Este proyecto consiste en una implementación del clásico juego "Tres en Raya" (Tic-Tac-Toe) en línea de comandos utilizando el lenguaje de programación Java. El juego permite a dos jugadores competir entre sí en varias partidas.

## Estructura del Proyecto

El proyecto está dividido en cinco clases:

1. **Juego.java**
   - Esta clase representa el juego en sí. Contiene la lógica principal, incluyendo la inicialización de jugadores, el tablero y las reglas de victoria. Además, gestiona el estado del juego, los movimientos de los jugadores y determina al ganador.

2. **Jugador.java**
   - La clase define la estructura de un jugador, con atributos como ID, nombre y puntuación. También proporciona métodos para acceder y modificar estos atributos.

3. **Partida.java**
   - Representa una serie de juegos consecutivos. Al iniciar una partida, solicita los nombres de los jugadores y crea múltiples instancias de la clase `Juego`.

4. **Tablero.java**
   - Esta clase modela el tablero del juego. Contiene métodos para verificar el estado del tablero, determinar si una casilla está ocupada, obtener casillas libres, y permitir a los jugadores realizar movimientos.

5. **Tictactoe.java**
   - La clase principal del programa que inicia el juego en línea de comandos. En este caso, un juego de ejemplo se lleva a cabo en el método `main`.

## Instrucciones de Uso

1. **Ejecución del Juego**
   - El punto de entrada principal es la clase `Tictactoe.java`. Al ejecutar este archivo, se iniciará una partida y se solicitarán los nombres de los jugadores.

2. **Realizar Movimientos**
   - Durante el juego, los jugadores realizarán movimientos seleccionando una casilla disponible en el tablero.

3. **Finalización del Juego**
   - El juego continúa hasta que se alcanza un estado de victoria o empate. Al final de cada partida, se muestra el ganador y se actualizan las puntuaciones de los jugadores.

## Consideraciones Importantes

- El proyecto utiliza expresiones regulares para definir los estados de victoria. Estos patrones representan todas las combinaciones posibles para ganar el juego.

- El código está estructurado de manera modular, facilitando la expansión o modificación del juego.

- El programa está diseñado para ejecutarse en la línea de comandos, lo que facilita su uso en cualquier entorno que admita Java.

¡Disfruta del juego de Tres en Raya en la línea de comandos! Si tienes alguna pregunta o sugerencia, no dudes en contactar al autor.
