# MNIST-GAN-TRAINNING-
# MNIST GAN Training

This repository contains an implementation of a Generative Adversarial Network (GAN) trained on the MNIST dataset using TensorFlow and Keras. The model consists of a generator that generates fake images and a discriminator that classifies images as real or fake.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Training Process](#training-process)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project implements a GAN to generate handwritten digits similar to the MNIST dataset. The generator creates synthetic digit images, while the discriminator learns to differentiate between real and fake images.

## Installation

To set up the project, install the necessary dependencies:

```bash
pip install tensorflow numpy matplotlib
```

## Usage

To train the GAN model, run:

```bash
python train.py
```

This will train the generator and discriminator on the MNIST dataset.

## Training Process

- The discriminator is trained on real and fake images.
- The generator learns to produce realistic images to fool the discriminator.
- Training continues for a specified number of iterations.

## Results

The training process outputs the discriminator loss, discriminator accuracy, and generator loss at each iteration.

### Sample Output
```
Iteration: 0, Discriminator loss: 5.028236, Discriminator Accuracy: 0.244006, Generator loss: 0.000501
Iteration: 1, Discriminator loss: 5.028860, Discriminator Accuracy: 0.243987, Generator loss: 0.000500
```

## Contributing

Feel free to contribute by improving the model, fixing bugs, or enhancing documentation. Submit a pull request with your changes.

## License

This project is licensed under the MIT License.

