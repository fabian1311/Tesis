Conjunto de algoritmos de aprendizaje supervisado <br>
Dado un conjunto de puntos, subconjunto de un conjunto mayor (espacio), en el que cada uno de ellos pertenece a una de dos posibles categorías, un algoritmo basado en SVM construye un modelo capaz de predecir si un punto nuevo (cuya categoría desconocemos) pertenece a una categoría o a la otra.

Como en la mayoría de los métodos de clasificación supervisada, los datos de entrada (los puntos) son vistos como un vector _p_-dimensional (una [lista ordenada](https://es.wikipedia.org/wiki/Tupla "Tupla") de _p_ [números](https://es.wikipedia.org/wiki/N%C3%BAmero_real "Número real")).

La SVM busca un hiperplano que separe de forma óptima a los puntos de una clase de la de otra, que eventualmente han podido ser previamente proyectados a un espacio de dimensionalidad superior.

En ese concepto de "separación óptima" es donde reside la característica fundamental de las SVM: este tipo de algoritmos buscan el hiperplano que tenga la máxima distancia (margen) con los puntos que estén más cerca de él mismo. Por eso también a veces se les conoce a las SVM como _clasificadores de margen máximo_. De esta forma, los puntos del vector que son etiquetados con una categoría estarán a un lado del hiperplano y los casos que se encuentren en la otra categoría estarán al otro lado.

Los algoritmos SVM pertenecen a la familia de los [clasificadores lineales](https://es.wikipedia.org/wiki/Clasificador_lineal "Clasificador lineal"). También pueden ser considerados un caso especial de la [regularización de Tikhonov](https://es.wikipedia.org/wiki/Regularizaci%C3%B3n_de_T%C3%ADjonov "Regularización de Tíjonov").

En la literatura de las SVM, se llama _atributo_ a la variable predictora y _característica_ a un atributo transformado que es usado para definir el hiperplano. La elección de la representación más adecuada del universo estudiado, se realiza mediante un proceso denominado selección de características.

Al vector formado por los puntos más cercanos al hiperplano se le llama vector de soporte.

Los modelos basados en SVM están estrechamente relacionados con las redes neuronales. Usando una función kernel, resultan un método de entrenamiento alternativo para clasificadores polinomiales, [funciones de base radial](https://es.wikipedia.org/wiki/Funci%C3%B3n_de_base_radial "Función de base radial") y [perceptrón](https://es.wikipedia.org/wiki/Perceptr%C3%B3n "Perceptrón") multicapa.