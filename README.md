# Adversarial Attack Evaluation on Neural Networks

This repository contains the code, Jupyter Notebooks, and data for evaluating the effectiveness of adversarial attacks, specifically FGSM (Fast Gradient Sign Method) and Patch Attacks, on neural networks. The research focuses on analyzing the vulnerability of two prominent models, a Custom CNN trained on CIFAR-10 and a ResNet model trained on TinyImageNet, to these adversarial techniques.

## Overview

Adversarial attacks pose significant threats to the reliability and security of deep learning systems. This project aims to investigate the efficacy of FGSM and Patch Attacks in fooling neural networks and compromising their accuracy. By conducting rigorous experiments and analyzing the results, we aim to gain insights into the robustness of neural networks against adversarial attacks and provide valuable implications for enhancing their security and reliability in real-world applications.

## Contents

- `notebooks/`: Contains Jupyter Notebooks (`*.ipynb`) for a more interactive exploration of the code and experiments.
- `data/`: Contains the datasets used in the experiments, including CIFAR-10 and TinyImageNet.
- `results/`: Stores the results of the experiments, including accuracy metrics, error rates, and visualizations.
- `README.md`: You are here! This file provides an overview of the project, instructions for running the code, and guidelines for interpreting the results.

## Getting Started

To run the experiments and evaluate the models, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/adversarial-attacks.git
```

2. Explore the Jupyter Notebooks in the  directory for a more interactive experience.

3. Check the report directory for the output files containing accuracy metrics, error rates, and visualizations.

## Requirements

- Python 3.x
- NumPy
- Pytorch (for neural network models)
- Matplotlib (for visualization)
- tqdm (for progress bars)
- Jupyter Notebook (for interactive exploration)

