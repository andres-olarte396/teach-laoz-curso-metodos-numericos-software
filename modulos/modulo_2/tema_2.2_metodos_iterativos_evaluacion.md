# Evaluación: Álgebra Lineal Computacional

Pon a prueba tu criterio para seleccionar el algoritmo de resolución más eficiente.

## Pregunta 1: Eficiencia de LU

¿En qué escenario es más eficiente utilizar la Descomposición LU sobre la Eliminación Gaussiana tradicional?

- A) Cuando la matriz es de gran tamaño y tiene muchos ceros.
- B) Cuando se debe resolver el mismo sistema $Ax = B$ para muchos vectores $B$ diferentes.
- C) Cuando la matriz es singular.
- D) Cuando se requiere una solución aproximada en lugar de exacta.

## Pregunta 2: Convergencia Iterativa

¿Cuál es el requisito principal para asegurar que los métodos de Jacobi o Gauss-Seidel converjan a la solución?

- A) La matriz debe ser simétrica.
- B) La matriz debe ser diagonalmente dominante.
- C) El determinante debe ser exactamente 1.
- D) No hay requisitos, siempre convergen.

## Pregunta 3: Análisis de Memoria

Si tienes un sistema de un millón de ecuaciones con una matriz donde cada fila solo tiene 3 elementos distintos de cero (matriz dispersa), ¿qué enfoque elegirías y por qué?

---

## Solucionario

1. **B**
2. **B**
3. **Métodos Iterativos** (como Gauss-Seidel o Gradiente Conjugado). Los métodos directos intentarían llenar los ceros ("fill-in"), agotando la memoria RAM rápidamente.
