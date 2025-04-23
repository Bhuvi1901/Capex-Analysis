# CapEx Planning and Resource Allocation Analysis

## Overview

Analyzed capital project spending data to predict budget variance. The project aims to enhance financial planning and resource allocation in capital-intensive projects.

## Project Structure

### 1. Data Loading and Cleaning
- Imported capital expenditure datasets containing planned vs actual costs for various projects.
- Handled missing values, dropped irrelevant features, and standardized column formats for analysis.

### 2. Exploratory Analysis
- Generated plots to compare planned and actual costs, highlighting variance trends across departments.
- Correlation matrices were used to identify cost drivers and variance predictors.

### 3. Feature Engineering
- Created new features such as cost ratio, time deviation, and project complexity score to explain cost overruns better.
- Performed feature selection using mutual information and Random Forest importance.

### 4. Model Development
- Trained XGBoost and Linear Regression models to predict cost variance (numerical target).
- The XGBoost regressor was fine-tuned using grid search, achieving strong R² scores and low MAE.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

## Output

The XGBoost regression model achieved a mean absolute error of 6,103 and an R² score of 0.93, indicating strong predictive capability and high accuracy in forecasting project cost overruns.

## How to Use

- ### Clone this repository:
  ```bash
  git clone [https://github.com/Bhuvi1901/Capex-Analysis](https://github.com/Bhuvi1901/Capex-Analysis)
  ```
- ### Navigate to the project folder:
  ```bash
  cd Capex-Analysis
  ```
- ### Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- ### Run the Jupyter Notebook to execute the workflow.

## Future Improvements

- Incorporate metadata like project location or type to refine predictions.
- Develop forecasting modules and visual dashboards for real-time budget tracking.

