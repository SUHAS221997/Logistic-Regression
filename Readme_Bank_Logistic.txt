Logistic Regression Analysis
This project uses logistic regression to analyze and predict outcomes in a banking dataset with demographic, socio-economic, and campaign-related features.
The primary objective is to predict the target variable (y) based on the other features in the dataset.

Dataset Overview
The dataset contains 41,199 entries and 21 columns, including demographic and financial information, as well as historical campaign data. Below is a summary of each column:

Logistic Regression Analysis on Banking Dataset
This project involves using logistic regression to analyze and predict customer behavior based on a banking dataset. The goal is to predict whether a client will subscribe to a term deposit (y), based on their demographic, socio-economic, and past interaction data.

Dataset Overview
The dataset contains 41,199 entries with 21 columns, each representing a feature related to the clients or the bank's campaign. The data has been cleaned to remove missing values, ensuring a complete dataset for analysis.

Features
Demographic Attributes: Includes age, job type, marital status, and education level, which provide insight into the client's profile.

Financial Status: Variables such as default, housing, and loan indicate the client’s financial background and existing commitments.

Last Contact Information: Columns such as contact, month, day_of_week, and duration detail the last contact made with the client, including the communication type and duration of the last call.

Campaign Information: Columns like campaign, pdays, previous, and poutcome capture information about previous and current campaign interactions.

Economic Indicators: The dataset includes broader economic indicators like emp.var.rate, cons.price.idx, cons.conf.idx, euribor3m, and nr.employed, which help understand the external environment during the campaigns.

Target Variable: y is the outcome variable, indicating whether a client subscribed to a term deposit ("yes" or "no").

Analysis Workflow

Data Cleaning: The dataset is cleaned to remove any null values, ensuring it is ready for analysis without further preprocessing for missing data.

Exploratory Data Analysis (EDA): Visualizations and statistical analyses are used to explore distributions, correlations, and patterns in the data, aiding in feature selection and understanding.

Data Preprocessing:

Categorical variables are encoded to be compatible with logistic regression.
Numerical features are scaled for optimal model performance.

Modeling:

The cleaned dataset is split into training and testing sets.
Logistic regression models are trained to predict the target variable (y).
Model performance is evaluated using accuracy, precision, recall, and AUC scores.