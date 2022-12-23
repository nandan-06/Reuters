### Reuters is a multiclass213 classification

- Reuters data has 46 classes.
- Loaded the Reuters data from keras.
- Splitted data into the training and test data.
- As the data were in numbers, converted them to word for better understanding.
- Vectorized the data.
- Defined the dense layers in the model.
- 2 layers each with 64 unit output and activation of `relu`.
- 1 layer with 46 unit output and activation of `softmax`.
- Splitted the training data into train and validation dataset.
- Trained the model with 9 epochs.
- Plotted the graphs of loss and accuracy of training and validation scores against epochs.
- Trained the new model on the optimal number of epochs on complete training dataset.
- Used that model to predict values on test dataset.
