# labdeeplearning

En este trabajo se ha tratado un problema de clasificación multi - clase. El DataSet en cuestión cuenta con 600 clases. 
Se ha trabajado con dos de redes neuronales distintas, a las cuales se fue modificando su estructura:
- Multi Layer Perceptron (MLP)
- Convolutional NN (CNN)

En una primera instancia se probó un perceptrón multicapa (MLP), donde se fueron cambiando los valores de algunos parámetros tales como: 
  - Número y tamaño de capas ocultas.
  - Porcentaje de dropout.
  - Funcionces de activación : se trabajó primero con una función de activación relu y luego ...

Luego se continuó con la CNN, donde los parámetros a modificar fueron:
- Cantidad y tamaño de los filtros.
- Función de activación

En ambos casos el tamaño del embedding se dejó en 300 ya que se utilizó un embedding preentrenado. Y el número de épocas también varió para ambos casos.
