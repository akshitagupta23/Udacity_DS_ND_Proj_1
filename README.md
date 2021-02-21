# Udacity_DS_ND_Proj_1
### Predictive Model of Bank Loan Classification

#### Business Problem

Universal bank issues loan to its customers based on customer information known as features.
The bank wants to build a model which can predict if a customer is eligible to grant loan or not. The ROI of this transformation from legacy based decisioning to AI based decisioning is the fast disbursal to the loan along with enhancing the better customer reach.
This analysis is based on the dataset of [Universal Bank](https://www.kaggle.com/sriharipramod/bank-loan-classification). The analysis follows the CRISP-DM process.

The model is built in juypter notebook in python 3. Several Data and ML libraries are used like pandas, numpy , scikit-learn, etc. 
Hyperparameter tunning also known as Evaluation phase of CRISP-DM is done using Random Search CV.
Explaination of Black Box ML model is done using SHAP (SHapley Additive exPlanations).

The Jupyter Notebook Markdown file can be accessed through: [**Udacity_CRISP_DM_Project.ipynb**](https://github.com/akshitagupta23/Udacity_DS_ND_Proj_1/blob/main/Udacity_CRISP_DM_Project.ipynb)

The main question I'm trying to answer is, if salary is a suitable measure to influence ones job satisfaction. I will break down this question into the following three question:

Q1: What is the relationship between JobSatisfaction and Salary?
Q2. What is the relationship between Salary and YearsProgramJob (Experience)?
Q3: What is the relationship between JobSatisfaction and YearsProgramJob (Experience?)
The key findings are, that there is a correlation between salary and job satisfaction, however the causality is not clear. It is not the result of salary increase based over years of job experience.

See also my medium post with some condensed interpretation: https://medium.com/@252.at.work/salary-expericene-and-job-satisfaction-6b2fb974b849?source=friends_link&sk=d05e34a670cf950868ef16f0abad0cf8

The analysis is done in jupyter notebook. The survey data is not included in this repository; you will need to download it from the kaggle link above. You will need the following python packages to run this jupyter notebook successfully. (You can install them via pip install )

Required Python Packages
jupyter==1.0.0
matplotlib==3.2.1
numpy==1.18.2
pandas==1.0.3
seaborn==0.10.0
