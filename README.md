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
- [Cleaned data and Get Dummies](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/01_Clean_GetDummies.ipynb)
- [Used Logistic Regression to explore the data and create a benchmark model](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/03_Logistic_Reg_Explore.ipynb)
- [Address class imbalance](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/03_Logistic_Reg_ClassImbalance.ipynb)
  - The class imbalance for this project was just on the edge of potentially being problematic. Problems typically show up when a single class represents 80% or more of data. In this case, one class represented 72% of the data. 
  -  I made the decision to address the class imbalance to gain experience in thinking through the workflow and utilizing imblearn. 

#### Tested More Models
- [Decision Trees, Random Forest and XGBoost](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/04_Tree_vs_Forest_vs_LogReg.ipynb)

#### Tuned Hyperparamters
- [Tune hyperparameters using Gridsearch](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/05_Tuning_GridSearch.ipynb)

#### Determine Winner
- Best performing model
- Most important features

#### Identify Further Optimizations
- Identify further tuning opportunities

# Findings
Check out the [presentation](https://github.com/Jenni-Hawk/Customer_Churn/blob/main/CustomerChurn_Presentation.pdf)

# Tech Tools Used
- Pandas
- Sklearn
- Imblearn
- Numpy
