# Employee Salary Prediction Model

This project aims to build a machine learning regression model to predict the salary of newly hired employees at TechWorks Consulting. The goal is to make data-driven, fair compensation decisions using a variety of employee-related features.

## Project Overview

TechWorks Consulting specializes in providing IT talent to businesses, with a focus on placing top candidates in positions quickly and efficiently. One critical aspect of their hiring process is determining fair and competitive salary offers for new hires based on multiple factors.

This project utilizes historical employee data to predict future salaries, considering factors like:
- **College Tier**: Tier 1, Tier 2, or Tier 3 colleges
- **City Type**: Metro or Non-metro
- **Role**: Manager or Executive
- **Previous CTC**
- **Previous Job Changes**
- **Graduation Marks**
- **Experience in Months**

## Project Pipeline

1. **Data Preprocessing**:
   - Handling missing values and outliers.
   - Converting categorical data to numerical values (e.g., Tier, City).
   - One-hot encoding for categorical fields like "Role".
   
2. **Exploratory Data Analysis (EDA)**:
   - Understanding the data distribution.
   - Identifying key features and correlations.

3. **Model Selection**:
   - Training multiple regression models (e.g., Linear Regression, Decision Tree, Random Forest, etc.).
   - Evaluating model performance using metrics like Mean Squared Error (MSE) and R-squared.

4. **Model Optimization**:
   - Feature scaling and selection.
   - Hyperparameter tuning to improve model accuracy.

5. **Model Evaluation**:
   - Selecting the best-performing model.
   - Discussing why the model performed better and possible improvements.

