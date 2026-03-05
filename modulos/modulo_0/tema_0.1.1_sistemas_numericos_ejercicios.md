# Ejercicios: Sistemas Numéricos y Representación

Este conjunto de ejercicios te ayudará a dominar la base de cómo la computadora entiende los números antes de aplicar métodos numéricos.

## Ejercicio 1: Conversión Manual a Binario

Convierte los siguientes números decimales a binario (8 bits):

1. 5
2. 13
3. 42
4. 128

_Consejo: Divide sucesivamente por 2 y anota los residuos de abajo hacia arriba._

## Ejercicio 2: El Desafío del Hexadecimal

Convierte estos números binarios a hexadecimal. Recuerda agrupar de 4 en 4 bits (Nibles):

1. 1100 1010
2. 1111 1111
3. 0000 1001

## Ejercicio 3: Implementación de Código (Python/JS)

Escribe un pequeño script que haga lo siguiente:

- Solicite un número decimal al usuario.
- Imprima su representación en Binario y Hexadecimal usando funciones nativas del lenguaje.

**Ejemplo esperado (Python)**:

```python
numero = 255
print(f"Binario: {bin(numero)}")
print(f"Hex: {hex(numero)}")
```

---

> [!TIP]
> En métodos numéricos, entender el hexadecimal es clave para depurar cómo se guardan los datos en la memoria "cruda" de la computadora.
