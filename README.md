# Predicting Customer Churn for a Subscription Service

## Project Overview

This project aims to predict customer churn for a subscription-based service using machine learning techniques. Customer churn prediction is crucial for businesses to retain customers and improve their services. This project involves data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## Dataset

The dataset used in this project is the Telco Customer Churn dataset from Kaggle. It includes various features about customers, such as demographic details, account information, and service usage. You can download the dataset here: (https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Key Takeaways

1. **Tenure**. Longer tenure significantly reduces the likelihood of churn. Customers who have been with the company for a longer period are more likely to stay.
2. **Internet Service: Fiber Optic**. Customers using fiber optic internet service are more likely to churn compared to those using other types of internet services.
3. **Payment Method: Electronic Check**. Customers who use electronic checks as their payment method exhibit a higher propensity to churn.
4. **Monthly Charges**. Higher monthly charges are associated with an increased likelihood of churn. This indicates that cost-sensitive customers are more likely to leave.
5. **Multiple Lines: Yes**. Customers with multiple lines are more likely to churn, suggesting potential issues with service quality or pricing for multiple line subscriptions.
6. **Streaming Services (Television and Movies)**. Access to streaming services like streaming television and movies is associated with higher churn. This could be due to competition or dissatisfaction with the service.
7. **Contract Two Year**. Customers with two-year contracts are less likely to churn, indicating that long-term contracts can help in retaining customers.
8. **Payment Method: Mailed Check and Credit Card (Automatic)**. These payment methods are associated with lower churn rates, suggesting that customers using these methods may be more stable or satisfied.
9. **Dependents and Device Protection**. These factors show some impact on churn, but less significant compared to the above factors.


## Business Implications

1. **Customer Retention Programs**. Develop retention programs focused on customers with shorter tenure to extend their stay with the company. Encourage new customers to sign up for longer-term contracts with benefits and discounts, as these customers are less likely to churn.
2. **Service Improvement for Fiber Optic Customers**. Focus on improving the quality and reliability of fiber optic internet services to reduce churn among these high-risk customers. Collect and act on feedback specifically from fiber optic users to address their concerns.
3. **Pricing Strategy**. Consider revising pricing plans to make them more competitive, especially for customers with higher monthly charges. Offer more flexible payment options and discounts for electronic check users to lower their churn risk.
4. **Multiple Lines and Streaming Services**. Create attractive bundle offers for customers with multiple lines and streaming services to enhance value and satisfaction. Invest in improving the streaming service experience to address potential dissatisfaction.
5. **Payment Method Optimization**. Encourage the use of mailed checks and automatic credit card payments by offering incentives, as these methods are associated with lower churn.
6. **Personalized Customer Engagement**. While these factors have lower impact, personalized engagement strategies can still be developed to cater to these customer segments.

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- shap

## Usage

1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter notebooks or Python scripts in the notebooks/ or src/ directories to see the data analysis and model building process.
4. View the results and visualizations saved in the results/ directory.

## Acknowledgements

This project uses the Telco Customer Churn dataset from Kaggle.
