# Ejercicios: Interpolación Polinómica

Aprende a predecir datos intermedios con precisión matemática.

## Ejercicio 1: Polinomio de Lagrange

Dados los puntos $(0, 1), (1, 3), (2, 0)$:

1. Encuentra el polinomio de interpolación de Lagrange $P_2(x)$.
2. Evalúa $P_2(0.5)$.

## Ejercicio 2: Diferencias Divididas de Newton

Utiliza la misma tabla de puntos del ejercicio 1 para:

1. Construir la tabla de diferencias divididas.
2. Formar el polinomio de Newton.
3. Verifica que el resultado en $x=0.5$ sea idéntico al de Lagrange.

## Ejercicio 3: Script de Interpolación Flexible

Crea un programa que reciba una lista de coordenadas $X$ e $Y$ de cualquier longitud y utilice el método de Lagrange para estimar el valor en un punto $X_{target}$ dado por el usuario.

---

> [!CAUTION]
> Recuerda el **Fenómeno de Runge**: no intentes interpolar 20 puntos con un solo polinomio de grado 19, o verás oscilaciones absurdas en los extremos.
