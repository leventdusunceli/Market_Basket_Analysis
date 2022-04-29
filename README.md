# Market Basket Analysis Case Study 

Businesses are always looking to optimize their approach in sales to increase revenue.  One of the best ways of increasing the sale of a certain item is bundling it in an attractive offer. In order to create the best type of offer, supermarkets and shops look at the shopping data and try to deduce which items are frequently bought together or which items increase the probability of buying another item.  

In this data science project I used association rule learning methods to deduce a number of conclusions from the supermarket shopping dataset.  

**Business Case:**  A local supermarket wants to learn which items are frequently bought together under different circumstances to optimize their sales approach.  The business has provided me with the dataset containing the contents of each transaction for the last 3 months.  Business owner wants me to provide a set of different item combinations that can be bundled into special deals. 

**Our Approach**:  In order to identify item combinations I’ll build Apriori Learning models for  3 different conditions.  Each of these models will identify the items satisfying the following conditions. 

- Condition 1: Items that are bought together very very frequently.  
- Condition 2: Niche items that raise the probability of buying another item drastically 
- Condition 3: Items that are bought a lot

### Contents 
Market_Basket_Optimisation Notebook
- contains the model building steps for apriori learning algorithm with explanation of the code .  

Results Powerpoint Presentation
- analysis results and more detailed explanation of the rationale behind each condition

Datasets & Raw Data
- main dataset and result dataframes
