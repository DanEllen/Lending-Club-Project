# Lending-Club-Project
In this project I analyzed the public data provided by Lending Club from 2007 to 2019 of loans issued for a value of over US$ 33 Billion. The objective of the project is to help determine if this kind of new asset class could be of interest to an investment fund. 

In order to achieve this objective I will user tools from data science and finance to build the highest performing portfolios of loans possible to then determine if the results we are achieving from said portfolios are adequate for our fund when compared to other asset classes.

Optimizing our portfolios is not a trivial task that required building two models, one for predicting defaults and another to project their internal rate of returns. Several other steps are taken in the process, such as split testing and feature engineering,  to increase the robustness of the models and improve its accuracies.

Objective:
- Tasked by an Investment firm to analyze the possibility of investing in Lending Club loans as part of our portfolio. 


Tasks:
-	Perform EDA to understand dataset.
-	Impute missing data.
-	Select features, removing ones that could lead to data leakage or are unimportant.
-	Train model to predict loan defaults.
-   Estimate cashflows of each loan to be able to calculate IRR for each loan.
-	Calculate IRR based on thresholds of the spread between interest rate and default probability.
-   Create a second model to predict IRR based on default probability from the first model and the other features.
-   Calculate IRR of portfolios of loans composed of different percentile of loans predicted to have the largest IRR.
-	Compare with other investment assets.
-	Conclusions.
