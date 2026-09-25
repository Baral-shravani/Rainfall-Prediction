# Rainfall Prediction Using Machine Learning

# Overview
Rainfall prediction plays an important role in weather forecasting, agriculture planning, and water resource management. This project uses machine learning techniques to predict whether rainfall will occur on the next day based on historical weather data.

The project implements and compares multiple machine learning models to identify the best performing model for rainfall prediction.

## Dataset
- Dataset: Australian Weather Dataset (WeatherAUS)
- Source: Kaggle
- Features include:
  - Rainfall
  - Sunshine
  - Humidity
  - Cloud Cover
  - Temperature
  - Wind Speed
  - Atmospheric Pressure
  - Other weather parameters

## Data Preprocessing
The following preprocessing steps were performed:
- Removed unnecessary features
- Handled missing values
- Extracted month information from date
- Encoded categorical variables using Label Encoding
- Converted target variable (RainTomorrow) into binary format
- Applied outlier handling
- Performed feature selection

## Machine Learning Models Implemented

The following models were trained and evaluated:

1. Decision Tree Classifier
2. Random Forest Classifier
3. Logistic Regression
4. XGBoost Classifier
5. Artificial Neural Network (ANN)
   


## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- TensorFlow/Keras
- XGBoost
  
  

## Results
The performance of different models was compared based on evaluation metrics. The best model was selected based on accuracy and overall classification performance.

(Results and comparison graphs will be added soon.)

## Conclusion
This project demonstrates the application of machine learning algorithms for rainfall prediction. The comparison of multiple models helps understand the effectiveness of different approaches in weather prediction tasks.

## Author
Shravani Puspak Baral
