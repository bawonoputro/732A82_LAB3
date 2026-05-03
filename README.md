# 732A82 Lab 3 — Deep Learning (Linköping University)

This repository contains my work for **Lab 3** in the course **732A82** at Linköping University, Statistics and Machine Learning Master's Programme. The main assignment is implemented in the Jupyter notebook(s) and is shared here as part of my portfolio.

> **Collaboration note:** This lab assignment was completed as a **group of two**.

## What I worked on
- Implemented a CNN image classifier for **CIFAR‑10** (10 classes, 32×32 RGB images).
- Explored 2D convolutions using Gaussian and Sobel filters to understand filtering effects and output sizes.
- Prepared the dataset: train/validation/test split, normalization to `[-1, 1]`, and one‑hot labels.
- Built a configurable CNN (`Conv2D → BatchNorm → MaxPool → Dense`).
- Trained multiple configurations and evaluated performance on the test set.

## What I learned
- How convolution kernels and padding modes affect feature maps and spatial dimensions.
- The difference between convolution and cross‑correlation in CNN layers.
- Practical preprocessing steps for image classification with neural networks.
- How batch size and model capacity impact training stability and GPU memory use.
- How to diagnose overfitting by comparing training vs. validation/test accuracy.

## Repository Structure
- `CNN_Lab.ipynb` — main lab notebook with the full assignment.
- `CNN_Lab_check_ori.ipynb` — the original notebook from the professor before modification by the student.
- `utilities.py` — helper functions used by the notebooks.
- `utilities_ori.py` — helper functions used by the notebooks before modification
- `images/` — figures and assets.

## Notes
- This repository is shared for educational and portfolio purposes.
- The implementation details and experiments are documented directly in the notebook.
- Images used in the notebooks is not uploaded in this repository
