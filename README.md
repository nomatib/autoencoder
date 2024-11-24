# autoencoder
Este es un autoencoder implementado desde cero en python y numpy.

El autoencoder esta basado en el perceptron multicapa y procesamiento en lotes. Utiliza una funcion de activacion personalizada basada en ReLU con dos parametros entrenables c y d. El codificador y decodificador consisten cada uno en una capa densa con 784 neuronas, la capa del vector de espacio lantente es de 100 neuronas.

El autoencoder logra en 3000 epocas un error medio de 0.0014 en un lote de 100 digitos del MNIST:
![](https://github.com/nomatib/autoencoder/blob/main/results.png)
