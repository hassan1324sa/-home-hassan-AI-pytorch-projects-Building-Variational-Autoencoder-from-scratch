# Building a Variational Autoencoder from Scratch

## Overview
This repository contains an implementation of a Variational Autoencoder (VAE) built from scratch using PyTorch. The VAE is a type of generative model that learns to encode and decode data probabilistically, allowing it to generate new samples similar to the training data.

## Features
- Implemented using PyTorch
- Custom encoder and decoder networks
- Loss function based on KL divergence and reconstruction loss
- Training pipeline with dataset support

## Installation
To set up the environment, install the required dependencies:

```bash
pip install torch torchvision matplotlib numpy
```

## Usage
Run the training script:

```bash
python train.py
```

Modify hyperparameters in `config.py` as needed.

## Directory Structure
```
/home/hassan/AI/pytorch-projects/Building-Variational-Autoencoder-from-scratch/
│── dataset/         # Dataset directory
│── models/          # Model definitions
│── utils/           # Utility functions
│── train.py         # Training script
│── config.py        # Configuration file
│── README.md        # Project documentation
```

## Results
After training, the model can generate new samples from the learned distribution. You can visualize the generated outputs using the provided scripts.

## Author
Hassan mohamed


