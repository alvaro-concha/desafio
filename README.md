# Predictor de responsabilidad de siniestros viales

En su primera parte, el notebook "Desafío de Python.ipynb" comprende la carga, procesamiento y análisis exploratorio de datos.

Estos datos consisten de diversos atributos recolectados por una aseguradora, asociados a siniestros viales.

Luego, se implementan en el notebook varios modelos de clasificación binaria para predecir la responsabilidad de un asegurado en un siniestro.

Se llega a la conclusión de que el atributo más importante, para esta tarea, es la descripción textual del siniesto.

El modelo que se eligió para resolver la tarea es el NaiveBayesClassifier de nltk entrenado con ngrams de tamaño máximo 5, de las descripciones de los siniestros.

Finalmente, se plantean diferentes pasos a seguir antes de llevar este modelo a producción y de disponerlo para el uso por parte de un cliente.
