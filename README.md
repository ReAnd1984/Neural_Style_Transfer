# Neural Style Transfer

![Logo](https://camo.githubusercontent.com/3225433dd177ce8d8255c760ab7aefbdba83107545b62d17f4459cde05ecedd5/68747470733a2f2f696d672e736869656c64732e696f2f707970692f707976657273696f6e732f74662d6167656e7473)

This repository contains code for performing Neural Style Transfer using TensorFlow. Neural Style Transfer is a fascinating technique that allows us to generate artistic images by combining the content of one image with the style of another image.

## Overview
The main objectives of this project are to understand and implement the Neural Style Transfer algorithm, optimize the generated image to minimize the loss function, and visualize the style transfer process by saving intermediate results.

The code utilizes the VGG19 model pre-trained on the ImageNet dataset to extract features from content and style images. These features are then used to calculate the content loss and style loss, which are combined with the total variation loss to form the total loss.

The optimization process involves using gradient descent to minimize this total loss, resulting in a generated image that exhibits the content of the base image and the style of the style reference image.

Intermediate results are saved periodically during the optimization process to visualize the evolution of the style transfer. The generated images are saved in the specified directory, even if only the final image will be displayed in this notebook.
