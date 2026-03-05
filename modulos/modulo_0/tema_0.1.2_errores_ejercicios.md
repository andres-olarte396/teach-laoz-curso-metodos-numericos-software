# Ejercicios: El Estándar IEEE 754 y la Propagación de Errores

En estos ejercicios tocaremos el "corazón" de los métodos numéricos: la imperfección de la aritmética computacional.

## Ejercicio 1: El Error de Cero Coma Uno

Ejecuta el siguiente código en tu lenguaje favorito (Python o JavaScript):

```python
# Python
print(0.1 + 0.2 == 0.3)
print(0.1 + 0.2)
```

1. ¿Cuál es el resultado?
2. Explica por qué sucede esto basándote en lo aprendido sobre el estándar IEEE 754.

## Ejercicio 2: Cálculo de Errores

Supongamos que el valor real de una constante física es **π (3.14159265...)**, pero tu software usa la aproximación **3.14**.

- Calcula el **Error Absoluto**.
- Calcula el **Error Relativo** expresado en porcentaje.

## Ejercicio 3: Precisión de Máquina

Escribe un script para encontrar el "Épsilon de la máquina" (el número más pequeño que sumado a 1.0 da un resultado diferente de 1.0).

**Pista (Python)**:

```python
epsilon = 1.0
while (1.0 + epsilon) > 1.0:
    epsilon /= 2.0
print(f"Épsilon aproximado: {epsilon * 2.0}")
```

---

> [!WARNING]
> Nunca uses herramientras de comparación directa (`==`) con números de punto flotante en sistemas críticos. Usa siempre una tolerancia (ej. `abs(a - b) < 0.0001`).
