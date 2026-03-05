# Ejercicios: Métodos Iterativos (Jacobi y Gauss-Seidel)

Optimiza la resolución de sistemas masivos mediante iteración.

## Ejercicio 1: Iteración de Jacobi paso a paso

Para el sistema:
$$5x - y = 9$$
$$x + 6y = 8$$

1. Despeja $x$ e $y$ para el método de Jacobi.
2. Realiza 2 iteraciones empezando con $x_0 = 0, y_0 = 0$.

## Ejercicio 2: El Acelerador de Gauss-Seidel

Repite el ejercicio anterior pero usando **Gauss-Seidel**.

- ¿Qué valor de $x$ e $y$ obtienes después de la primera iteración?
- Compara con los resultados de Jacobi. ¿Cuál está más cerca de la solución real (2, 1)?

## Ejercicio 3: Implementación con Criterio de Parada

Elabora un script donde implementes Gauss-Seidel y que termine cuando la **Norma Infinita** del error entre iteraciones sea menor a $10^{-4}$.

---

> [!NOTE]
> La **Norma Infinita** simplemente es el valor máximo de la diferencia entre el vector nuevo y el viejo. `max(abs(x_nuevo - x_viejo))`.
