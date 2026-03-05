# Ejercicios: Diferenciación Numérica

Aprende a calcular cambios instantáneos en sistemas discretos.

## Ejercicio 1: Comparativa de Exactitud

Dada $f(x) = e^x$ en $x=1$:

1. Calcula la derivada real $f'(1)$.
2. Calcula la derivada usando **Diferencia Hacia Adelante** con $h=0.1$.
3. Calcula la derivada usando **Diferencia Centrada** con $h=0.1$.
4. ¿Cuál tuvo menor error relativo?

## Ejercicio 2: El Efecto de $h$ en Software

Escribe un script que calcule la derivada de $f(x) = \sin(x)$ en $x=0$ para diferentes valores de $h$: $[10^{-1}, 10^{-5}, 10^{-10}, 10^{-16}]$.

- ¿Qué sucede cuando $h$ es extremadamente pequeño (como $10^{-16}$)?
- Explica el resultado basándote en la aritmética de punto flotante.

## Ejercicio 3: Segunda Derivada

Deriva la fórmula de la **segunda derivada** usando diferencias finitas centradas partiendo de la serie de Taylor. El resultado debería ser:
$$f''(x) \approx \frac{f(x+h) - 2f(x) + f(x-h)}{h^2}$$

---

> [!IMPORTANT]
> En la práctica, la Diferencia Centrada es casi siempre la mejor opción por su balance entre simplicidad y precisión.
