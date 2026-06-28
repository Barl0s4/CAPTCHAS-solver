# CAPTCHA Solver using Convolutional Neural Networks

A machine learning model that solves 5-character CAPTCHA images using a multi-output CNN built with TensorFlow and Keras. The model processes each image pixel-by-pixel, converting it to grayscale and resizing to 128×128 before feeding it through convolutional layers. Each of the 5 characters is predicted independently across a 36-class alphanumeric character set (a-z, 0-9).

## Built With
- Python
- TensorFlow / Keras
- NumPy
- PIL (Pillow)
- Matplotlib
- Seaborn

## Features
- Custom preprocessing pipeline for CAPTCHA image normalization
- Multi-output CNN architecture predicting each character position separately
- 36-class alphanumeric character encoding
- Training with early stopping, learning rate scheduling, and model checkpointing
- Character frequency distribution analysis and dataset visualization

## Dataset
[CAPTCHA Version 2 Images](https://www.kaggle.com/datasets/fournierp/captcha-version-2-images) via Kaggle
