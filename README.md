# Proyecto de Cálculo de Probabilidades y Propiedades en Sistemas Cuánticos
Este proyecto contiene varias funciones realizadas en Python diseñadas para realizar cálculos de probabilidades y propiedades en sistemas cuánticos, 
tales como la probabilidad de encontrar un sistema en una posición específica, 
la probabilidad de transición entre dos estados, y la verificación de propiedades matemáticas como la hermiticidad y unitariedad de matrices.

## Este taller tiene lo siguiente:
1. Descripción del Proyecto
2. Requisitos
3. Ejemplos de Uso

## Descripción del Proyecto
Este proyecto está enfocado en la implementación de funciones para cálculos cuánticos usando Python y las librerías numpy y math. Las funciones incluyen:

Cálculo de la probabilidad de encontrar una partícula en una posición específica dentro de un vector de estados.
Cálculo de la probabilidad de transición entre dos vectores de estado.
Verificación de si una matriz es hermitiana.
Normalización de vectores.
Cálculo de productos internos y productos de matrices por vectores.
Cálculo del valor medio y la varianza de un observable.
Determinación de valores y vectores propios de una matriz.
Verificación de la unitariedad de matrices y productos de matrices.

## Requisitos
Para ejecutar este código, necesitas tener instalados los siguientes paquetes de Python:
- numpy
- math

## Ejemplos de uso
from my_module import *

# Ejemplo de probabilidad de posición
print(probabilidad_posicion([2 + 1j, -1 + 2j, 1j, 1, 3 - 1j, 2, -2j, -2 + 1j, 1 - 3j, -1j], 9))

# Ejemplo de probabilidad de transición
print(probabilidad_transicion([1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 1, 0, 0, 0]))

# Ejemplo de verificación de hermiticidad
print(es_hermitiana([[1, 1], [1, -1]]))

# Ejemplo de cálculo de valor medio
print(valor_medio([[1, -1j], [1j, 2]], [math.sqrt(2) / 2, (math.sqrt(2) / 2 * 1j)]))



  
