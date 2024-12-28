# Breast Cancer Classification and Prediction

This project focuses on analyzing breast cancer data to predict outcomes and survival rates using machine learning techniques. The dataset includes information on patients' demographics, tumor characteristics, and treatment outcomes. Various classification models are used, and the Random Forest classifier demonstrates the highest accuracy.

## Features of the Dataset

The dataset contains the following columns:

- **Age**: Age of the patient.
- **Race**: Race of the patient.
- **Marital Status**: Marital status of the patient.
- **T Stage**: Tumor stage.
- **N Stage**: Node stage.
- **6th Stage**: 6th edition cancer stage classification.
- **Differentiate**: Tumor differentiation grade.
- **Grade**: Grade of the cancer.
- **A Stage**: Regional A stage.
- **Tumor Size**: Size of the tumor (in cm).
- **Estrogen Status**: Estrogen receptor status (positive/negative).
- **Progesterone Status**: Progesterone receptor status (positive/negative).
- **Regional Node Examined**: Number of regional lymph nodes examined.
- **Regional Node Positive**: Number of positive lymph nodes.
- **Survival Months**: Survival duration in months.
- **Status**: Patient status (Alive/Dead).

## Preprocessing Steps

1. **Label Encoding**: Categorical variables are encoded to numerical values using `LabelEncoder` from `sklearn`.
2. **Feature Scaling**: Continuous variables are scaled using `StandardScaler` for better performance of machine learning models.
3. **Train-Test Split**: The dataset is split into training and testing sets to evaluate the models.

## Machine Learning Models

The following classifiers are implemented and compared:

1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Support Vector Classifier (SVC)**

### Metrics Used for Evaluation

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**

### Result

The Random Forest Classifier demonstrates the highest accuracy in predicting breast cancer outcomes.
