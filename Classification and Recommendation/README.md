# Classification and Recommendation System

This project aims to demonstrate the understanding and application of classification techniques for prediction and recommendation. We will use the "CreditCardData.csv" dataset for classification analysis and the "mcdonalds.csv" dataset for recommendation analysis.

## Project Overview

The main objective of this project is to apply classification techniques to predict credit card approval status using the "CreditCardData.csv" dataset. Additionally, we will build a decision tree-based recommendation system using the "mcdonalds.csv" dataset to recommend similar food items based on their attributes.

### Dataset Description

1. "CreditCardData.csv": This dataset contains information related to credit card applications. It includes various attributes such as income, age, education, marital status, and others. The goal is to predict the approval status of credit card applications.

2. "mcdonalds.csv": This dataset contains information about McDonald's menu items and their attributes. It includes attributes such as category, item, calories, carbohydrates, fat, and others. The goal is to build a decision tree-based recommendation system to suggest similar food items based on their attributes.

### Project Tasks

The project can be divided into two main tasks: classification using the "CreditCardData.csv" dataset and recommendation using the "mcdonalds.csv" dataset.

#### Classification using CreditCardData.csv

1. Data cleaning:
   - Remove all rows that have missing values in any column.
   - Replace the "Approved" column values from -/+ to 0/1 or No/Yes based on your preference.

2. Train and test set split:
   - Create a train and test set after cleaning the data.
   - Use 30% (0.3) of the records for the test set.
   - Set the seed after reading the data to ensure consistent calculations throughout the analysis.

3. Decision Tree classification model:
   - Create a classification model to predict the approval status using the Decision Tree algorithm.
   - Interpret the decision tree and discuss the importance of attributes.
   - Perform Tree Pruning Analysis and compare the results before and after pruning.

4. RandomForest classification model:
   - Create a classification model to predict the approval status using the RandomForest algorithm.
   - Perform variable importance plot analysis.
   - Try at least 5 different values of n_estimators (number of trees) and compare the classification error.
   - Select the best model (based on n_estimators) for the final comparison.

5. Comparison of Decision Tree and RandomForest:
   - Report the comparison between Decision Tree and RandomForest in terms of classification performance.

#### Recommendation using mcdonalds.csv

1. Decision Tree-based recommendation system:
   - Build a decision tree to recommend similar food items based on their attributes using the "mcdonalds.csv" dataset.
   - Interpret the decision tree and provide interesting insights.
   - Select three similar food items of your choice and explain/interpret the recommendations.
