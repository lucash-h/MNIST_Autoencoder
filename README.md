# MNIST_Autoencoder
This is an autoencoder model that reduces the dimensionality of an image before attempting to restructure it back to its original shape.
The mnist dataset is being used and the model performs pretty decently, with reconstructed images turning out pretty similarly to their respective images.
## Architecture
![image](https://github.com/lucash-h/MNIST_Autoencoder/assets/93152056/ca940fe1-3b4b-462c-9f99-023da94c19da)
[image found here](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftowardsdatascience.com%2Fapplied-deep-learning-part-3-autoencoders-1c083af4d798&psig=AOvVaw1mWtehy6MDmqWH0Oq6w9d4&ust=1711863885621000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCIjb6Yikm4UDFQAAAAAdAAAAABAE)

### Encoder
![image](https://github.com/lucash-h/MNIST_Autoencoder/assets/93152056/63831a47-a7b9-40b5-ae72-bbbe21ae9114)


### Decoder
![image](https://github.com/lucash-h/MNIST_Autoencoder/assets/93152056/62a34e48-758f-4339-9040-08097aa971d9)

## Variables and hyperparameters
These can be found near the beginning of the colab or IDE file to be easily changed
* batch size is the number of images in a batch
* learning rate refers to the step size at which model parameters are updated during optimization. In other words, it controls the rate at which the model learns.
* epochs is the number of batches that are used to train the model
* first dimension (first_dim) is the size that the image gets shaped to in the first Dense layer
* latent dimension (latent_dim) is the size of the final Dense layer in the encoder and the Input layer of the decoder
* Shape is the dimensions of the input to the encoder
## Running in google colab
1. Navigate to the autoencoder.ipynb file
2. click on the ```open with google colab``` button
3. Ensure that the runtime type is set to Python 3 by clicking on the "Runtime" menu, then "Change runtime type", and selecting "Python 3".
4. Run the entire notebook by clicking on the "Runtime" menu and selecting "Run all". Alternatively, run each cell individually by clicking on the play button to the left of each cell.
