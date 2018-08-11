Project description:

Data science offers banks a set of tools to identify customers most likely to sign-up to financial products, 
in this particular instance term deposits, which reduces the time, resources and costs required to reach and 
convert the highest possible number of customers with fewest number of calls.

Our primary goal was to understand the dataset, track down the most important attributes that have an outsized 
influence on the outcome and then prescribe alternatives that can further improve the success rate for the bank. 
By using basic statistical techniques, graphical representations and Random Forest algorithm, we were successful 
in building a model that can predict with an 89% accuracy, the success rate of this direct marketing campaign.

The dataset used was originally from a paper published by S. Moro, P. Cortez and P. Rita in the following paper: 
[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. 
Decision Support Systems, Elsevier, 62:22-31, June 2014. We accessed this dataset from the UCI Data Repository 
(https://archive.ics.uci.edu/ml/datasets/bank+marketing) where the information has been truncated to include 41,188 
unique rows and 21 attributes. The dataset is primarily a combination of demographics data, campaign operational data 
and economic indicators. The goal of the paper was to use machine learning algorithms to build a model, that can predict 
success or failure when a customer is targeted to open a term deposit account.

Age, Education and Job profile came up as the most important customer attributes that predicted success. In addition, we 
also reviewed economic indicators like Euribor rate, Consumer Confidence Index and Employment rate to further support the 
underlying assumptions. Overall, our suggestion is to not only focus on the most obvious success criteria, but also branch 
out and target underserved groups in order to drastically improve the success of the campaign.
