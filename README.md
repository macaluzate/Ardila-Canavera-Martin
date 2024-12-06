# Tarea 1

**Ardila Otero, María Paula**  
**Cañavera Aluma, Mateo**  
**Martin Acosta, David Esteban**  


---

**3006886: Análisis Numérico**  
**Departamento de Matemáticas**  
**Universidad Nacional de Colombia**

---

**Diciembre 6, 2024**

# Nota Importante Sobre el Notebook 'Teoría'
Debido al gran tamaño del notebook `Teoría`, su previsualización en GitHub puede no ser posible. Recomendamos descargar el documento directamente para poder visualizarlo y trabajar con él sin inconvenientes. Esto asegurará que puedas acceder a todo el contenido y funcionalidad del notebook sin problemas de carga.


# Tabla de contenidos:
- [Proyecto del Método de las Potencias](#proyecto-del-método-de-las-potencias)
  - [Descripción](#descripción)
  - [Pre-requisitos](#pre-requisitos)
  - [Dependencias](#dependencias)
- - [Proyecto del Método de Descomposición QR](#proyecto-del-método-de-la-descomposición-QR)
  - [Descripción](#descripción)
  - [Pre-requisitos](#pre-requisitos)
  - [Dependencias](#dependencias)
- 

# Proyecto del Método del Polinomio Característico

## Descripción
Este proyecto implementa el cálculo de eigenvalores y eigenvectores de una matriz cuadrada utilizando el método del polinomio característico. A través de este enfoque, primero se calcula el polinomio característico de la matriz mediante la construcción simbólica de \((A - \lambda I)\) y la determinación de su determinante. Posteriormente, se resuelven las raíces del polinomio para obtener los eigenvalores y, finalmente, se calculan los eigenvectores resolviendo el sistema homogéneo asociado \((A - \lambda I)v = 0\). Este método es especialmente útil para matrices pequeñas o medianas y proporciona una visión simbólica clara del proceso de cálculo de eigenvalores y eigenvectores.

## Pre-requisitos
Para ejecutar este proyecto, necesitarás Python y algunas bibliotecas específicas. Asegúrate de tener instalado Python 3.8 o superior.


## Dependencias

Este código depende de las siguientes bibliotecas:

- `numpy`: Para el manejo eficiente de matrices y operaciones numéricas.
- `sympy`: Para el manejo simbólico de matrices, cálculo del determinante y resolución de polinomios.

Puedes instalar ambas bibliotecas usando pip:

```bash
pip install numpy sympy


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

# proyecto del método de la descomposición QR

## Descripción
Este proyecto utiliza el método de descomposición QR de forma iterativa para calcular los eigenvalores y eigenvectores de una matriz. A través de este proceso, la matriz es descompuesta repetidamente en una matriz ortogonal (Q) y una matriz triangular (R). La iteración continua permite aproximarse progresivamente a los eigenvalores, y dependiendo del tipo de matriz, la precisión de las aproximaciones puede variar. Este enfoque iterativo ofrece una forma eficiente de obtener los eigenvalores y eigenvectores con un grado de exactitud que se ajusta al comportamiento y la naturaleza de la matriz en cuestión.

## Pre-requisitos
Para ejecutar este proyecto, necesitarás Python y algunas bibliotecas específicas. Asegúrate de tener instalado Python 3.8 o superior.


## Dependencias

Este código depende de las siguientes bibliotecas:

- `numpy`: Para el manejo eficiente de matrices y operaciones numéricas.
- `sympy`: Para el manejo simbólico de matrices y la simplificación de expresiones algebraicas.

Puedes instalar ambas bibliotecas usando pip:

```bash
pip install numpy sympy
```


