# Employee Attrition Prediction and Analysis

## Authors
- Fathima Khader
- Nishant Singh
- Sujit Kumar Koppula

## Overview
This project focuses on predicting employee attrition using a dataset obtained from Kaggle. The dataset contains various attributes such as age, education level, job role, salary, and satisfaction scores, with the attrition variable indicating whether an employee has left the company or is still employed. The goal is to develop a predictive model that can accurately classify employees into these two categories based on their attributes. This involves exploring different machine learning algorithms, preprocessing the data, and evaluating model performance using metrics like accuracy and F1-score.

## Dataset
The dataset used in this project was collected from Kaggle and can be found [here](https://www.kaggle.com/datasets/patelprashant/employee-attrition). It contains the following columns:
- Age
- BusinessTravel
- DailyRate
- Department
- DistanceFromHome
- Education
- EducationField
- EmployeeCount
- EmployeeNumber
- EnvironmentSatisfaction
- Gender
- HourlyRate
- JobInvolvement
- JobLevel
- JobRole
- JobSatisfaction
- MaritalStatus
- MonthlyIncome
- MonthlyRate
- NumCompaniesWorked
- Over18
- OverTime
- PercentSalaryHike
- PerformanceRating
- RelationshipSatisfaction
- StandardHours
- StockOptionLevel
- TotalWorkingYears
- TrainingTimesLastYear
- WorkLifeBalance
- YearsAtCompany
- YearsInCurrentRole
- YearsSinceLastPromotion
- YearsWithCurrManager
- Attrition (Target Variable)

## Approach
1. **Data Preprocessing**: Handle missing values and encode categorical variables to prepare the dataset for training machine learning models.
2. **Model Selection**: Explore various algorithms such as logistic regression, decision trees, and support vector machines to build the predictive model.
3. **Model Evaluation**: Assess the performance of the models using cross-validation techniques and appropriate evaluation metrics like accuracy and F1-score.
4. **Deployment**: Deploy the selected model to make predictions on new data, enabling organizations to gain insights into factors contributing to employee attrition and potentially take proactive measures to mitigate turnover.

## Files Included
- `employee_attrition_prediction.ipynb`: Jupyter notebook containing code for data preprocessing, model training, and evaluation.
- `README.md`: This file providing an overview of the project, dataset, approach, and files included.
- `requirements.txt`: Text file listing the dependencies required to run the project.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/employee-attrition-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd employee-attrition-prediction
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Open and run the `employee_attrition_prediction.ipynb` notebook using Jupyter or any compatible environment.

## Dependencies
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Acknowledgements
We would like to express our gratitude to Kaggle user Patel Prashant for providing the dataset used in this project.

