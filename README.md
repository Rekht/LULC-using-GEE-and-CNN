# Land Use Land Cover (LULC) Classification using Google Earth Engine (GEE) and CNN

## Overview
This project focuses on Land Use Land Cover (LULC) classification using satellite imagery processed with Google Earth Engine (GEE) and a Convolutional Neural Network (CNN). The approach leverages GEE for large-scale remote sensing data processing and CNN for accurate classification.

## Dataset
The dataset used for this project is obtained from Google Earth Engine (GEE). The script for data preprocessing and extraction is available at the following link:
[Google Earth Engine Script](https://code.earthengine.google.com/fa55d2f96ce7099b9af44089547d0f3a)

## Methodology
1. **Data Preprocessing**:
   - Image selection and filtering based on cloud cover and time range.
   - Feature extraction using spectral indices and bands from satellite imagery.
   
2. **Modeling**:
   - CNN-based deep learning model is trained for classification.
   - Data augmentation and transfer learning techniques are applied.

3. **Evaluation**:
   - Metrics such as accuracy, precision, recall, and F1-score are used to evaluate the model performance.

## Tools Used
- Google Earth Engine (GEE)
- TensorFlow/Keras for CNN implementation
- Python for data processing and model training

## Results
- Comparative analysis of CNN-based LULC classification with traditional machine learning models.
- Visualization of classification results using GEE and Matplotlib.
