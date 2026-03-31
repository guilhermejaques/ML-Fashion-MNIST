📌 **Objetivo**: 
Classificar cada imagem em uma entre 10 categorias de roupas.

---

**Sobre o Conjunto de Dados**: `Fashion MNIST` É um conjunto de imagens de roupas em escala de cinza, onde cada registro representa uma imagem com rótulo e pixels.

*   Total: 70.000 Imagens
*   Dimensão: 28x28 Pixels
*   1 Canal de Cor (Grayscale)
*   10 Classes / Rótulos 

**Créditos e Download do Dataset**: 
* [TensorFlow](https://www.tensorflow.org/datasets/catalog/fashion_mnist?hl=pt-br)
* [Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist)
  
`import tensorflow as tf`
`(x_train, y_train), (x_test, y_test) = tf.keras.datasets.fashion_mnist.load_data()`

**Linguagem e bibliotecas**:

* Python, Jupyter Notebook, TensorFlow, Keras, Pandas, Numpy, Matplotlib, Seaborn

**Para visualizar o documento**: clique na pasta `Projeto` e `modeloML.ipynb`

---
