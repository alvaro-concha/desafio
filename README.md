# Predictor de responsabilidad de siniestros viales

En su primera parte, el notebook "Desafío de Python.ipynb" comprende la carga, procesamiento y análisis exploratorio de datos.

Estos datos consisten de diversos atributos recolectados por una aseguradora, asociados a siniestros viales.

Luego, se implementa, en el notebook, un modelo Gradient Boosting Classifier binaria para predecir la responsabilidad de un asegurado en un siniestro.

Este modelo utiliza como inputs, además de los atributos anteriores, a los scores de un Naive Bayes Classifier entrenado sobre un cuerpo de texto con las descripciones de los siniestros.

Finalmente, se plantean diferentes maneras de disponer este modelo frente a un cliente.
