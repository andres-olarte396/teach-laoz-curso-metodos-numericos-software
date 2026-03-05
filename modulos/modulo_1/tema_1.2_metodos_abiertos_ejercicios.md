# Ejercicios: Métodos Abiertos (Newton y Secante)

Los métodos abiertos son los corredores de velocidad del análisis numérico. Vamos a ponerlos a prueba.

## Ejercicio 1: Newton-Raphson para Raíces Cuadradas

¿Sabías que tu calculadora usa una versión de Newton-Raphson para calcular raíces cuadradas?
Para encontrar $\sqrt{N}$, resolvemos $x^2 - N = 0$.

1. Deriva la función $f(x) = x^2 - N$.
2. Escribe la fórmula de Newton-Raphson específica para este caso.
3. Calcula $\sqrt{612}$ manualmente con 2 iteraciones empezando en $x_0 = 25$.

## Ejercicio 2: El Peligro de Diverger

Dada la función $f(x) = \arctan(x)$:

- Intenta encontrar la raíz ($x=0$) usando Newton-Raphson empezando en $x_0 = 1.4$.
- Intenta de nuevo empezando en $x_0 = 1.5$.
- ¿Qué observas? (Pista: Grafica la tangente).

## Ejercicio 3: Programación de la Secante

Implementa el Método de la Secante en Python. El programa debe recibir dos puntos iniciales y una tolerancia. Pruébalo con $f(x) = e^{-x} - x$.

---

> [!IMPORTANT]
> Los métodos abiertos son rápidos pero caprichosos. Un mal valor inicial puede llevar el algoritmo al infinito.
