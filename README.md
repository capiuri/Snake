# Juego de la Serpiente con Turtle

Este proyecto es una implementación clásica del juego de la **Serpiente** utilizando la biblioteca `turtle` en Python. El juego consiste en controlar una serpiente para comer la comida que aparece en el tablero y evitar colisiones con los bordes del área de juego y con el propio cuerpo de la serpiente.

## Requisitos

- Python 3.x
- Biblioteca `turtle` (incluida con Python por defecto)

## Cómo Jugar

1. **Ejecuta el script** para iniciar el juego:

    ```bash
    python main.py
    ```

2. **Controles del juego**:
   - **Flecha hacia arriba**: Mueve la serpiente hacia arriba.
   - **Flecha hacia abajo**: Mueve la serpiente hacia abajo.
   - **Flecha hacia la izquierda**: Mueve la serpiente hacia la izquierda.
   - **Flecha hacia la derecha**: Mueve la serpiente hacia la derecha.

3. **Objetivo del juego**:
   - Come la comida que aparece en el tablero para aumentar la longitud de la serpiente y obtener puntos.
   - Evita chocar contra los bordes del tablero y contra el propio cuerpo de la serpiente.

4. **Marcador**:
   - El puntaje se muestra en la parte superior del tablero.
   - El puntaje se incrementa en 10 puntos cada vez que la serpiente come la comida.
   - El puntaje más alto (High Score) se guarda y se muestra en la pantalla.

5. **Fin del juego**:
   - El juego termina si la serpiente choca contra los bordes del tablero o contra su propio cuerpo.
   - La serpiente se reinicia en el centro del tablero y el puntaje se restablece a 0.

## Personalización

Puedes ajustar el tamaño del tablero y la velocidad del juego cambiando los valores en el script:

- **Velocidad del juego**: Ajusta el valor de la variable `posponer` (en segundos) para cambiar la velocidad del juego. Por ejemplo, `posponer = 0.1` controla la frecuencia de actualización del juego.
