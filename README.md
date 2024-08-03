# A Review of Machine Learning Models for Predicting Cardiovascular Diseases

## Overview

Cardiovascular diseases (CVD) are the leading cause of death globally, accounting for around 17.9 million lives annually. This project aims to utilize machine learning models to refine the early detection of potential heart disease in patients, thereby improving outcomes and reducing premature deaths. We reviewed and implemented several machine learning algorithms to predict CVD using the "Heart Failure Prediction Dataset" from Kaggle.

## Project Motivation

Early identification of individuals at high risk of cardiovascular diseases can significantly reduce the rates of premature deaths. By leveraging machine learning models, we aim to build a predictive model with high accuracy, precision, recall, and F1 scores to serve as a valuable tool in early CVD detection.

## Dataset

The dataset used in this project is the "Heart Failure Prediction Dataset" from Kaggle, which includes 12 features and 918 observations. The features represent various clinical attributes of patients, and the target variable indicates the presence of heart disease.

## Data Preprocessing

1. **Categorical to Numerical Conversion:** Used Panda’s `get_dummies` method to convert non-numerical features to numerical ones.
2. **Outlier Detection and Handling:** Identified outliers using boxplots and handled them by scaling the data instead of removal to retain valuable information.
3. **Dimensionality Reduction:** Performed factor analysis and evaluated factor eigenvalues using a scree plot to minimize information loss while reducing the number of features.

## Machine Learning Models

We implemented and evaluated the following machine learning models:

1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **Random Forest**
4. **k-Nearest Neighbors (kNN)**
5. **Decision Tree**

## Model Evaluation

The models were evaluated using the following performance metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

Based on the evaluation, the SVM model demonstrated the highest recall value, which is critical for predicting true positives and minimizing false negatives in a healthcare setting.

## Key Findings

- **SVM Model:** Achieved the highest recall, making it the preferred model for predicting cardiovascular diseases.
- **Feature Importance:** Identified key features influencing heart disease predictions, including chest pain type, exercise-induced angina, old peak, and ST slope.
- **Outlier Handling:** Keeping and scaling outliers resulted in higher accuracy metrics, emphasizing the importance of retaining critical patient information.

## Conclusion

This project demonstrates the potential of machine learning in improving early detection of cardiovascular diseases. Further experimentation and analysis are recommended to refine these models and ensure their applicability in real-world healthcare scenarios.

## Future Work

- **Statistical Hypothesis Testing:** Perform a thorough statistical review to analyze variations in results based on different training data splits.
- **Model Optimization:** Experiment with additional hyperparameter tuning and advanced machine learning techniques to enhance predictive performance.

## References

1. [Heart Failure Prediction Dataset](https://www.kaggle.com/fedesoriano/heart-failure-prediction) - Kaggle
2. [Cardiovascular Diseases](https://www.who.int/health-topics/cardiovascular-diseases#tab=tab_1) - World Health Organization
3. [Learn Classification Algorithms using Python and scikit-learn](https://developer.ibm.com/tutorials/learn-classification-algorithms-using-python-and-scikit-learn/) - IBM Developer
4. [Blood Cholesterol](https://www.mayoclinic.org/diseases-conditions/high-blood-cholesterol/symptoms-causes/syc-20350800) - Mayo Clinic

---

**Authors:** Amr Ibrahim & Vlad Yashaev  
**Institution:** SUNY Old Westbury  
**Semester:** Fall 2022
