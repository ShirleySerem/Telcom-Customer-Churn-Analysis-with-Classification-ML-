# Telcom-Customer-Churn-Analysis-with-Classification-ML-
This project aims to find the likelihood of a customer leaving the organization, the key indicators of churn as well as the retention strategies that can be implemented to avert this problem.

---

Introduction
Predicting customer churn is critical for telecommunication companies to be able to effectively retain customers. It is more costly to acquire new customers than to retain existing ones. For this reason, large telecommunications corporations are seeking to develop models to predict which customers are more likely to change and take action accordingly.
In this article, we build a model to predict how likely a customer will churn by analyzing its characteristics: (1) demographic information, (2) account information, and (3) service information. The objective is to obtain a data-driven solution that will allow us to reduce churn rates and, as a consequence, to increase customer satisfaction and corporation revenue.

---

**Requirements**

Python 3.0 +

Understanding of libraries (Scikit Learn, Numpy, Pandas, Matplotlib, Seaborn)

Jupyter Notebook or Google Colab

Basic understanding of classification methods or Algorithms



**Data Set**

The Churn column (response variable) indicates whether the customer departed within the last month or not. The class No includes the clients that did not leave the company last month, while the class Yes contains the clients that decided to terminate their relations with the company. The objective of the analysis is to obtain the relation between the customer's characteristics and the churn.

The data for this project is in a CSV format. The following describes the columns present in the data.
1. Gender - Whether the customer is a male or a female
2. SeniorCitizen - Whether a customer is a senior citizen or not
3. Partner - Whether the customer has a partner or not (Yes, No)
4. Dependents - Whether the customer has dependents or not (Yes, No)
5. Tenure - Number of months the customer has stayed with the company
6. Phone Service - Whether the customer has a phone service or not (Yes, No)
7. MultipleLines - Whether the customer has multiple lines or not
8. InternetService - Customer's internet service provider (DSL, Fiber Optic, No)
9. OnlineSecurity - Whether the customer has online security or not (Yes, No, No Internet)
10. OnlineBackup - Whether the customer has online backup or not (Yes, No, No Internet)
11. DeviceProtection - Whether the customer has device protection or not (Yes, No, No internet service)
12. TechSupport - Whether the customer has tech support or not (Yes, No, No internet)
13. StreamingTV - Whether the customer has streaming TV or not (Yes, No, No internet service)
14. StreamingMovies - Whether the customer has streaming movies or not (Yes, No, No Internet service)
15. Contract - The contract term of the customer (Month-to-Month, One year, two years)
16. PaperlessBilling - Whether the customer has paperless billing or not (Yes, No)
17. Payment Method - The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))
18. MonthlyCharges - The amount charged to the customer monthly
19. TotalCharges - The total amount charged to the customer
20. Churn - Whether the customer churned or not (Yes or No)

---

**Data Understanding**

**Research Questions**

I used the questions below to find more information on this data set.
1. Do customers who have subscribed to online security from the company likely to churn?
2. How does the length of a customer's contract affect their likelihood to churn?
3. How do customers' total monthly charges impact their decision to churn?
4. Does the payment method contribute to why customers churn?
5. What is the rate of customer churn concerning the billing method?
6. Is there a relation between total charges and the likelihood of customers churning?