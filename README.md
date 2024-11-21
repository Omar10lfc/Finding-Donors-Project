# Finding Donors for CharityML

This project is part of a machine learning initiative to assist CharityML, a fictitious charity organization, in identifying potential donors. The goal is to build a model that predicts whether individuals earn more than $50,000 annually, enabling CharityML to focus its outreach efforts effectively.

## Project Overview

The notebook employs supervised learning techniques and covers the entire machine learning workflow, including:

1. **Exploratory Data Analysis (EDA)**: Understanding the data through summary statistics and visualizations.
2. **Data Preprocessing**: Preparing the dataset for modeling by handling missing values, encoding categorical features, and feature scaling.
3. **Model Selection and Evaluation**: Training multiple supervised learning algorithms and evaluating their performance.
4. **Optimization**: Fine-tuning the best model using grid search and other techniques.
5. **Feature Importance Analysis**: Identifying the most significant predictors of high-income individuals.

## Dataset

The dataset used for this project is the **Census Income Dataset**, which contains the following key attributes:

- Demographic information (age, education, marital status, etc.)
- Occupation-related data
- Income label (`>50K` or `<=50K`)

## Key Highlights

### Exploratory Data Analysis
- Insights into data distribution and potential relationships between features.
- Identification of potential data issues such as imbalanced classes.

### Data Preprocessing
- Handled missing or inconsistent data.
- Applied one-hot encoding for categorical features.
- Normalized numerical features for better model performance.

### Model Selection
- Experimented with various algorithms, including:
  - Decision Trees
  - Support Vector Machines
  - Gradient Boosting Classifiers
- Used accuracy, precision, recall, and F1-score for evaluation.

### Optimization
- Hyperparameter tuning using grid search to maximize model performance.
- Analyzed the impact of different features on model predictions.

### Results
- Achieved a high F1-score and accuracy on the test set.
- Gradient Boosting Classifier was identified as the best-performing model.

## Files in the Repository

- **`finding_donors.ipynb`**: Jupyter Notebook with the complete analysis and model development process.
- **`README.md`**: Overview of the project and instructions.
- **`census.csv`**: Includes the Census Income Dataset.

## Requirements

- Required Libraries:
  - NumPy
  - pandas
  - scikit-learn
  - Matplotlib
  - Seaborn
- Jupyter Notebook or equivalent environment.


## Insights

- The project demonstrates the power of machine learning in identifying potential donors for a charity.

## Credits

This project was completed as part of a machine learning initiative to practice and demonstrate real-world data science and AI techniques.
