# Linear Regression Examples

This repository contains three Jupyter Notebooks demonstrating different linear regression applications:

## Notebooks Overview

### 1. Student Scores Prediction (`linear_regression_student_scores.ipynb`)
- **Task**: Predict student scores based on hours studied
- **Features**: 
  - Single feature: Hours studied
- **Output**: Exam score prediction
- **Technique**: Simple linear regression
- **Equation**: `Score = intercept + coefficient * Hours`

### 2. House Price Prediction (`multiple_regression_house_prices.ipynb`)
- **Task**: Predict house prices based on multiple features
- **Features**:
  - Number of rooms (rm)
  - Age of property (age)
  - Pupil-teacher ratio (ptratio)
- **Output**: Median home value prediction
- **Technique**: Multiple linear regression
- **Equation**: `Price = intercept + coef1*Rooms + coef2*Age + coef3*PTRatio`

### 3. Advertising Sales Prediction (`multiple_regression_advertising_sales.ipynb`)
- **Task**: Predict product sales based on advertising budgets
- **Features**:
  - TV advertising budget
  - Radio advertising budget
  - Newspaper advertising budget
- **Output**: Sales prediction
- **Technique**: Multiple linear regression
- **Equation**: `Sales = intercept + coef1*TV + coef2*Radio + coef3*Newspaper`

## Setup Instructions

1. Create and activate virtual environment:

`python -m venv regression_env
source regression_env/bin/activate  # On Windows: regression_env\Scripts\activate`

2. Install required packages:
`pip install numpy pandas scikit-learn matplotlib jupyter`

3. Run Jupyter Notebook:
`jupyter notebook`

 Open the notebook files from the Jupyter interface

Requirements
Python 3.6+

Libraries:
numpy
pandas
scikit-learn
matplotlib
jupyter
Usage
Run all cells in each notebook sequentially
Examine the model coefficients and intercept
The final equation shows how predictions are calculated
Try modifying the input values to see different predictions

#Expected Output

Each notebook will display:
The regression equation
Model coefficients
For the student scores notebook: a plot of the regression line
For other notebooks: sample predictions vs actual values

`
This README provides:
1. Clear description of each notebook's purpose
2. Setup instructions
3. Requirements
4. Usage guide
5. Expected outputs

You can save this as `README.md` in your project directory. The markdown formatting will render nicely on GitHub or any markdown viewer.`
