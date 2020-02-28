# ChurnPrediction To Be Continue

It is a customer churn prediction project. It can be divided into two parts.
1.	Customer's time series data was analyzed to find out the user_ids which were considered have churned their service from the equity_value_data, those user_ids were used as the label of the features_data
2.	The features_data and the label gotten from part 1 were analyzed and trained to several machine learning models. The best AUC was about 0.63.
Unlike the appendence or upselling behavior of customers, the churn behavior was sometimes very hard to be predicted since the dataset may miss the key feature of customers why they churned their services. I will try the augmentation of data features by adding some linear/non-linear combinations of the given features.
