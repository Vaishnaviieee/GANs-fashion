# GANs-fashion- To generate fashion images from MNIST fashion dataset
This project applies Generative Adversarial Networks (GANs) to generate fashion images using the Fashion MNIST dataset. GANs consist of two neural networks: a Generator and a Discriminator, which work together in a minimax game to produce realistic synthetic images.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Steps](#steps)
  - [Load Dataset](#load-dataset)
  - [Preprocess Data](#preprocess-data)
  - [Define Generator](#define-generator)
  - [Define Discriminator](#define-discriminator)
  - [Train Data](#train-data)
  - [Optimize](#optimize)
  - [Convert to Color](#convert-to-color)
  - [Generate Images](#generate-images)
### Dataset

The Fashion MNIST dataset is included in the project directory under \`data/fashion_mnist\`. It contains 60,000 training images and 10,000 testing images, each of size 28x28 pixels.

## Steps

### Load Dataset

Load the Fashion MNIST dataset, which consists of grayscale images of clothing items.

### Preprocess Data

Preprocess the data loaded.

### Define Generator

The generator, or decoder, is defined using a Sequential model. It takes a noise vector as input and generates an image.

### Define Discriminator

The discriminator, or encoder, is defined using a Sequential model. It takes an image as input and outputs a classification.

### Train Data

Train both the generator and discriminator of the GAN.

### Optimize

Optimize the encoder and decoder models.

### Convert to Color

Convert the grayscale images to colored for clearer and better designs.

### Generate Images

Generate synthetic fashion images.
