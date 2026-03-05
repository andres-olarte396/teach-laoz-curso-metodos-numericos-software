# Evaluación: El Método de Euler

Pon a prueba tu comprensión sobre el método más fundamental para resolver ODEs.

## Pregunta 1: Lógica del Método

¿En qué principio se basa el método de Euler para predecir el siguiente valor $y_{i+1}$?

- A) En el promedio de todas las pendientes anteriores.
- B) En suponer que la pendiente se mantiene constante durante todo el intervalo $h$.
- C) En resolver una integral exacta.
- D) En adivinar un número al azar.

## Pregunta 2: El tamaño del paso ($h$)

¿Qué sucede si el tamaño del paso $h$ es demasiado grande en una ecuación diferencial "rígida" (que cambia muy rápido)?

- A) El método se vuelve más preciso.
- B) El método puede volverse inestable y divergir (explotar al infinito).
- C) El resultado es el mismo, solo que más rápido.
- D) No afecta en nada al resultado final.

## Pregunta 3: Error de Truncamiento Local

¿Cuál es el orden de error del método de Euler?

- [Escribe tu respuesta aquí]

---

## Solucionario

1. **B** (Usa la tangente en el punto actual).
2. **B**
3. Es de **Orden 1** ($O(h)$), lo que significa que el error es proporcional al tamaño del paso.
