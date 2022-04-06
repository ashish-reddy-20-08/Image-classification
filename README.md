# Image-classification
classifying the images using tensor flow


In this project we use an inbuilt tensor flow dataset and try to classify the images and used the model 

The [Sequential] model consists of three convolution blocks (tf.keras.layers.Conv2D) with a max pooling layer (tf.keras.layers.MaxPooling2D) in each of them.

There's a fully-connected layer (tf.keras.layers.Dense) with 128 units on top of it that is activated by a ReLU activation function ('relu') and the tf.keras.optimizers.Adam optimizer and tf.keras.losses.SparseCategoricalCrossentropy loss function.


To view training and validation accuracy for each training epoch, pass the metrics argument to Model.compile
