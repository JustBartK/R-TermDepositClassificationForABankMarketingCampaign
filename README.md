# R-TermDepositClassificationForABankMarketingCampaign

Norbert Lużyński, Dominik Sobczyk, Bartosz Justkowski, Stanisław Cabaj


This project focuses on implying machine learning techniques, particularly logistic regression, neural networks, decision trees, and random forests, to analyse a dataset related to the marketing campaign of a Portuguese banking institution during the 2008-2010, time marked by a significant financial crisis. The primary objective is to predict whether a client will open a term deposit, indicated by the binary variable ‘y’ (yes or no).

The dataset contains various input variables, including clients’ personal data, details of the last contact during the campaign, and social and economic context attributes. The data cleaning process involves handling missing values, what is quite a challenging task as the dataset lacks NaN values but contains ‘unknown’ values. Furthermore, given the presence of character values, the creation of dummy variables is necessary for some algorithms. Due to the fact that our dataset is imbalanced, it is recommended to perform upsampling or downsampling.

The analysis involves implementing different machine learning models and assessing their performance based on key metrics such as accuracy, sensitivity, and AUC (area under the curve). Logistic regression, neural networks, decision trees, and random forests are explored, with a focus on finding the most suitable model for predicting term deposit subscriptions.

The project reveals that economic parameters play a significant role in predicting deposit subscriptions, alongside influential variables like age and education. Results indicate that the decision tree model, after hyperparameter tuning, outperforms other models in term of AUC=74,81%. The decision tree is identified as the most suitable model for this dataset, considering the project's primary goal and the trade-offs between marketing costs and the identification of potential clients. The study provides valuable insights into the effectiveness of machine learning models in predicting term deposit subscriptions during a challenging economic period.

For more detailed information please take a look at the .pdf file, for R code please take a look at the .rmd file.
