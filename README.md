Proyecto Análisis y Métodos Numéricos

Este proyecto se enfoca en la implementación y aplicación del Método de Newton-Raphson para la resolución de ecuaciones de una variable en el contexto del análisis numérico. A través de este algoritmo, se busca encontrar soluciones o raíces de ecuaciones no lineales de manera eficiente y precisa.
Integrantes del Proyecto

    Johan Steven Muñoz Lopez - 1958380

Método Newton-Raphson

El Método de Newton-Raphson es un algoritmo iterativo utilizado para encontrar soluciones de ecuaciones no lineales. La idea principal es aproximar la raíz de una función mediante sucesivas iteraciones basadas en el cálculo de la tangente a la curva en el punto actual. Este método requiere la evaluación de la función y su derivada, lo que lo hace eficiente pero sensible a la elección del punto inicial y a la existencia de múltiples raíces.
Funcionalidades Implementadas

El proyecto incluye las siguientes funcionalidades:

    Cálculo de la Derivada: Se proporciona una función para calcular la derivada de una función dada utilizando la biblioteca SymPy.

    Método Gráfico: Se ofrece una función para graficar una función dada en un intervalo específico. Esta funcionalidad proporciona una manera visual de identificar las raíces de la función, aunque puede ser menos precisa que otros métodos numéricos.

    Algoritmo Newton-Raphson: Se implementa el Método de Newton-Raphson para encontrar soluciones numéricas de ecuaciones no lineales. El algoritmo toma como entrada la función, su derivada, un punto inicial, y criterios de parada como el error máximo permitido y el número máximo de iteraciones.

Instrucciones de Uso

Para utilizar este proyecto:

    Clona el repositorio en tu máquina local.
    Instala las dependencias necesarias (SymPy, Matplotlib, NumPy, etc.).
    Ejecuta el script principal o los scripts de ejemplo según tus necesidades.
    Observa los resultados obtenidos y ajusta los parámetros según sea necesario.
