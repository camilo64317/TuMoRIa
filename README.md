<h1 align="center"><em> TuMoRIa </em></h1>


<h4 align="center">Autores: Daniel Eduardo Ortiz Celis - 2171469, Jefrey Steven Torres Garzón - 2190049, Camilo Eduardo González Guerrero - 2180065
</h4>


![Recurso 2@10x](https://user-images.githubusercontent.com/20091905/219105281-2affc680-3bd8-4234-9f23-ef6b66ea7006.png)

<h4> Objetivo:</h4>


Determinación del estadío de la enfermedad de Alzheimer a través de imagenología MRI: Herramienta para la detección de estadío de la enfermedad de Alzheimer a través de imagenología MRI. Se desarrolla con el fin de servir de guía o para correlación por parte del profesional de Neurología. Está enfocado para ser un problema Supervisado con fines de clasificación Multiclases(Estadíos de la Enfermedad)

<h4>  Dataset:</h4>
El link del dataset que usamos es el siguiente: https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images

Hay que aclarar que el dataset que usamos fue creado a apartir de las imagenes de la carpeta train, cargamos las imagenes y las transformamos en escala de grises, volvimos un DataFrame las imagenes, le añadimos una columna extra llamada labels que representa alguna de la etapa del Alzheimer y por ultimo permutamos el DataFrame.

<h4>  Metodos:</h4>
Gaussian Naive Bayes
Decision Tree classifier
Random Forest classifier
Support vector machine (SVM) con 3 kernesl (RBF, poly y linear)
Redes neuronales
Redes convolucionales

<h4>  Librerias</h4>
Numpy, Pandas, Sklearn, Tensorflow, Keras, Matplotlib, Seaborn y Scipy
Video:
El link del video es el siguiente: https://www.youtube.com/watch?v=SguUOUBv6LE

<h4> Codigo y repositorio:</h4>
El link del repositorio con el notebook es el siguiente: https://github.com/camilo64317/TuMoRIa/
