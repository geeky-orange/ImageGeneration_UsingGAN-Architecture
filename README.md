# ImageGeneration_UsingGAN-Architecture


# Anime Image Generation using GANs with PyTorch

## Overview

This project aims to generate new anime images using a Generative Adversarial Network (GAN) architecture and the PyTorch library. The project takes in a dataset of anime images from Kaggle, trains the GAN on the dataset, and then generates new anime images that are similar to the original dataset.

## Requirements

- PyTorch
- Kaggle API (for downloading the dataset)
- Numpy
- Matplotlib

## Dataset

The anime image dataset used in this project can be downloaded from Kaggle using the following steps:

1. Create a Kaggle account and obtain an API key.
2. Run the following command in the terminal to download the dataset:


## Model

The project uses a GAN architecture to generate new anime images. The GAN consists of two neural networks, a generator and a discriminator, that compete with each other to improve the quality of the generated images. The generator creates new images, while the discriminator evaluates the authenticity of the generated images. Over time, the generator becomes better at creating realistic images, while the discriminator becomes better at detecting fake images.

## Usage

1. Clone the repository.
2. Run the following command in the terminal to install the required packages:
3. Extract the dataset to the project folder.
4. Run the following command in the terminal to train the GAN:
5. The generated images can be viewed in the `generated_images` folder.

## Contributions

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request.

## Conclusion

This project demonstrates the use of GANs to generate new anime images using the PyTorch library and a dataset from Kaggle. The project can be further improved by incorporating more advanced techniques and technologies, such as difficult and other methods for enhancing the quality of the generated images.
