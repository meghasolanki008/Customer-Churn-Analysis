# Customer Churn Analysis Report
# Table of contents
- [Underlying Business Problem](#probelem)
- [Data Summary](#summary)
-  [Skills used And Approach](#approach)
-  [Dashboard](#dashboard)
-  [Findings](#findings)

## Business Problem<a id="problem"></a>
One of the prestigious Telecom company maintains a database of the customer and their details.The company wants an end-to-end Business Analysis Solution to minimize Customer Attrition.The stakeholders wants to determine the factors associated with Customer churn along with quantification and categorization of the churn risk associated with any user in the subscriber base and to find out the most popular churn segments.

## Data Summary<a id="summary"></a>
The provided dataset consists of the information below:

- Demographic information about customers including gender, age, marital status.

- Customer account information including the number of months staying with the company, paperless billing, payment method, monthly charges, and total charges.

- Customer usage behavior, such as streaming TV, streaming movie.

- Services that the customer signed up for: phone service, multiples, internet service, online security, online backup, device protection, and tech support.

- Customer churn where the customer left within the last month.

## Skills used And Approach<a id="approach"></a>

Skills: Data Modelling, Machine Learning, Power BI

I have divided the analytic part in 3 Sections: 
         1. Churned Customer Analysis 
         2. Customer Overall Analysis 
         3. Not Churn Customer Risk Analysis

1st Section: Churned Customer Analysis: In this Section, I analyzed only Churned customers from the dataset and showed the results with proper visualization.

2nd Section: Customer Analysis: In this Section, I analyzed overall customer data and showed the results with proper visualization.

3rd Section: Not Churn Customer Risk Analysis: In this Section, I analyzed retained customers' data and Created a Machine Learning (ML) model to predict which customers from the retained customers will be Risky Customers for the future. And showed the results with proper visualization.

In order to analyze the churning risk of a subscriber we need to create Machine Learning models to predict whether a subscriber will discontinue to take the services of the company or not. Here, I have used Logistic regression to do the modeling.

In order to identify the customers with high risk of being churn we use conditional column as

- IF Probability of a customer being churn **less than 40% then non risky**,

- between 40% to 60% : **Low Risky**,

- 60% to 80%: **Risky**,

- Greater than 80%: **High risky**

## Dashboard<a id="dashboard"></a>

# Screenshots of Dashboard
![Customer Analysis](https://github.com/meghasolanki008/Customer-Churn-Analysis/blob/main/Overall%20Customer%20Analysis.png)
![Churn Customer Analysis](https://github.com/meghasolanki008/Customer-Churn-Analysis/blob/main/Churned%20Customer.png)
![Not Churn Customer Analysis](https://github.com/meghasolanki008/Customer-Churn-Analysis/blob/main/Not%20Churn%20Customer.png)

## Findings<a id="findings"></a>
Insights:

1. **The data shows that roughly 27% of the subscriber base have churned**, means out of 7034 customers 1869 left the company.
   
2. From demographic information we can infer that :
     2.1. **Gender has no impact on churning.**

     2.2. Customers who have lower tenure are more likely to churn **i.e. NEW customers are churning much more as compared to long term customer**.

     2.3. Higher percentage (around **11% more) of Senior citizen are in the churner base** then in the subscriber base.

     2.4. Subscribers who **do not have partners are 40% more likely to churn** as compared to partnered subscriber.

3. In the **Phone Service and usage data** we can infer that:

    3.1 Subscribers with **no online security are 30 % more likely to churn.**

    3.2: Subscribers **without any tech support assistance are 32% more likely to churn.**

   3.3: Subscribers **on fiber optics are 25 % more likely to churn** as well.

4. In the **Contract and Payment data** we can infer that:

   4.1 Subscribers on **monthly plan form 90% of all the churners** and are very highly likely to churn as compared to just 55% of all subscriber.

   4.2: Subscribers paying through **electronic cheques are 24% more likely to churn.**

   4.3: **Churner's average monthly revenue is $10 more than overall average monthly revenue.**

Suggestions:
1. The company should consider extending the basic contract plan from one month to three or six months. This would encourage the customers to stay longer with the company and reduce churn rate.

2. The company should also target who are single and have no family obligations.They have the potential to become loyal customers if they are offered attractive deals and discounts.

3. The company should provide basic services such as device protection, tech support and online security as part of their standard package. These services can increase customer satisfaction, loyalty and prevent them from switching.

   



