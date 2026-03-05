# Ejercicios: Método de Runge-Kutta 4 (RK4)

Implementa el estándar de la industria en simulaciones de precisión.

## Ejercicio 1: RK4 Manual (Un solo paso)

Para la ODE $dy/dt = y - t^2 + 1$ con $y_0 = 0.5$:

- Calcula $k1, k2, k3$ y $k4$ para dar un solo paso de tamaño $h=0.2$.
- ¿Cuál es el valor aproximado de $y(0.2)$?

## Ejercicio 2: El Simulador de Órbitas

Escribe un script en Python que use RK4 para simular un oscilador armónico simple (un resorte):

- $\frac{d^2x}{dt^2} = -x \implies$ Sistema: $v' = -x$ y $x' = v$.
- Compara el resultado con el método de Euler. ¿Cuál mantiene mejor la amplitud de la oscilación con el tiempo?

## Ejercicio 3: Estabilidad con Pasos Grandes

Prueba tu simulador RK4 con un paso de tiempo "agresivo" ($h=0.5$).

- ¿Sigue siendo estable en comparación con Euler usando el mismo paso?
- Grafica ambos resultados.

---

> [!TIP]
> RK4 es el "caballo de batalla" de la física computacional. Domínalo y podrás programar casi cualquier simulación física realista.
