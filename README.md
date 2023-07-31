# Pixel Character Sprites Generation

In this project, we use a CVAE short for Convolutional Variational Auto Encoder to generate new pixel sprites which are not present in the training dataset. CVAE is a technique that is used to compress images to a lower dimension space and then rebuild them from that space using randomness to generate new images. This project is made using the CVAE Notebook from Tensorflow.

## Introduction

### Auto Encoders
Auto Encoders are neural networks that are trained to compress data into a lower dimension called the latent dimension. This method is known as Encoding. Then these neural networks make the original data again from that latent dimension. This is known as Decoding.

### Variational Auto Encoders (VAE)
Variational Auto Encoders work on the basis of autoencoders but have some randomness in the neural network. Because of this randomness the autoencoder instead of generating the data it was trained on, generates completely new and random data. This is a very powerful tool to generate new data from existing data.

### Convolutional Variational Auto Encoders (CVAE)
Convolutional Variational Auto Encoders are designed to work with images. Using Convolution, the variational auto-encoder generates new random images using the ones it was trained on.


## Dataset

We used the following dataset of pixelated character sprites to train our neural network

Kaggle Link: [TinyHero - Retro pixel characters dataset](https://www.kaggle.com/datasets/calmness/retro-pixel-characters-generator)

## Results

![CVAE Results]()

## Credits

- [CVAE Notebook from TensorFlow](https://www.tensorflow.org/tutorials/generative/cvae)
- Special thanks to my teammate [Huraira Majeed](https://github.com/Abu-Huraira21)
