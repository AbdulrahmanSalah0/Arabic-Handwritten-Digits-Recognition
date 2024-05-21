# Arabic Handwritten Digit Recognition

This repository contains code for recognizing Arabic handwritten digits using Convolutional Neural Networks (CNN), Artificial Neural Networks (ANN), and Random Forest.

## Project Overview

The project aims to:

- Develop machine learning models to accurately recognize Arabic handwritten digits (0-9).
- Compare the performance of CNNs and ANNs for this task.
- Experiment with Random Forest as an alternative approach.

## Data

The dataset used in this project consists of Arabic handwritten digits, with 60,000 training samples and 10,000 test samples. The data is provided in CSV format, with each row representing a 28x28 grayscale image.

## Model Architecture

- **CNN:** The CNN model utilizes two convolutional layers with max pooling, followed by a flatten layer, dense layers, a dropout layer, and a final dense layer with softmax activation.
- **ANN:** The ANN model has a simpler architecture with three dense layers.
- **Random Forest:** The Random Forest model is an ensemble method that combines multiple decision trees.

## Results

The CNN model achieves the highest accuracy among the three models, demonstrating its effectiveness in recognizing Arabic handwritten digits. The Random Forest model performs reasonably well, but falls short compared to the deep learning models.

## GUI Application

A simple GUI application is provided for drawing digits and getting predictions from the trained models.

