**Introduction**

As part of a module on Data analytics we were provided with a subset of data from an animal shelter.This assignment focused on building and evaluating prediction models for a particular problem and dataset.
The problem and data come from an animal shelter concerned with animal welfare and reducing the risk of animal death. The shelter wants to use the data collected about their animals to build a data analytics solution for death risk prediction to help them in their planning towards improving the welfare of the animals they shelter. The shelter collects some data for each animal they take in (columns in the dataset with keyword "intake") and also records the status of each animal when it left the shelter (columns in the dataset with keyword "outcome").
The target variable to predict is a binary variable called **binary_outcome**. For this variable, the value “1” indicates that after intake, the animal outcome was negative, e.g., "death", while the value "0" indicates that the animal outcome was a positive one, e.g., was adopted or returned to the owner.
The dataset we work with is a sample of the data released by this shelter:
https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238
The goal in this homework was to work with the data to build and evaluate prediction models that capture the relationship between the descriptive features and the target feature **binary_outcome**.

The steps and general data techniques learnt were:
- Data cleaning
- Data understanding
- Data preparation
- Feature engineering
- Predictive Modelling
- Model optimisationa and evaluation

Models explored and optimised were:
1. Linear Regression
2. Logistic Regression
3. Random Forests
