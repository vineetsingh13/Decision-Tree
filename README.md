# Decision-Tree
## Drug Prescription Decision Tree Classification
This repository contains code for predicting drug prescriptions using the Decision Tree algorithm. The dataset includes information about patients, such as age, sex, blood pressure (BP), cholesterol level, sodium-to-potassium ratio (Na_to_K), and the corresponding drug prescribed.

## Dataset
The dataset used is a tabular dataset with the following columns:

 - Age
 - Sex
 - Blood Pressure (BP)
 - Cholesterol Level
 - Sodium-to-Potassium Ratio (Na_to_K)
 - Drug
 - Decision Tree Classification

The Decision Tree algorithm is implemented to predict which drug should be prescribed based on the patient's features:

 - Age
 - Sex
 - Blood Pressure
 - Cholesterol Level
 - Sodium-to-Potassium Ratio

## Data Preprocessing
Before applying the Decision Tree algorithm, the data is processed using LabelEncoder() to convert all categorical variables into numeric values.

## Data Splitting
The dataset is split into training and testing sets (70% training, 30% testing) to train the model and evaluate its performance.

## Model Training
The Decision Tree is initially created using entropy as a criterion and an initial depth of 4. Subsequently, the code iterates through different depth values to find the optimal depth that maximizes accuracy.

## Code Execution Environment
The code has been implemented using Python and executed in Google Colaboratory. Google Colaboratory provides a free and convenient platform for running Python code in a Jupyter notebook environment.

## Files in the Repository
DecisionTree.ipynb: Jupyter notebook containing the code for Decision Tree classification.
drug200.csv: The dataset used for training and testing the Decision Tree model.
README.md: This readme file.


## Dependencies
The following Python libraries are used in the implementation:

pandas
numpy
sklearn
