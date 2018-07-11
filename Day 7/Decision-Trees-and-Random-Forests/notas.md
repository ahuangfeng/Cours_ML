Decision Tree --> para clasificación
--------------
Tiene nodos (preguntas)
Aristas (respuestas)


K-Means
--------
- D tiene n muestras
- puntos en n tienen d dimensiones
- algoritmo: A tal que cada punto existente en d retorne una una etiqueta (cluster) al que pertenece
- En verdad, se calcula la media de cada cluster y mides la cercania entre la media calculada y el punto que quieres predecir. Se predice la 'label' asociada al cluster.
- el grupo (cluster) tiene que ser redondo (o esferico en caso de n-dimensiones) 
- es totalmente de la inicializacion! si la inicializas con valores muy cercanos, los n clusters van a tener el mismo valor!

Preguntas:
- que hiperparametros necesita K-means? : cuantos clusters hay y metrica de distancia
- que diferencia hay entre KNN y Kmeans ? supervisado y no supervisado respectivamente. (tenemos el dato real o no)