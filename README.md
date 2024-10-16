# financial-fraud-detection

In this competition, we will detect online fraudulent transactions using machine learning techniques. Our objective is to implement a solution that comes under the top 5% in Kaggle leaderboard which is not an easy task. IEEE-CIS Fraud Detection is a Kaggle competition organized by the IEEE Computational Intelligence Society. Vesta Corporation who is one of the forerunners in guaranteed e-commerce payment solutions provided the dataset for this competition.

Business Objective
The main business objective of finding fraud transactions can be following:

If a fraud transaction is found out, the company should immediately block that card.
We should be able to predict the probability of fraud transaction
We should not predict fraud transactions as nonfraud. Also the vice versa. So precision and recall should be taken care of.
Approach
Do exploratory data analysis on each and every column and understand the impact of each feature.
Build a baseline model.
Create new features and see whether those features improve the performance of the model. If yes retain the features or else drop those features. I used forward feature selection for that.
Iteratively continue this approach until we get a good score.
Results
After creating some baseline models we stick up with xgboost as it was giving better perfomance. We did several feature engineering and feature selection and ultimatly end up with a solution which is top 3.5% in kaggle leaderboard.

The progress of project is as follows:
![result](https://github.com/user-attachments/assets/a5b736d7-4526-45da-96aa-0e4bd0ac26a6)
