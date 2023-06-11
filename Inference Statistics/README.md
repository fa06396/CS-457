# Inference Statistics Project

This project focuses on performing hypothesis testing using Python to explore data and draw statistical inferences. The goal is to use hypothesis testing methods to answer specific questions and provide insights and justifications for the decision made based on the statistical analysis.

## Project Overview

The main objective of this project is to conduct hypothesis testing on the "EmployeeAttrition.csv" dataset. By leveraging Python and hypothesis testing techniques, we aim to answer specific questions and draw conclusions based on statistical evidence.

### Dataset Description

The "EmployeeAttrition.csv" dataset is provided as the input for this project. It contains information about employees, including attributes such as MonthlyIncome, WorkLifeBalance, YearsAtCompany, EnvironmentalSatisfaction, JobRole, Department, and Gender. We will utilize this dataset to perform hypothesis testing and explore relationships between variables.

### Project Tasks

The project can be divided into the following tasks:

1. Hypothesis formulation: For each question, we will start by formulating the null and alternative hypotheses. The hypotheses will be designed to address the specific comparisons, such as differences in MonthlyIncome between genders or associations between Department and Gender.

2. Hypothesis testing: Using appropriate statistical tests, we will perform hypothesis testing to evaluate the evidence against the null hypothesis and make informed decisions. We will utilize Python libraries such as SciPy or StatsModels to conduct the necessary statistical tests.

3. Results interpretation: Based on the hypothesis testing results, we will interpret the statistical evidence and draw conclusions for each question. We will provide justifications for our decisions, considering factors such as p-values, confidence intervals, effect sizes, and any relevant domain knowledge.

### Questions and Hypotheses

1. MonthlyIncome: Is the MonthlyIncome of males greater than females?
   - Null Hypothesis (H0): MonthlyIncome of Males is equal to Females
   - Alternative Hypothesis (H1): MonthlyIncome of Males is greater than Females

2. WorkLifeBalance: Is the WorkLifeBalance of males less than females?
   - Null Hypothesis (H0): WorkLifeBalance of Males is similar to Females
   - Alternative Hypothesis (H1): WorkLifeBalance of Males is less than Female

3. YearsAtCompany: Is the YearsAtCompany of single employees less than married employees?
   - Null Hypothesis (H0): The mean YearsAtCompany of single employees is similar to Married employees
   - Alternative Hypothesis (H1): The mean YearsAtCompany of single employees is less than the mean YearsAtCompany of married employees.

4. EnvironmentalSatisfaction: Is the EnvironmentalSatisfaction of employees with attrition (Attrition = Yes) less than employees without attrition (Attrition = No)?
   - Null Hypothesis (H0): The mean EnvironmentalSatisfaction of employees with attrition is equal to the mean EnvironmentalSatisfaction of employees without attrition.
   - Alternative Hypothesis (H1): The mean EnvironmentalSatisfaction of employees with attrition is less than the mean EnvironmentalSatisfaction of employees without attrition.

5. MonthlyIncome: Is the MonthlyIncome of managers greater than laboratory technicians?
   - Null Hypothesis (H0): The mean MonthlyIncome of managers is equal to the mean MonthlyIncome of laboratory technicians.
   - Alternative Hypothesis (H1): The mean MonthlyIncome of managers is greater than the mean MonthlyIncome of laboratory technicians.

6. Department and Gender association: Is there any association between the Department and Gender?
   - Null Hypothesis (H0): There is no association between the Department and Gender.
   - Alternative Hypothesis (H1): There is an association between the Department and Gender.
