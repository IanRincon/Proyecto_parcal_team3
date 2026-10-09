# ¿Puede un robot aprender donde trabajar?

Proyecto de la primera parcial de la materia de Inteligencia Artificial

## Profesor

- Dr. Pedro Cesar Santana Mancilla

## Integrantes

- Francisco Javier Nava Rojas
- Ian Leonel Rincón Radillo
- José Rodolfo Ocampo Barajas

## Descripción del problema

Imaginemos que somos un estudiante buscando un lugar adecuado para tener una sesión de estudio de 30 minutos dentro del campus central de la Universidad de Colima. ¿Cómo podemos determinar si un lugar es apto o no apto?. El objetivo de este proyecto es dar respuesta a esta pregunta utilizando machine learning. En el programa realizado se realizan 3 algoritmos para determinar la respuesta:

- KNN (propio)
- KNN (de la librería scikit learn)
- Random Forest (de la librería scikit learn)

En el programa se evaluaran las métricas de cada modelo, para comparar el rendimiento de cada uno.

## Instrucciones de uso

Debido a que el programa se trata de un archivo de Jupyter Notebook, la recomendación es que este se ejecute en el entorno de Google Colab.

### Preparación del entorno

Los modelos entrenados en este proyecto, utilizan el dataset:

- Dataset v1.0

el cual se encuentra disponible dentro de este repositorio. Este dataset se debe subir al entorno de Google Colab una vez abierto el archivo models_testing.ipynb.

### Ejecución del modelo KNN propio

La celda donde se encuentra KNN_Classifier contiene el modelo propio, en la siguiente se hace el split de datos con proporción 80/20 y el ciclo de entrenamientos de k=1,3,5,7,9. Dentro de la misma celda se colocan comandos para obtener un resumen de las métricas y las matrices de confusión de cada caso.

### Ejecución del modelo KNN de scikit-learn

La siguiente celda aplica el mismo proceso anterior, pero en lugar de usar el algoritmo propio, llama al que viene integrado en la librería de scikit-learn. También arroja el mismo resumen de las métricas.

### Ejecuación del modelo de Random Forest

En el último conjunto de celdas, se entrena y evalua Random Forest







