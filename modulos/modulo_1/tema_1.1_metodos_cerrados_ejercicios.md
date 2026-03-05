# Ejercicios: Métodos Cerrados (Bisección y Falsa Posición)

Pon a prueba tu lógica implementando y analizando la convergencia de estos métodos.

## Ejercicio 1: Seguimiento Manual de Bisección

Dada la función $f(x) = x^2 - 3$:

1. Verifica si hay una raíz en el intervalo [1, 2].
2. Realiza 3 iteraciones del método de bisección manualmente. Anota el valor de cada punto medio m y el error aproximado.

## Ejercicio 2: Implementación de Tolerancia

Modifica el código de bisección proporcionado en la teoría para que se detenga no por número de iteraciones, sino cuando el **Error Relativo Porcentual** sea menor al **0.01%**.

## Ejercicio 3: Bisección vs Falsa Posición

Usando la función $f(x) = \ln(x) + x - 5$ en el intervalo $[3, 4]$:

- Implementa ambos métodos en Python.
- Cuenta cuántas iteraciones requiere cada uno para alcanzar una tolerancia de $10^{-6}$.
- ¿Cuál fue más eficiente? Explica por qué.

---

> [!NOTE]
> Recuerda que para que la bisección funcione, $f(a)$ y $f(b)$ deben tener signos opuestos. Si no, ¡estarás buscando una raíz donde no la hay!
