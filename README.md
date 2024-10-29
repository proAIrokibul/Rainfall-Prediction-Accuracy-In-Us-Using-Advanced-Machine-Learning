# Rainfall-Prediction-Accuracy-In-Us-Using-Advanced-Machine-Learning
This repository contains a machine learning project aimed at predicting rainfall based on various meteorological features. The dataset includes historical weather data, allowing us to assess the likelihood of rain the following day.

## Dataset

The dataset consists of the following features:

- **Temperature**: The temperature recorded (in degrees).
- **Humidity**: The humidity percentage.
- **Wind Speed**: The wind speed (in km/h).
- **Precipitation**: The amount of precipitation recorded.
- **Cloud Cover**: The cloud cover percentage.
- **Pressure**: The atmospheric pressure.
- **Rain Tomorrow**: Target variable indicating whether it will rain tomorrow (1 for Yes, 0 for No).

## Models Implemented

Three different machine learning algorithms were implemented and evaluated for their performance in predicting rainfall:

### 1. Logistic Regression
- **Accuracy**: Approximately 91%
- **Precision**: 
  - Class 0 (No Rain): 92%
  - Class 1 (Rain): 86%
- **Recall**:
  - Class 0: 97%
  - Class 1: 71%
- **F1 Score**:
  - Class 0: 94%
  - Class 1: 78%

### 2. Random Forest Classifier
- **Accuracy**: 100%
- **Precision**: 
  - Class 0: 100%
  - Class 1: 100%
- **Recall**:
  - Class 0: 100%
  - Class 1: 100%
- **F1 Score**:
  - Class 0: 100%
  - Class 1: 100%

### 3. Support Vector Machine (SVM)
- **Accuracy**: Approximately 91%
- **Precision**:
  - Class 0: 92%
  - Class 1: 86%
- **Recall**:
  - Class 0: 97%
  - Class 1: 70%
- **F1 Score**:
  - Class 0: 94%
  - Class 1: 77%

## Conclusion

The Random Forest Classifier outperformed the other models, achieving a perfect accuracy of 100%. This indicates that it was able to classify all instances in the test set accurately. Meanwhile, Logistic Regression and Support Vector Machine models performed well with accuracies around 91%, but they exhibited lower precision and recall for predicting rainfall.
This project demonstrates the effectiveness of various machine learning techniques in weather prediction. It serves as a solid foundation for further enhancements, such as hyperparameter tuning, feature engineering, and the incorporation of additional meteorological data to improve predictive performance.



