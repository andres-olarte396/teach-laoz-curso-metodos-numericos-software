# Ejercicios: Métodos Directos (Gauss y LU)

Aprende a resolver sistemas de ecuaciones como lo hacen los motores de simulación.

## Ejercicio 1: Eliminación Gaussiana Manual

Resuelve el siguiente sistema $3 \times 3$ usando eliminación gaussiana paso a paso:
$$2x + y - z = 8$$
$$-3x - y + 2z = -11$$
$$-2x + y + 2z = -3$$

## Ejercicio 2: El Poder de la Descomposición LU

Dada la matriz $A = \begin{bmatrix} 4 & 3 \\ 6 & 3 \end{bmatrix}$:

1. Encuentra las matrices $L$ (triangular inferior) y $U$ (triangular superior) tales que $A = LU$.
2. Resuelve el sistema $Ax = [7, 9]^T$ usando sustitución hacia adelante y hacia atrás con las matrices $L$ y $U$.

## Ejercicio 3: Detectando Matrices Singulares

Escribe un programa que reciba una matriz $A$ y determine si puede resolverse mediante métodos directos (calculando el determinante o verificando si tiene filas linealmente dependientes).

---

> [!TIP]
> En Python, `numpy.linalg.det(A)` te dirá si la matriz es singular (determinante = 0), en cuyo caso el sistema no tiene solución única.
