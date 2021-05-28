# Introduction to  RNN & CNN 
 RNN & CNN classification on MNIST dataset with tensorflow v1
 
 Getting started with Tensorflow V1 : https://www.tensorflow.org/api_docs/python/tf/compat/v1
 
 Getting started with CNN : https://radiant-brushlands-42789.herokuapp.com/medium.com/data-science-group-iitr/building-a-convolutional-neural-network-in-python-with-tensorflow-d251c3ca8117
 
 Getting started with RNN :https://medium.com/@erikhallstrm/hello-world-rnn-83cd7105b767
 
 Might like regression with tensorflow : https://radiant-brushlands-42789.herokuapp.com/sniafas.medium.com/regression-in-tensorflow-v1-v2-e8d7e80068b
__________________________________________________________________________________

## Dataset Description
Fashion MNIST Dataset. You can load the dataset from tf.keras directly as shown in the following tutorial: https://www.tensorflow.org/tutorials/keras/classification with the following code:
```
fashion_mnist = tf.keras.datasets.fashion_mnist
(train_data, train_labels), (test_data, test_labels) =fashion_mnist.load_data()
```
The images are 28x28 NumPy arrays, with pixel values ranging from 0 to 255.

Class Labels: Each training and test example is assigned to one of the following labels:

0 T-shirt/top
1 Trouser
2 Pullover
3 Dress
4 Coat
5 Sandal
6 Shirt
7 Sneaker
8 Bag
9 Ankle boot
### Task 1 :

Create a recurrent neural network with a tensorflow.compat.v1.nn.rnn_cell.RNNCell as a basic component. Use tensorflow.compat.v1.nn.static_rnn to create the RNN. Train it end to end.

### Task 2 :

Create a 2D convolutional neural network using tensorflow.compat.v1.layers.conv2d as a basic component. Training it end to end.

![alt text](https://github.com/rvravi77/RNN-Acc89-----CNN-Acc-91----TFv1/blob/main/IMG/RNN1.png?raw=true)

![alt text](https://github.com/rvravi77/RNN-Acc89-----CNN-Acc-91----TFv1/blob/main/IMG/RNN2.png?raw=true)

![alt text](https://github.com/rvravi77/RNN-Acc89-----CNN-Acc-91----TFv1/blob/main/IMG/RNN3.png?raw=true)

![alt text](https://github.com/rvravi77/RNN-Acc89-----CNN-Acc-91----TFv1/blob/main/IMG/CNN1.png?raw=true)

![alt text](https://github.com/rvravi77/RNN-Acc89-----CNN-Acc-91----TFv1/blob/main/IMG/CNN2.png?raw=true)
