# SONAR-Rock-vs-Mine-Prediction
# Rock vs Mine Prediction from SONAR Data using Python

This project uses a machine learning model to classify whether an object is a **rock** or a **mine** based on SONAR signal data. The dataset is sourced from the Kaggle and consists of 60 sonar frequency response values for each sample.



## Project Overview

Underwater mines can be hazardous, and their detection is vital for safety in naval operations. This project builds a predictive model that takes sonar data as input and determines whether the detected object is a **mine** or **rock**. The notebook walks through data preprocessing, exploratory analysis, model training, evaluation, and testing.



## Files

- `Rock_v_s_Mine_Prediction_from_SONAR_data_using_python.ipynb`:  
  The Jupyter Notebook containing the entire process from loading the data to building and evaluating the model.

- `sonar.csv`:  
  The dataset containing 208 samples with 60 features and a label (either 'M' for Mine or 'R' for Rock).



## Dataset Description

- **Instances:** 208  
- **Attributes:** 60 continuous features (numeric sonar readings) + 1 categorical label  
- **Target:**  
  - `M` – Mine  
  - `R` – Rock



## How to Run the Project

1. Clone the repository or download the notebook and dataset.
2. Ensure you have Python installed.
3. Install required libraries.
4. Run the Jupyter Notebook cell by cell.




## Model Summary

The project uses **Logistic Regression** for binary classification. Key steps include:

- Data normalization using `StandardScaler`
- Train-Test split (typically 80-20)
- Model training and evaluation (accuracy, confusion matrix)
- Final testing with real data inputs



## Accuracy

Model accuracy is typically around **85-90%** depending on train/test split and preprocessing.

