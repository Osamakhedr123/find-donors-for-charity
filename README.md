# Finding Donors for CharityML Project

## Overview
This project utilizes various supervised machine learning algorithms to predict individuals' income levels using data from the 1994 U.S. Census. The goal is to identify potential donors for a charity by determining if an individual earns more than $50,000 per year. This task is crucial for non-profit organizations as it helps tailor their fundraising strategies more effectively.

## Repository Contents
- **Jupyter Notebook:** Detailed implementation of machine learning models.
- **Data File:** `census.csv` - Modified census dataset with relevant features for income prediction.
- **Visualization Scripts:** Contains custom visualization codes for data analysis.

## Steps in the Analysis
1. **Data Preprocessing:** Handling skewed features, normalizing numerical features, and encoding categorical variables.
2. **Model Selection and Evaluation:** Testing various algorithms to find the most effective model.
3. **Model Optimization:** Using GridSearchCV to fine-tune the best model.
4. **Feature Importance Analysis:** Identifying key features that impact income prediction.

## Libraries and Tools Used
- `pandas`, `numpy`: Data manipulation and numerical operations.
- `matplotlib`, `seaborn`: Data visualization.
- `sklearn`: Machine learning algorithms, data preprocessing, and model evaluation.

## How to Run the Notebook
Ensure Python and necessary libraries are installed. Download the dataset and run the Jupyter Notebook to replicate the analysis and view the predictions.

## Results
The project concludes with a model that can predict with high accuracy whether an individual's income exceeds $50,000. This model helps in understanding the factors influencing higher incomes and aids non-profits in targeting potential donors effectively.
