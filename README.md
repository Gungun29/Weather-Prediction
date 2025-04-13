# Weather-Prediction

## Overview

In this project, we employed a diverse set of machine learning algorithms to predict weather conditions. The algorithms used include:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**
- **Gradient Boosting Classifier**
- **XGBoost**
- **RandomForest Classifier**

These models were trained using weather-related features such as precipitation, maximum and minimum temperatures, and wind speed.

## Evaluation

After training the models, we evaluated their performance using the following steps:

1. **Accuracy Scores**:
   - The accuracy of each model was calculated to assess the proportion of correct predictions.
   
   - Accuracy Scores:
     - **Logistic Regression**: 0.8327645
     - **K-Nearest Neighbors (KNN)**: 0.778157
     - **Decision Tree Classifier**: 0.7372014
     - **Gradient Boosting Classifier**: 0.8156997
     - **XGBoost**: 0.8054608
     - **RandomForest Classifier**: 0.8020478

2. **Normalized Confusion Matrices**:
   - We generated normalized confusion matrices to provide a detailed view of how well each model classified the different weather categories. These matrices showed the distribution of true vs. predicted labels, revealing the strengths and weaknesses of each model.
