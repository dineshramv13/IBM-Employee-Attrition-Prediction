

# Employee Attrition Prediction

## Overview
This project aims to predict employee attrition using machine learning techniques. Employee attrition refers to the phenomenon of employees leaving an organization, which can have significant implications for businesses. By analyzing various factors related to employees, such as demographics, job satisfaction, and work-life balance, the goal is to develop models that can predict the likelihood of an employee leaving the company.

## Dataset
The dataset used in this project is the IBM HR Analytics Employee Attrition & Performance dataset, which contains information about employees' demographics, job roles, and satisfaction levels, among other attributes. The dataset can be found in the file `WA_Fn-UseC_-HR-Employee-Attrition.csv`.


## Instructions for Running the Code
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/dineshramv13/IBM-Employee-Attrition-Prediction.git
   ```

2. Install the required Python packages using pip:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook `IBM_HR_ANALYSIS.ipynb` to execute the code step-by-step. Make sure to have Jupyter Notebook installed.
4. Follow the instructions within the notebook to load the dataset, analyze the data, preprocess it, develop machine learning models, evaluate their performance, and perform hyperparameter tuning.

## Additional Information
- This project utilizes various machine learning algorithms, including Logistic Regression, Random Forest Classifier, K Neighbors Classifier, and Naive Bayes, to predict employee attrition.
- The dataset is preprocessed to handle missing values, encode categorical variables, and scale numerical features.
- Model evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the performance of the models.
- Hyperparameter tuning is performed using GridSearchCV to optimize model parameters and improve predictive accuracy.



