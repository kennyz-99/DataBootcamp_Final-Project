# DataBootcamp_Final-Project: Profit-Driven Customer Targeting for iFood
This repository demonstrates how to turn a loss-making pilot marketing campaign into a profitable, data-driven strategy. Using a real iFood dataset of 2,240 customers (15% response rate), we first explored key drivers of campaign success—identifying “lapsed but loyal” customers with high historical spend, frequent purchases, and past campaign engagement.

Next, we trained and compared five classifiers (Logistic Regression, k-NN, Decision Tree, Random Forest, and XGBoost), ultimately selecting XGBoost (ROC-AUC ≈ 0.99) for its superior ranking performance. We then translated model scores into business decisions via gain/lift curves and profit-threshold analysis, showing that contacting just 340 customers (≈15% of the base) would flip a –3.046 MU loss into a +2.54 MU profit. Finally, we profile the top 340 targets and outline suggestions on further investigation.

Data_url: https://www.kaggle.com/datasets/jackdaoud/marketing-data/data







