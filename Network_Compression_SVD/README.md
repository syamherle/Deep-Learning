#Network Compresion using Singular Value Decomposition (on weights)

I have tried to compress weights of Deep Neural Network of 5-Layers for MNIST dataset problem. I have used Singular Value Decomposition on the weights of each layer by selecting top 10 and 20 features in Singular matrix.

With normal 5-Layer Deep Neural Network (Fully connected layers) the test accuracies on MNIST data was 98.5%

With top 20 features of Singular matrix values of trained weights, I was able to get 95% accuracy on test data for trained model.

Training the model again with top 20 features of Singular matrix of trained weights, I was able to get accuracy of around 98%. And the training time was smaller compared to original training, as the weights were reduced.
