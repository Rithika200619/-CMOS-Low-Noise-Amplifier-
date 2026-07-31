# CMOS Low Noise Amplifier Performance Prediction using ANN

## Overview

This project uses an **Artificial Neural Network (ANN)** to predict the **Gain** and **Noise Figure** of a CMOS Low Noise Amplifier (LNA). By learning from existing data, the model can estimate amplifier performance based on **Temperature** and **Frequency**, reducing the need for repeated simulations.

## Features

- Data preprocessing and cleaning
- Outlier removal using the IQR method
- Exploratory Data Analysis (EDA)
- Feature scaling
- ANN model using TensorFlow/Keras
- Prediction of Gain and Noise Figure
- Model evaluation using MAE, MAPE, and R² Score

## Dataset

**Input Features**
- Temperature (°C)
- Frequency (GHz)

**Output Features**
- Gain (dB)
- Noise Figure (dB)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

## Workflow

1. Load the dataset
2. Clean and preprocess the data
3. Perform Exploratory Data Analysis
4. Train the ANN model
5. Evaluate model performance
6. Predict Gain and Noise Figure for new inputs

## Results

The trained ANN successfully predicts the **Gain** and **Noise Figure** of a CMOS Low Noise Amplifier using Temperature and Frequency as inputs.
