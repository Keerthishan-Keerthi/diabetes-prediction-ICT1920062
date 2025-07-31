# Diabetes Prediction Using Neural Network

## Project Description

This project uses a feedforward neural network to predict whether a patient is diabetic, based on health-related features. The model is trained on the **Pima Indian Diabetes dataset**, which includes values like glucose level, BMI, insulin, and age. The goal is to classify patients as diabetic or non-diabetic.

The following are implemented:
- Data cleaning, visualization, and preprocessing
- Model training with early stopping and L2 regularization
- Manual hyperparameter tuning adhering grid search methodology
- Model evaluation using accuracy, confusion matrix, classification report and ROC-AUC
- Final model saved and loaded using `.h5` format

## Code file
The code file containing all the steps mentioned are given under the name **diabetes-classifier.ipynb**
Final optimized model file is given under the name **diabetes_model.h5**

## Dataset
Pima Indian Diabetes dataset was used for training, validation and testing purposes of the model. 
The dataset is also uploaded herewith, under the name **diabetes.csv**
The dataset acn also be downloaded fron the following URL: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?resource=download#

## Setup Instructions

1. **Environment setup**:
   Python version and the exact versions of the libraraies used during the development and execution of the model are provided in the **requirements.txt.file**.
   Following libraries are rquired to be installed before running the model:
      - tensorflow               
      - numpy                     
      - pandas                   
      - seaborn                   
      - matplotlib              
      - keras                              
      - tf-keras
    Anaconda navigator with Jupyter Notebook was used for the development and testing purposes of this model.
   
2. **How to run the mode**:
  2.1. Create the environment according to the requirements.txt file.
  2.2. Run Jupyter notebook in that environment.
  2.3. Create a directory and copy the given dataset.
  2.4. Run the model.


