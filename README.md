# Healthcare Prediction Project

This project aims to predict attrition of healthcare staff using machine learning techniques, specifically leveraging the PyCaret library for streamlined model development and deployment.

## Dataset

The dataset used in this project is `watson_healthcare_modified.csv`. It contains various attributes related to healthcare staff, including demographic information, service usage, and an 'Attrition' column indicating whether an employee has left their position.

## Project Goal

The primary goal is to build a robust classification model that can accurately predict staff attrition, helping healthcare management identify at-risk employess and implement retention strategies.

## Technologies Used

*   Python
*   Pandas (for data manipulation)
*   PyCaret (for automated machine learning)

## Setup

To run this notebook, ensure you have the necessary libraries installed. You can install PyCaret using pip:

```bash
pip install pycaret
```

Once installed, you can proceed with loading the dataset and setting up the PyCaret environment as shown in the notebook cells.

## How to Use (Further Steps)

1.  **Data Loading and Exploration**: The initial cells load and display a glimpse of the data.
2.  **PyCaret Setup**: The `pycaret.classification.setup()` function is used to initialize the PyCaret environment, preparing the data for modeling.
3.  **Model Training**: PyCaret allows for easy comparison and training of various classification models.
4.  **Model Evaluation and Selection**: Evaluate models based on metrics like accuracy, precision, recall, and F1-score.
5.  **Prediction**: Use the best-performing model to make predictions on new, unseen data.

## Findings

The dataset is moderately imbalanced as it has 1477 instances of class No and 199 instances of class Yes. Thus, precision, recall, and F1-score are the best KPIs to measure this dataset since the dataset is imbalanced. 

## Model Performance Evaluation
