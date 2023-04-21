# Medical Premium Project

This repository contains an analysis of medical premium data, including Exploratory Data Analysis (EDA) and the implementation of a linear regression model. The goal of this project is to understand the factors affecting medical premium prices and to build a predictive model for premium prices based on the available features.

## Data

The dataset contains the following features:

- Age
- Diabetes (presence of diabetes)
- BloodPressureProblems (presence of blood pressure problems)
- AnyTransplants (presence of any transplants)
- AnyChronicDiseases (presence of any chronic diseases)
- Height
- Weight
- KnownAllergies (presence of known allergies)
- HistoryOfCancerInFamily (presence of cancer history in the family)
- NumberOfMajorSurgeries (number of major surgeries)

The target variable is PremiumPrice, which represents the medical premium price.

## Exploratory Data Analysis

The EDA process includes:

- Loading the dataset into a pandas DataFrame
- Checking the shape of the dataset
- Investigating missing values and dropping rows with missing values
- Computing summary statistics
- Visualizing the distribution of PremiumPrice using a histogram
- Visualizing the relationships between features and PremiumPrice using pair plots and a heatmap of the correlation matrix
- Grouping data by age and visualizing the distribution of PremiumPrice within age groups using box plots

## Linear Regression Model

After the EDA process, a linear regression model is built using the cleaned and preprocessed data. The process includes:

- Dropping the 'AgeGroup' column created during EDA
- Encoding categorical variables using one-hot encoding
- Splitting the data into training and testing sets
- Fitting a linear regression model to the training data
- Evaluating the model on the test set
- Printing the coefficients of the linear regression model

## Repository Structure

- Medicalpremium.csv: The dataset containing medical premium information
- medical_premium_analysis.ipynb: Jupyter notebook containing the EDA, data preprocessing, and linear regression model implementation
- README.md: A brief overview of the project and its components

## Usage

To run the analysis, you will need Python 3 and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Clone the repository and open the medical_premium_analysis.ipynb notebook in Jupyter to view and run the analysis.
