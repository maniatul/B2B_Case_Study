# B2B_Case_Study

# Problem Statement:
Schuster is a multinational retail company dealing in sports goods and accessories. Schuster conducts significant business with hundreds of its vendors, with whom it has credit arrangements. Unfortunately, not all vendors respect credit terms and some of them tend to make payments late. Schuster levies heavy late payment fees, although this procedure is not beneficial to either party in a long-term business relationship. The company has some employees who keep chasing vendors to get the payment on time; this procedure nevertheless also results in non-value-added activities, loss of time and financial impact. Schuster would thus try to understand its customers’ payment behaviour and predict the likelihood of late payments against open invoices.



To understand how to approach this problem using data science, let’s first understand the payment process at Schuster now. Every time a transaction of goods takes place with a vendor, the accounting team raises an invoice and shares it with the vendor. This invoice contains the details of the goods, the invoice value, the creation date and the payment due date based on the credit terms as per the contract. Business with these vendors occurs quite frequently. Hence, there are always multiple invoices associated with each vendor at any given time.

# Goal 
Schuster would like to better understand the customers’ payment behaviour based on their past payment patterns (customer segmentation).
Using historical information, it wants to be able to predict the likelihood of delayed payment against open invoices from its customers.
It wants to use this information so that collectors can prioritise their work in following up with customers beforehand to get the payments on time.

# Solution Approach:

For this case study we're going to use logistic regression model to predict whether the customer is going to delay the payment or not.

The steps involved for this case study are mentioned below:

Data Loading
Data Exploration and pre-preprocessing which will include following steps: a. Missing value handling b. Outlier handling c. Feature engineering
Model Building using statsmodel and VIF
Model Performance Evaluation using Probability Calibration, ROC Curve, Precision-Recall Curve
Final recommendation.

# Files Submitted:
 
README file for information
Python commented file: Juputer Notebook.
Presentation: Present the analysis. (PDF format)
