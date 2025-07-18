# MNIST GAN with TensorFlow and Keras

This repository contains a complete implementation and analysis of a Generative Adversarial Network (GAN) trained on the MNIST dataset using TensorFlow and Keras.

## 🧠 Overview

The project is divided into two main notebooks:

- `Image_Generation_with_GAN.ipynb`:  Contains the full GAN implementation including the Generator, Discriminator, and training loop for image generation. The model learns to generate MNIST-style digits from random noise.
- `GAN Report.ipynb`: A structured analysis explaining architectural decisions (e.g. use of `tanh`, `LeakyReLU`) and training behavior.

## 📊 Features

- TensorFlow/Keras-based GAN
- MNIST digit generation
- Custom training loop
- Image saving after each epoch
- Architectural reasoning and activation analysis

## 🧰 Technologies Used

- Python 3
- TensorFlow & Keras
- NumPy
- Matplotlib

## 🏁 Getting Started

### Installation

Clone the repo and install the requirements:

```bash
git clone https://github.com/Thierry-Celestin/mnist-gan-tf-keras.git
cd mnist-gan-tf-keras
pip install -r requirements.txt
