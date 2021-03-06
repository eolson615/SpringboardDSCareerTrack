## The Project
This folder contains a project that I came up with independently to satisfy the requirements of Springboard's Capstone 2 project requirements. For this project, I wanted to solve a very common business issue. The contents of this folder contain the process and results of that endeavor. Enjoy!

## The Problem: 
Can I use a data set from the fictional telecommunications company Telco to predict customer churn?  If so, can I identify which features have the greatest predictive power in identifying those customers who will leave?

## The Why: 
As the author and speaker, Jeffery Gitomer, states in the title of his book, “Customer Satisfaction Is Worthless, Customer Loyalty Is Priceless”, having customers that stick with your company is extremely important. That is why it is of great value to a business to be able to identify those customers who will potentially leave the business and why. 

For Telco specifically, here is why it matters. The customers who left spent a total of $139,130.85/month with an average of $74.44/month per customer. The customers who are still with Telco spend $316,985.75/month with an average of $61.27/month per customer. This is a 30.5% per month loss due to customer churn! Our best model was able to predict 79% of the customers who would leave. If just half of the 79% the model predicted to leave Telco were convinced to stay, then that would be a savings of $54,956.68/month. This would reduce the per month loss to 18.5%!

## The Solution:
After cleaning the data set and conducting extensive exploratory data analysis (EDA) I was able to train a logistic regression model in conjunction with the SMOTE oversampling technique that had an overall accuracy of 0.75 and a 'Yes' recall score on the target class of 0.79. 

If you are interested in understanding more of the discovery process that led to this model and the rejection of many others, please peruse these notebooks. I suggest the order given, but each notebook should be able to stand on its own as well.

[1.0_Capstone2_cleaningdata](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/1.0_Capstone2_cleaningdata.ipynb)  
[2.0_Capstone2_EDA](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/2.0_Capstone2_EDA.ipynb)  
[2.1_Capstone2_featureselection](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/2.1_Capstone2_featureselection.ipynb)  
[3.0_Capstone2_LogisticRegression_initialassessment](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/3.0_Capstone2_LogisticRegression_initialassessment.ipynb)  
[3.1_Capstone2_LogisticRegression_imbalanceddata](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/3.1_Capstone2_LogisticRegression_imbalanceddata.ipynb)  
[3.2_Capstone2_randomforest](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/3.2_Capstone2_randomforest.ipynb)  
[3.3_Capstone2_LogReg_and_RFC_usingselectedfeatures](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/3.3_Capstone2_LogReg_and_RFC_usingselectedfeatures.ipynb)  
[4.0_Capstone2_furtherexploration_year1model](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Coding/4.0_Capstone2_furtherexploration_year1model.ipynb)  

## The Take Away:
- Look into the reason **customers are leaving within the first 12 months** of being with Telco.
- Look into why so many **Fiber Optic customers are leaving**
- Look into why the **customers who purchase internet but do not buy any of the extra services** are leaving as compared to the customers who are purchasing the extra internet services (also the price point for the extra services might be below other providers in the area, hence high customer loyalty).
- Look into the **month-to-month payment option** as 43% of those customers ended up leaving.

## The Whole Story:
This introduction is part of a larger report telling the story of my search to identify the customers who left Telco. This larger report is in the file [Capstone2_Final_Report](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Capstone2_Final_Report.pdf). I have also created a slide deck which could be presented to Telco managment or C-suite executives. It can be found in the file [Capstone2_Presentation](https://github.com/eolson615/SpringboardDSCareerTrack/blob/master/Capstone2/Capstone2_Presentation.pptx).

