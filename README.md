### Digit Recognition CNN

This repo follows the guide on [multi class classifier for Digit Recognition](https://machinelearningmastery.com/handwritten-digit-recognition-using-convolutional-neural-networks-python-keras/) using a convolutional neural network in Python. This is on the MNist dataset loaded through Keras.

# Result

- 108s - loss: 0.0147 - acc: 0.9956 - val_loss: 0.0342 - val_acc: 0.9889
  CNN Error: 1.11%

# Keywords and linked articles for learning

- Convolutional neural network

`A convolutional neural network deviates from the standard Perceptron it is beter at retaining spatial information during the training phase allowing it to classify images better than MLPs. full_padding_no_strides_transposed.gif" height="250px" />

- Convolutional layers

`The raw image input is covoluted as shown in the image below, this reduces the vector space representing the image whilst still retaining essential features.`

<img src="https://raw.githubusercontent.com/iamaaditya/iamaaditya.github.io/master/images/conv_arithmetic/

- Pooling layers

`This is where the image is divided into sub regions and only the pooled value is retained. This reduces an`x by x`image to a single value. Typically max pooling is used where the maximum value in the`x by x`region is kept.`

  <img src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Max_pooling.png" height="150px" />

- Dropout layers
  `To avoid over fitting the dropout layer will individual nodes will be removed based on a probability.`
