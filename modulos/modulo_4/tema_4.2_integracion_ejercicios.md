# Ejercicios: Integración Numérica (Trapecio y Simpson)

Convierte funciones complejas en áreas simples y calculables.

## Ejercicio 1: El Área del Círculo

Aproxima el valor de $\pi$ integrando la función $f(x) = \sqrt{1 - x^2}$ desde $0$ hasta $1$ (esto te dará $\pi/4$).

1. Usa la **Regla del Trapecio** con $n=4$ intervalos.
2. Multiplica el resultado por 4 y compara con el valor real de $\pi$.

## Ejercicio 2: Simpson contra la Curva

Usa la **Regla de Simpson 1/3** con $n=4$ para integrar la misma función del ejercicio 1 ($f(x) = \sqrt{1 - x^2}$ de $0$ a $1$).

- ¿El error fue menor que con el Trapecio?

## Ejercicio 3: Integración de Datos Tabulados

En el mundo real, a veces no tienes la fórmula, solo una tabla:

| x    | 0   | 0.5 | 1.0 | 1.5 | 2.0 |
| ---- | --- | --- | --- | --- | --- |
| f(x) | 1.0 | 0.8 | 0.5 | 0.2 | 0.1 |

Calcula la integral desde 0 hasta 2 usando los datos de la tabla (Pista: elige el método que prefieras, pero justifica por qué).

---

> [!TIP]
> Simpson 3/8 es tu mejor amigo cuando tienes una cantidad de intervalos múltiplo de 3 (como 3, 6, 9...).
