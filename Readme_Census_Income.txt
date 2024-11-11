Census Income Dataset for Logistic Regression

Overview:
This dataset is used for predicting whether an individual earns more than $50K/year based on demographic attributes. It is a binary classification problem where the goal is to predict the income level of an individual based on features such as age, education, marital status, occupation, and more.
The dataset is typically used for training machine learning models, specifically logistic regression in this case, to predict binary outcomes (high income vs. low income).

Dataset Description
Features:
The dataset contains a variety of demographic and employment-related features. Each record represents an individual with the following columns:
1.	Age: Continuous. The person's age in years.
2.	Workclass: Categorical. The type of employment (e.g., Private, Self-emp-not-inc, etc.).
3.	fnlwgt: Continuous. The "final weight" is a value that represents the number of people the census record represents.
4.	Education: Categorical. Highest level of education (e.g., Bachelors, Masters, Doctorate).
5.	Education-Num: Continuous. The number of years of education.
6.	Marital-Status: Categorical. The marital status (e.g., Married-civ-spouse, Never-married).
7.	Occupation: Categorical. Occupation (e.g., Tech-support, Craft-repair, etc.).
8.	Relationship: Categorical. The individual's relationship status (e.g., Husband, Not-in-family).
9.	Race: Categorical. The individual's race (e.g., White, Black, Asian-Pac-Islander).
10.	Sex: Categorical. Gender of the individual (Male, Female).
11.	Capital-Gain: Continuous. Capital gains for the individual.
12.	Capital-Loss: Continuous. Capital losses for the individual.
13.	Hours-per-week: Continuous. The number of hours worked per week.
14.	Native-Country: Categorical. The country of origin (e.g., United-States, Mexico, etc.).

Target Variable:
•	Income: Binary target variable indicating whether the individual’s income is greater than $50K per year.
o	<=50K: Income is less than or equal to $50K.
o	>50K: Income is greater than $50K.

Objective:
The objective of this dataset is to predict the binary outcome (whether an individual earns >50K) based on demographic and employment features using a logistic regression model.

