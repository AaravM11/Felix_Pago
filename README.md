Project Overview

Enhance fraud and risk prevention for new users in remittance transactions by refining the current rule-based scoring system.

Main Objective

Accurately identify fraudulent transactions based on users’ past transactions and behaviors, increasing acceptance rate (85%) while minimizing losses for Felix.

Important Features

Despite the extensive PCA, the logistic regression model still underperforms with detecting fraud data. We used the optimal probability threshold of 0.911 in determining when to classify as fraud. 

Even after getting the top 35 features, Random Forest still underperforms.

The most important features are
- Amount
- Country location
- Device source

The model correctly catches 31% of frauds (low recall), but of those flagged as fraud, 68% are truly fraud (good precision). Overall, this balance gives an F1 of 0.43, indicating a moderate overall performance.


