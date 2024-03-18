# Custom DNN using TensorFlow 2.x

This is an example of a fully-connected feed-forward neural network implemented in TensorFlow 2.x without relying (much) on Keras, except for tf.keras.Model, tf.keras.layers.Layer and tf.keras.layers.RandomRotation.

This implementation has custom "dense", "flatten" and "dropout" layers. EarlyStopping, Adam and the loss function are all implemented from scratch. Finally, the training loop is also made explicit (i.e. not using the fit() function).

An hyperparameter optimization is also done using grid search.

## Dependencies

```
tensorflow
tensorflow_datasets
numpy
matplotlib
sklearn
seaborn
```
