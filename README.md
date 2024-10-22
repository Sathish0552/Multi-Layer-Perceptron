# Multi-Layer Perceptron from Scratch for Heart Disease Classification

This project implements a Multi-Layer Perceptron (MLP) to classify the presence of heart disease using the UCI Heart Disease Dataset. The goal is to predict whether a patient has heart disease based on several features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
This project utilizes a Multi-Layer Perceptron (MLP), a type of artificial neural network, to classify the presence of heart disease based on patient medical data.

## Dataset
The dataset is the UCI Heart Disease dataset, consisting of:
- **Samples**: 303
- **Features**: 13 attributes including:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Serum Cholesterol
  - Fasting Blood Sugar
  - Resting ECG Results
  - Maximum Heart Rate Achieved
  - Exercise-Induced Angina
  - ST Depression Induced by Exercise
  - Slope of Peak Exercise ST Segment
  - Number of Major Vessels Colored by Fluoroscopy
  - Thalassemia
- **Label**: Presence of heart disease (binary classification: 0 = no disease, 1 = disease)

## Project Structure
├── heart.csv # The dataset file 
├── MLP.py # Main script for training and testing the MLP 
├── README.md # Project documentation 
└── requirements.txt # Python dependencies

## Prerequisites
To run this project, you will need:
- Python 3.x
- Necessary libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Sathish0552/Multi-Layer-Perceptron.git
   cd Multi-Layer-Perceptron
2. Install the dependencies:
   pip install -r requirements.txt
3. Ensure you have the dataset (heart.csv) placed in the project root directory.

## Usage
To run the perceptron model on the heart disease dataset, execute:
    ```bash
    python MLP.py

The script will:
- Load the dataset from heart.csv
- Shuffle the dataset
- Train the MLP model on a training set
- Test the model on the test set and output the accuracy

## Results
The results of the MLP model will be displayed in the terminal, showing the classification accuracy. Graphs for accuracy and loss curves will also be generated during training.

## Contributing
If you want to contribute to this project, feel free to:

Fork the repository
Submit a pull request
We welcome any improvements and bug fixes!