# Deep-Learning
Contains submissions of the Deep Learning Elective Course at IIITA.

# Dependencies
1. Python3
2. Numpy
3. Matplotlib
4. Keras(Tensorflow backend)

# Assignments

1. Implementing building blocks of convolutional neural networks from scratch using numpy and matplotlib. 
Following functions were implemented.
	1. Zero padding
	2. Convolve window
	3. Convolution forward
	4. Pooling forward
	
2. Make a CNN model on the FEI dataset(<a>https://fei.edu.br/~cet/facedatabase.html</a>) and divide the dataset into training,
validation and testing. Analyze, visualize and generate final feature map of your model just before Softmax function. 
Try tweaking the network by using Dropout, Drop Connect and any other method to change/ analyze and improve performance of the model.

3. Implement and analyse the variations in various varients of gradient descent algorithm(use only Numpy) by applying linear 
regression on the Housing Price dataset by taking only two features and applying the following optimizers.
	1. Stochastic Gradient Descent
	2. Gradient Descent with Momentum
	3. RMSProp
	4. ADAM optimizer
	
4. Implement the following autoencoders and analyse them for 20, 40 and 60 epochs: 
	1. Vanilla Autoencoder
	2. Sparse Autoencoder
	3. Contractive Autoencoder
	
5. Train a VAE model (the encoder, decoder and VAE) with MNIST handwritten dataset using K-L divergence and J-S divergence as components in the loss function and adam as optimizer. 
After latent space is created generate MNIST digits by sampling the latent vector from a Gaussian distribution with mean = 0 and std = 1.
  
