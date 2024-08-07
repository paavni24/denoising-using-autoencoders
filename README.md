# Denosing-medical-images-using-autoencoders

## Introduction
Autoencoders are a type of artificial neural network used for unsupervised learning. They are designed to learn efficient representations of data, typically for the purpose of dimensionality reduction or feature learning.

## Overview

This project involves using autoencoders to denoise dental medical images. The dataset consists of dental X-ray images with various types of noise. The goal is to apply an autoencoder to remove noise from these images, improving their quality for better diagnosis and analysis.

## Model Architecture

![Project Screenshot](https://github.com/paavni24/denoising-using-autoencoders/blob/main/autoenc-model.png)

## Dataset

The dataset used in this project contains dental X-ray images with noise. The images are stored in a directory with each image being a grayscale PNG file.

## Requirements

- Python 3.x
- TensorFlow 2.x
- scikit-learn
- pandas
- matplotlib
- numpy
- OpenCV (for image processing)

## Results
PSNR value for Denoised image is 68.22754978530422 dB while for Median filtered image is 58.44450155924384 dB


