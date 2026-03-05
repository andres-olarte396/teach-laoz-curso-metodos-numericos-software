# Evaluación: Búsqueda de Raíces en Ingeniería de Software

Demuestra tu dominio sobre los algoritmos iterativos de búsqueda de raíces.

## Pregunta 1: Convergencia de Newton-Raphson

¿Qué sucede con el método de Newton-Raphson si el punto inicial $x_0$ se elige de tal manera que $f'(x_0) = 0$?

- A) El método converge instantáneamente.
- B) El método entra en un bucle infinito.
- C) El método falla por división por cero.
- D) El método cambia automáticamente a bisección.

## Pregunta 2: Elección del Método

Tienes una función continua pero cuya derivada es extremadamente difícil de calcular computacionalmente. ¿Cuál de estos métodos es el más apropiado?

- A) Newton-Raphson.
- B) Método de la Secante.
- C) Diferenciación simbólica.
- D) Regla de Simpson.

## Pregunta 3: Caso Práctico

Deseas encontrar el punto de equilibrio donde los ingresos igualan a los costos en un modelo financiero $f(x) = x^3 - 5x + 2$. Si sabes que la solución está cerca de $x=2$, ¿qué método elegirías para obtener la respuesta con 10 decimales en el menor tiempo posible? Justifica brevemente.

---

## Solucionario

1. **C**
2. **B** (Porque la Secante aproxima la derivada sin necesitar la fórmula analítica).
3. **Newton-Raphson**. Debido a su convergencia cuadrática, es el más rápido una vez que estamos cerca de la raíz (como en este caso $x \approx 2$).
