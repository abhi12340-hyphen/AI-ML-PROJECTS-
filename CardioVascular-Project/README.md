# Cardiovascular Disease Prediction

## Overview

This project focuses on predicting the presence of cardiovascular disease using machine learning techniques.
The model analyzes patient health data such as age, blood pressure, cholesterol, and lifestyle factors to determine the likelihood of heart disease.

## Objective

To build and compare multiple machine learning models and select the best model for predicting heart disease accurately.

## Dataset

* Dataset used: `cardio_train.csv`
* Contains medical attributes like:

  * Age
  * Gender
  * Height & Weight
  * Blood Pressure (ap_hi, ap_lo)
  * Cholesterol
  * Glucose
  * Lifestyle factors (smoking, alcohol, activity)
* Target variable:

  * `cardio` → 0 (No disease), 1 (Disease)
    
## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

##  Machine Learning Models

The following models were implemented and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Support Vector Machine (SVM)
* Random Forest

## Data Analysis & Visualization

* Data preprocessing and cleaning
* Count plots for target distribution
* Correlation heatmap to analyze feature relationships

## Model Evaluation

All models were evaluated based on accuracy.

| Model               | Performance |
| ------------------- | ----------- |
| Logistic Regression | Moderate    |
| KNN                 | Lower       |
| Decision Tree       | Moderate    |
| SVM                 | Good        |
| Random Forest       | Best        |

## Final Model

Random Forest achieved the highest accuracy and was selected as the final model for prediction.

## Prediction

The final model can take patient health data as input and predict whether the person is likely to have cardiovascular disease.

## Future Improvements

* Improve accuracy using hyperparameter tuning
* Deploy the model using Flask or web app
* Use real-time healthcare data
  
## Conclusion

This project demonstrates how machine learning can be used to assist in early detection of heart disease and support medical decision-making.

## Author

ABHIRAM ADDEPALLY 
