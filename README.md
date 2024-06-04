# German Traffic Sign Image Recognition

This project aims to recognize German traffic signs using machine learning and image recognition techniques. The project includes data preprocessing, data augmentation, and training of both dense and convolutional neural networks (CNNs).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Data Augmentation and Preprocessing](#data-augmentation-and-preprocessing)
- [Results](#results)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/traffic-sign-recognition.git
   cd traffic-sign-recognition

## Usage

1. Download the GTSRB dataset from [Kaggle](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) and place it in the `Traffic_Signals` directory.
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook German_Traffic_Sign_Recognition.ipynb

## Model Architecture

### Dense Neural Network
- Implements a fully connected neural network with multiple dense layers, Batch Normalization, and Dropout for regularization.
- The baseline model is trained without any preprocessing.

### Convolutional Neural Network (CNN)
- Enhances the model by adding convolutional layers for better feature extraction.
- Uses data augmentation techniques to increase the training data size and balance the class distribution.

## Data Augmentation and Preprocessing

- **Data Augmentation:** Applies rotation, translation, and bilateral filtering to increase the dataset size and balance class distribution.
- **Preprocessing:** Converts images to grayscale, applies local histogram equalization, and normalizes the pixel values.

## Results

- **Baseline Dense Network Test Accuracy:** 92.30
- **CNN Test Accuracy:** 97.02
  
