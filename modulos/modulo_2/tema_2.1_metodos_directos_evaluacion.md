# Evaluación: Sistemas Lineales - Métodos Directos

Domina la resolución exacta de sistemas de ecuaciones mediante algoritmos matriciales.

## Pregunta 1: Eliminación Gaussiana y Pivoteo

¿Por qué es recomendable realizar "pivoteo parcial" (intercambiar filas) durante la eliminación gaussiana?

- A) Para que la matriz se vea más ordenada.
- B) Para evitar divisiones por cero o por números muy pequeños que generen grandes errores de redondeo.
- C) Porque el estándar IEEE 754 lo exige legalmente.
- D) Para reducir el número de multiplicaciones necesarias.

## Pregunta 2: Matrices Triangulares

¿Cuál es la ventaja de tener una matriz en forma triangular superior ($U$)?

- A) Que su determinante es siempre 1.
- B) Que se puede resolver fácilmente mediante "Sustitución hacia Atrás".
- C) Que no consume memoria RAM.
- D) Que es inmune a los errores de punto flotante.

## Pregunta 3: Descomposición LU

Si ya conocemos la descomposición $A = LU$, ¿cuántos sistemas triangulares debemos resolver para encontrar $x$ en $Ax = B$?

- [Escribe tu respuesta aquí]

---

## Solucionario

1. **B**
2. **B**
3. **Dos** ($Ly = B$ y luego $Ux = y$).
