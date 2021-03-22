# DiploDatos 2020 -  Aprendizaje Profundo

## Práctico

### Integrantes:
- Martín Brunori 
- Maximiliano Nivoli
- María de los Ángeles Martínez
- Gabriel Moyano

### Detalles de los experimentos:

En este trabajo se ha tratado un problema de clasificación multi - clase. El DataSet en cuestión cuenta con 600 clases. 
Se ha trabajado con dos redes neuronales distintas, a las cuales se fue modificando su estructura:
- Multi Layer Perceptron (MLP)
- Convolutional Neural Networ (CNN)

En una primera instancia se probó un perceptrón multicapa (MLP), donde se fueron cambiando los valores de algunos parámetros tales como: 
  - Número y tamaño de capas ocultas.
  - Funcionces de activación : se trabajó primero con una función de activación relu y luego con una función de activación celu, con el objetivo de evitar el punto de no diferenciabilidad.

Luego se continuó con una red neuronal convolucionaria (CNN), donde los parámetros a modificar fueron:
- Cantidad y tamaño de los filtros.
- Funcionces de activación : se trabajó primero con una función de activación relu y luego con una función de activación celu, con el objetivo de evitar el punto de no diferenciabilidad.

En ambos casos el tamaño del embedding se dejó en 300 ya que se utilizó un embedding preentrenado.
Otros parámetros a evaluar serían el número de épocas en ambos experimentos y el porcentaje de dropout en el modelo MLP, que no se llegaron a probar por falta de tiempo.
