# Deep-Autoencoder-using-Tensorflow

## Getting Started
This is an implementation of an stacked autoencoder using Keras to reconstruct a subset of samples from the mnist dataset.The architecture is built using Keras.
Autoencoders are deep neural networks used to reproduce the input at the output layer i.e. the number of neurons in the output layer is exactly the same as the number of neurons in the input layer. 
But, the actual use of autoencoders is for determining a compressed version of the input data with the lowest amount of loss in data. What I mean by this is: You must have heard of a term while developing machine learning projects called Principle Component Analysis. The concept of PCA is to find the best and relevant parameters for training of a model where the dataset has a huge number of parameters. 
The autoencoders work in a similar way. The encoder part of the architecture breaks down the input data to a compressed version ensuring that important data is not lost but the overall size of the data is reduced significantly. This concept is called Dimensionality Reduction.

![images](https://user-images.githubusercontent.com/28685502/43400785-396a18f8-942c-11e8-9251-807f13d5dd1c.png)


## Dataset 
The code downloads the mnnist dataset automatically if it does not exist on your local machine. Alternatively, download the four zip fles and place them in a directory and name it according to the code.

## Results
![untitled](https://user-images.githubusercontent.com/28685502/43400628-d4d02928-942b-11e8-9895-1adcfe62d4d6.png)

Here, we can see the reconstructions are not perfect but are pretty close to the original images. Notice, the reconstruction of 2 seems like a 3, this is due to information loss while compressing.