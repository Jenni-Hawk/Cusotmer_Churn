# Customer_Churn
Classification modeling project to predict churn

# Client / Background
- Connex is a fictitous communications company that provides phone, internet, and streaming services. In addition, they offer supportive services like online security, device protection, etc. 

- Connex would like to utilize machine learning methodologies to create a model that gives them the ability to get ahead of customer churn.

# Business Questions
- What model can best predict churn?
- Which features (inputs) are more likely to predict churn?

# Data to Answer the Question
- 7032 Observations (rows)
- 30 Features (columns)
- [Kaggle dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) 

# Solution Path
#### EDA + Benchmark
- [Used Logistic Regression to explore the data and create a benchmark model](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/03_Logistic_Reg_ClassImbalanceWork.ipynb)
- Evalute key metrics
- [Address class imbalance](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/03_Logistic_Reg_ClassImbalanceWork.ipynb)

#### Test More Models
- [Decision Trees, Random Forest and XGBoost](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/04_Tree_vs_Forest_vs_LogReg.ipynb)
- [Tune hyperparameters using Gridsearch](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/05_Tuning_GridSearch.ipynb)

#### Determine Winner
- Best performing model
- Most important features

#### Identify Further Optimizations
- Identify further tuning opportunities
- Explore other ideas

# Findings
Check out the [presentation](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/CustomerChurn_Presentation.pdf)

# Tech Tools Used
- Pandas
- Sklearn
- Imblearn
- Numpy
