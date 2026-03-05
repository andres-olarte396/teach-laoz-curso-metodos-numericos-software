# Evaluación: Fundamentos de Interpolación

Valida tu capacidad para construir polinomios que pasen exactamente por puntos dados.

## Pregunta 1: Grado del Polinomio

Si tienes 5 puntos de datos distintos, ¿cuál es el grado del polinomio único que pasa exactamente por todos ellos?

- A) Grado 5
- B) Grado 4
- C) Grado 6
- D) Depende de los valores de Y.

## Pregunta 2: Polinomio de Lagrange

¿Cuál es una característica de la base de polinomios de Lagrange $L_i(x)$?

- A) Todos valen 1 en x=0.
- B) El polinomio $L_i(x)$ vale 1 en el nodo $x_i$ y valen 0 en todos los demás nodos $x_j$.
- C) Son siempre líneas rectas.
- D) No se pueden programar en Python.

## Pregunta 3: Newton vs Lagrange

¿Qué sucede con el cálculo si decides añadir un sexto punto de datos a un conjunto de 5?

- [Compara brevemente el esfuerzo en Newton vs Lagrange]

---

## Solucionario

1. **B** (n-1 grados para n puntos).
2. **B**
3. En **Newton**, solo se añade un término nuevo a la tabla de diferencias. En **Lagrange**, hay que recalcular todos los polinomios base desde cero. Newton es más eficiente para datos dinámicos.
