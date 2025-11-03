## Overview
This repository contains implementations of different types of autoencoders using Jupyter notebooks:

- **Autoencoders.ipynb**: Simple autoencoder with dense layers for MNIST image reconstruction.
- **Denoising_Autoencoder.ipynb**: Denoising autoencoder that removes noise from MNIST images using convolutional layers.
- **Variational_Autoencoder.ipynb**: Variational autoencoder (VAE) for MNIST, including latent space visualization and image generation.

## How to run
1. Requirements: Python 3.8+ (recommended), Jupyter Notebook, and packages listed in `requirements.txt`.
2. Setup environment:
	```bash
	python -m venv venv
	source venv/bin/activate
	pip install -r requirements.txt
	```
3. Start Jupyter Notebook:
	```bash
	jupyter notebook/Collab for GPU Enabled training
	```
4. Open any notebook (`Autoencoders.ipynb`, `Denoising_Autoencoder.ipynb`, or `Variational_Autoencoder.ipynb`) and run the cells.

## Notebooks
- **Autoencoders.ipynb**: Basic autoencoder for dimensionality reduction and reconstruction.
- **Denoising_Autoencoder.ipynb**: Adds noise to images and trains a model to reconstruct clean images.
- **Variational_Autoencoder.ipynb**: Implements a VAE, visualizes latent clusters, and generates new images from latent space.