# This Repository is for the model training and assignments of Responsible And Explainable AI

## Dataset

I used the **Bank Account Fraud (BAF) dataset** from Kaggle. It comes from a
NeurIPS 2022 paper by Jesus et al. Each row is one bank account application
and the goal is to predict if the application is fraud (`fraud_bool` = 1) or
not (0).

- Link: https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022
- File used: `Base.csv`
- Size: 1,000,000 rows and 32 columns
- Only about 1.1% of the applications are fraud

I picked this dataset because it is large and the authors made it for studying
fairness. The data is synthetic, so no real person's information is in it.
The dataset is not uploaded here because the file is too big for GitHub. To run
my code, download `Base.csv` from the link and put it in a folder named `data`.