Bank Campaign Subscriptions Prediction

0. Introduction
This is the extendede work of Georgios Spyrou, In this project it is to analyze a dataset containing information about marketing campaigns that were conducted via phone calls from a Portuguese banking institution to their clients. Purpose of these campaigns is to prompt their clients to subscribe for a specific financial product of the bank (term deposit). After each call was conducted, the client had to inform the institution about their intention of either subscribing to the product (indicating a successful campaign) or not (unsucessful campaign).

1. Dataset Description
The dataset has 41188 rows (instances of calls to clients) and 21 columns (variables) which are describing certain aspects of the call. Please note that there are cases where the same client was contacted multiple times - something that practically doesn't affect the analysis as each call will be considered independent from another even if the client is the same.

Dataset description link: 
https://www.kaggle.com/pankajbhowmik/bank-marketing-campaign-subscriptions


Proposed Approach: 
EDA, Data Preprocessing, PCA, Random Forest Classifier, XGboost, Model Evaluation Metrics, CM, ROC, AUC, Model Comparision