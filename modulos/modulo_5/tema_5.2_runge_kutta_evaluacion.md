# Evaluación: Modelado de Sistemas Dinámicos

Demuestra que sabes cómo simular el tiempo mediante software.

## Pregunta 1: Orden de Convergencia

¿Qué significa que Runge-Kutta de 4to Orden (RK4) sea de "cuarto orden"?

- A) Que requiere 4 computadoras para funcionar.
- B) Que el error disminuye con la cuarta potencia del paso de tiempo ($h^4$).
- C) Que solo sirve para polinomios de grado 4.
- D) Que se inventó en el cuarto mes del año.

## Pregunta 2: Estabilidad Numérica

Si estás programando una simulación de alta fidelidad para un cohete espacial, ¿por qué rechazarías el método de Euler en favor de RK4?

- A) Porque Euler es más lento.
- B) Porque Euler acumula error de truncamiento linealmente, lo que desviaría el cohete de su curso rápidamente.
- C) Porque RK4 no necesita paso de tiempo.
- D) Porque Euler solo funciona en 2D.

## Pregunta 3: Análisis de Pseudocódigo

En la implementación de RK4, calculamos 4 pendientes ($k1, k2, k3, k4$). ¿Cuál es el peso que tiene $k2$ y $k3$ en el promedio final en comparación con $k1$ y $k4$?

- [Escribe tu respuesta aquí]

---

## Solucionario

1. **B**
2. **B**
3. Tienen el **doble de peso** ($k2$ y $k3$ se multiplican por 2 en la fórmula). Esto es porque representan estimaciones en el punto medio del intervalo, que suelen ser más representativas de la trayectoria real.
