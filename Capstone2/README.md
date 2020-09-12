The Problem:
Can I use a data set from the fictional telecommunications company Telco to predict customer churn?  If so, can I identify which features have the greatest predictive power in identifying those customers who will leave?

The Why: 
As the author and speaker, Jeffery Gitomer, states in the title of his book, “Customer Satisfaction Is Worthless, Customer Loyalty Is Priceless”, having customers that stick with your company is extremely important. That is why it is of great value to a business to be able to identify those customers who will potentially leave the business and why. 

For Telco specifically, here is why it matters. The customers who left spent a total of $139,130.85/month with an average of $74.44/month per customer. The customers who are still with Telco spend $316,985.75/month with an average of $61.27/month per customer. This is a 30.5% per month loss due to customer churn! Our best model was able to predict 79% of the customers who would leave. If just half of the 79% the model predicted to leave Telco were convinced to stay, then that would be a savings of $54,956.68/month. This would reduce the per month loss to 18.5%!

The Solution:
After cleaning the data set and conducting extensive exploratory data analysis (EDA) I was able to train a logistic regression model in conjunction with the SMOTE oversampling technique that had an overall accuracy of 0.75 and a recall score on the target feature of 0.79. 

If you are interested in understanding more of the discovery process that led to this model and the rejection of many others, please peruse these notebooks. I suggest the order given, but each notebook should be able to stand on its own as well.

1.0_Capstone2_cleaningdata
2.0_Capstone2_EDA
2.1_Capstone2_featureselection
3.0_Capstone2_LogisticRegression_initialassessment
3.1_Capstone2_LogisticRegression_imbalanceddata
3.2_Capstone2_randomforest
3.3_Capstone2_LogReg_and_RFC_usingselectedfeatures
4.0_Capstone2_furtherexploration_year1model

This introduction is part of a larger report telling the story of my search to identify the customers who left Telco. This larger report is in the file “Capstone2_Final_Report”.

