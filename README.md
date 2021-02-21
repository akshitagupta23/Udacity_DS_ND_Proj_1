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

Following are the `questions` I tried to answer from the model:

- Q1: What are the distributions of the data? Is there some deviation from the Normal distribution?
- Q2. Is the data being balanced, if not then what implication it can levy on Business decision?
- Q3: Which features are responsible for customer to get a Loan or Not.

Some of the key findings are:
- `Income` and `Mortgage` columns are skewed and have kurtosis, hence logarithm of these columns transformed to Normal Distribution 
- From the statistics summary of data we observed that Experience column has some negative values, also we checked the correlation between Age and Experience and found that they are highly corrleated hence dropped the Experience column
- From `SHAP` for expalaining the decision it was observed that `Income`, `CCAvg` and `Education` are the most important features while `Age` & `Securities Account` being the least

Also in detail answers to above questions can be found at blog post [Loan Grant: A conundrum explained by XAI](https://medium.com/@akshi.gupta23/loan-grant-a-conundrum-explained-by-xai-e476d11e640e)


### References
- [**CRISP-DM**](https://www.sv-europe.com/crisp-dm-methodology/)

