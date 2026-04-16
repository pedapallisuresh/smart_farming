# Crop Recommendation Assistant

## Overview

The **Crop Recommendation Assistant** is an intelligent machine learning application that provides crop recommendations based on soil and environmental conditions. Using the k-Nearest Neighbors (KNN) algorithm, this application analyzes soil nutrients, temperature, humidity, pH levels, and rainfall patterns to recommend the most suitable crop for a given geographical location.

## Features

- **Machine Learning-Powered Predictions**: Utilizes scikit-learn's KNN classifier with k=3 neighbors for accurate crop recommendations
- **Soil Analysis**: Evaluates nutrient levels including:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
- **Environmental Monitoring**: Analyzes:
  - Temperature
  - Humidity
  - pH level
  - Rainfall
- **Interactive GUI**: User-friendly graphical interface built with PySimpleGUI
- **Audio Feedback**: Text-to-speech functionality provides detailed analysis and recommendations
- **Multi-language Support**: Crop names displayed in both English and Hindi
- **22 Crop Varieties**: Supports recommendations for a diverse range of crops including cereals, pulses, fruits, and cash crops

## Supported Crops

Apple, Banana, Blackgram, Chickpea, Coconut, Coffee, Cotton, Grapes, Jute, Kidneybeans, Lentil, Maize, Mango, Mothbeans, Mungbeans, Muskmelon, Orange, Papaya, Pigeonpeas, Pomegranate, Rice, and Watermelon

## Requirements

### Dependencies

- **Python** 3.6 or higher
- **pandas**: Data manipulation and Excel file handling
- **scikit-learn**: Machine learning algorithms and preprocessing
- **numpy**: Numerical computing and array operations
- **PySimpleGUI**: GUI framework for the application
- **pyttsx3**: Text-to-speech conversion (Windows SAPI5)

### Install Dependencies

```bash
pip install pandas scikit-learn numpy PySimpleGUI pyttsx3
