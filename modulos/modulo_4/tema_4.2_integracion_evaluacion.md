# Evaluación: Cálculo Infinitesimal Computacional

Valida tu comprensión sobre la integración y derivación en entornos digitales.

## Pregunta 1: Regla de Simpson 1/3

¿Cuál es la restricción principal para aplicar la regla de Simpson 1/3 en integración numérica?

- A) La función debe ser un polinomio.
- B) El número de intervalos ($n$) debe ser par.
- C) El número de puntos debe ser impar.
- D) Las opciones B y C son equivalentes y correctas.

## Pregunta 2: El Dilema del Paso ($h$)

Si al calcular una derivada numérica reduces $h$ infinitamente, ¿qué sucede con el error total?

- A) El error disminuye hasta llegar a cero.
- B) El error disminuye inicialmente, pero luego aumenta debido al error de redondeo computacional.
- C) El error se mantiene constante.
- D) El software se bloquea por división por cero.

## Pregunta 3: Aplicación Real

Necesitas calcular la distancia recorrida por un robot sumando las velocidades medidas por sus sensores cada 0.1 segundos. ¿Qué método de integración elegirías para obtener mayor precisión si tienes un número par de lecturas? Justifica.

---

## Solucionario

1. **D** (Si $n$ es par, hay $n+1$ puntos, lo cual es impar).
2. **B**
3. **Regla de Simpson 1/3**. Es superior al Trapecio porque utiliza aproximaciones parabólicas en lugar de líneas rectas, lo que captura mucho mejor los cambios de velocidad.
