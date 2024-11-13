Logistic Regression on Breast Cancer Dataset
This project applies logistic regression to predict whether a tumor is malignant or benign, based on features extracted from cell nuclei in breast tissue samples. By analyzing these characteristics, we aim to build a reliable model to support diagnostic efforts.

Dataset Overview
The dataset contains 569 entries with 9 features that describe various mean properties of cell nuclei, captured from digitized images of breast masses. Each entry includes measurements that help differentiate between malignant and benign tumors, making this dataset suitable for binary classification.

Features
ID: Unique identifier for each observation.
Diagnosis: Target variable, indicating the type of tumor:
M: Malignant
B: Benign
radius_mean: Mean radius of cell nuclei.
texture_mean: Mean standard deviation of gray-scale values.
perimeter_mean: Mean perimeter size.
area_mean: Mean area size of cell nuclei.
smoothness_mean: Mean smoothness of the nuclei, based on local variations in radius lengths.
compactness_mean: Mean compactness, computed as (perimeter² / area - 1.0).
symmetry_mean: Mean symmetry of the cell nuclei.

Project Structure
data/: Contains the dataset file (breast_cancer_data.csv).
notebooks/: Jupyter notebooks for data exploration, preprocessing, and logistic regression modeling.
src/: Scripts for data processing, model training, and evaluation.
README.md: Overview and instructions for the project.
requirements.txt: List of necessary Python packages.

Analysis Workflow

Data Cleaning:

Remove or ignore the ID column, as it does not provide predictive information.
Encode the diagnosis column to binary (1 for malignant, 0 for benign).

Exploratory Data Analysis (EDA):

Examine feature distributions and compare them across malignant and benign diagnoses.
Visualize correlations to understand relationships between features.

Data Preprocessing:

Standardize the numeric features for compatibility with logistic regression.
Split the dataset into training and test sets.

Modeling:

Train a logistic regression model using the training data.
Evaluate the model's performance on the test set using accuracy, precision, recall, and ROC-AUC metrics.