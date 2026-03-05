# Ejercicios: Introducción a ODEs y Método de Euler

Comienza a simular sistemas dinámicos que evolucionan en el tiempo.

## Ejercicio 1: Simulación Manual de Enfriamiento

La ley de enfriamiento de Newton dice que $\frac{dy}{dt} = -0.1(y - 20)$, donde $y$ es la temperatura y $20$ la ambiente.

- Si la temperatura inicial es $y_0 = 80$, usa el **Método de Euler** con $h=2$ (minutos) para encontrar la temperatura a los 4 minutos (2 pasos).

## Ejercicio 2: El Peligro del Salto Grande

Usa la función $dy/dt = -10y$ con $y_0 = 1$.

1. Intenta resolverla con Euler usando $h=0.5$. ¿Qué sucede con los valores de $y$ en los primeros pasos?
2. Intenta de nuevo con $h=0.01$.
3. Explica qué significa que un método sea "inestable" basándote en este ejemplo.

## Ejercicio 3: Implementación en Python

Escribe un programa que use Euler para simular la caída libre de un objeto (sin aire por ahora):

- $dv/dt = -9.81$
- $dy/dt = v$
  (Este es un sistema de dos ecuaciones).

---

> [!NOTE]
> Euler es genial para entender la lógica, pero en el mundo real, los errores se acumulan como una bola de nieve.
