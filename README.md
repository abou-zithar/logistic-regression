# logistic-regression
## Employee Retention Analysis - HR Analytics
This README file explains the Python code that performs employee retention analysis using HR Analytics data downloaded from Kaggle. The code covers data exploration, visualization, and building a predictive model to analyze factors that influence employee retention.

## Dataset
The dataset used for analysis is obtained from Kaggle. It includes various features related to employee performance, satisfaction, and demographics.

## Code Overview
The code is structured into the following sections:

## Data Loading and Exploration
The code first imports necessary libraries, reads the dataset using pandas, and displays the initial rows of the dataset. It also calculates the number of employees who left and who were retained.

## Data Visualization
The code calculates and visualizes average values for various features based on whether an employee left or not. It draws insights about satisfaction level, average monthly hours, and promotion status concerning employee retention.

It also explores the impact of salary and department on employee retention using bar charts.

## Feature Selection
Based on the exploratory analysis, the code selects specific features (satisfaction level, average monthly hours, promotion status, and salary) as independent variables for further analysis.

## Data Preprocessing
The salary feature is converted into dummy variables using one-hot encoding to make it compatible with the model. The code then drops the original salary column and retains only the encoded columns.

## Model Building and Evaluation
The code splits the data into training and testing sets using the train_test_split function. A logistic regression model is trained on the training data and evaluated on the testing data. The model's accuracy is calculated using the model.score() method.

## Conclusion
This README provides a summary of the employee retention analysis using HR Analytics data. By analyzing various features and building a predictive model, the code aims to understand the factors that influence employee retention within the organization. The provided insights can help HR departments make informed decisions to improve employee satisfaction and reduce turnover.
