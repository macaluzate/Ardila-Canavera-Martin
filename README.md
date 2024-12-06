# Proyecto del Método de las Potencias

## Descripción
Este proyecto implementa el método de las potencias para encontrar el eigenvalor dominante y su correspondiente eigenvector de una matriz diagonalizable cuadrada. Es una herramienta útil en álgebra lineal para estudiar matrices y sus propiedades espectrales.

## Pre-requisitos
Para ejecutar este proyecto, necesitarás Python y algunas bibliotecas específicas. Asegúrate de tener instalado Python 3.8 o superior.

## Dependencias
Este código depende de la biblioteca `numpy`. Puedes instalar esta biblioteca usando pip:

```bash
pip install numpy
```

## Uso
Para usar el código, abre el Jupyter Notebook Método_de_las_potencias.ipynb y ejecuta las celdas. Aquí tienes una guía rápida para usar la función principal:

## Función largeeig_recursive(A, x0, tol, maxiter)
**Parámetros:**
- A: Matriz cuadrada numpy array. Debe ser diagonalizable.
- x0: Vector inicial numpy array. No debe ser el vector cero.
- tol: Tolerancia para el criterio de parada (tipo float).
- maxiter: Número máximo de iteraciones (tipo int).

**Retorno:**
- lambda_val: Eigenvalor dominante encontrado.
- x_next: Eigenvector correspondiente al eigenvalor dominante.
- k: Número de iteraciones realizadas.

**Ejemplo de uso:**
```python
import numpy as np

# Define la matriz y el vector inicial
A = np.array([[2, 1], [1, 3]], dtype=float)
x0 = np.array([1, 1], dtype=float)

# Llama a la función
eigenvalue, eigenvector, iterations = largest_eigenvalue(A, x0, 1e-8, 100)

print("Eigenvalor dominante:", eigenvalue)
print("Eigenvector correspondiente:", eigenvector)
print("Iteraciones realizadas:", iterations)
```

