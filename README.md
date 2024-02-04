# Telco Subscription Service Churn Analysis

<p align = "center">
<img src = ".\Images\Subscription Service Churn.png"> </img> </p>

### Project Overview

- This repository contains code and resources for analyzing customer churn in subscription-based businesses. 
- The project involves `Machine Learning Prediction` for churn, a `Power BI dashboard` with comprehensive features, `insights` drawn from the analysis, and `recommended actions` to mitigate churn.
  
### Data Source
The dataset was sourced from the Telco company's customer database and anonymized for privacy and confidentiality purposes. It consists of historical records of customers and their interactions with the company's services



#### Data Model:
telco_customer_churn.csv: CSV file containing the dataset with the following columns:

``` json
"CustomerID": Unique identifier for each customer.
"Gender": Customer's gender (Male/Female).
"SeniorCitizen": Indicates if the customer is a senior citizen (1) or not (0).
"Partner": Indicates if the customer has a partner (Yes/No).
"Dependents": Indicates if the customer has dependents (Yes/No).
"Tenure": Number of months the customer has been with the company.
"PhoneService": Indicates if the customer has phone service (Yes/No)
"MultipleLines": Indicates if the customer has multiple lines (Yes/No/No phone service).
"InternetService": Type of internet service subscribed by the customer (DSL/Fiber optic/No).
"OnlineSecurity": Indicates if the customer has online security service (Yes/No/No internet service).
"OnlineBackup": Indicates if the customer has online backup service (Yes/No/No internet service).
"DeviceProtection": Indicates if the customer has device protection service (Yes/No/No internet service).
"TechSupport": Indicates if the customer has tech support service (Yes/No/No internet service).
"StreamingTV": Indicates if the customer has streaming TV service (Yes/No/No internet service).
"StreamingMovies": Indicates if the customer has streaming movies service (Yes/No/No internet service).
"Contract": Type of contract subscribed by the customer (Month-to-month/One year/Two year).
"PaperlessBilling": Indicates if the customer has opted for paperless billing (Yes/No).
"PaymentMethod": Payment method used by the customer (Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic)).
"MonthlyCharges": Monthly charges incurred by the customer.
"TotalCharges": Total charges incurred by the customer.
"Churn": Indicates if the customer has churned (Yes/No).

```
### Machine Learning Model for Churn Prediction
The machine learning model for churn prediction is developed using the Telco Customer Churn Dataset. It follows these steps:

- `Data Preprocessing:` The dataset is cleaned and preprocessed to handle missing values, encode categorical variables, and scale numerical features.

- `Feature Selection:` Relevant features are selected based on their importance in predicting churn using techniques such as feature importance scores or domain knowledge.

- `Model Training:` Various machine learning algorithms such as logistic regression, random forest, or gradient boosting are trained on the preprocessed data to predict churn.

- `Model Evaluation:` The performance of each model is evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score. Cross-validation techniques may be used to assess generalization performance.

- `Model Selection:` The best-performing model is selected based on evaluation metrics and deployed for churn prediction.

#### Advantages of the machine learning model include:

- Ability to identify customers at risk of churning, enabling proactive retention strategies.
- Utilization of historical data to uncover insights and trends contributing to churn.
- Scalability and adaptability to evolving business needs and customer behaviors.

#### Limitations of the model include:

- Dependency on the quality and relevance of the input data.
Inherent uncertainty in predicting human behavior, leading to false positives and false negatives.
- Need for continuous monitoring and refinement to maintain accuracy and effectiveness over time.

### Analysis and Insights
Analysis of the Telco Customer Churn Dataset reveals several key insights:

- `Churn Rate Trends:` Analysis of churn rates over time reveals fluctuations and trends that may coincide with changes in service offerings, pricing plans, or market conditions.

- `Demographic Patterns:` Examination of churn patterns across different demographic segments (e.g., age, gender, marital status) may uncover disparities in churn behavior and inform targeted retention strategies.

- `Service Usage Patterns:` Customers with specific service subscriptions or usage patterns (e.g., internet service type, contract duration) may exhibit higher or lower churn rates, indicating the influence of service quality and customer experience.

- `Payment Methods and Billing Preferences:` Analysis of payment methods and billing preferences may highlight correlations with churn behavior, suggesting opportunities to optimize billing processes and enhance payment options.

- `Customer Engagement Metrics:` Evaluation of customer engagement metrics (e.g., frequency of interactions, customer support interactions) can identify indicators of customer satisfaction and loyalty, offering insights into potential drivers of churn.


### Features in Churn Analysis Dashbord Features

A churn analysis dashboard should provide a comprehensive view of key metrics and insights related to customer churn. Here are some must-have features for a churn analysis dashboard:

- `Churn Rate:` Display the overall churn rate over a specified time period. This is typically calculated as the number of customers who churned divided by the total number of customers.

- `Trend Analysis:` Visualize the trend of churn rate over time, allowing users to identify patterns, seasonal variations, or trends in churn behavior.

- `Segmentation:` Enable segmentation of the customer base based on different criteria such as demographics, subscription plans, or usage patterns. Display churn rates and trends for each segment to identify high-risk groups.

- `Customer Lifetime Value (CLV):` Include metrics related to customer lifetime value, such as average revenue per user (ARPU), customer acquisition cost (CAC), and CLV. Understanding the financial impact of churn can help prioritize retention efforts.

- `Feature Importance:` If machine learning models are used for churn prediction, provide insights into the most important features contributing to churn prediction. This helps identify key drivers of churn and informs targeted interventions.

- `Predictive Analytics:` Display predictions or forecasts of future churn based on historical data and predictive models. This allows proactive measures to be taken to mitigate churn risk.

- `Customer Feedback and Sentiment Analysis:` Integrate customer feedback data from surveys, reviews, or support tickets to assess customer satisfaction and sentiment. Identify trends in feedback associated with churn and prioritize areas for improvement.

- `Engagement Metrics:` Track customer engagement metrics such as login frequency, session duration, feature adoption, and usage patterns. Monitor changes in engagement levels to identify signals of potential churn.

- `Retention Efforts:` Provide visibility into retention efforts and initiatives aimed at reducing churn, such as promotional campaigns, loyalty programs, or targeted offers. Measure the effectiveness of these efforts in reducing churn rates.

- `Customer Journey Analysis:` Visualize the customer journey from acquisition to churn, highlighting key touchpoints and interactions along the way. Identify critical stages where churn risk is highest and focus retention efforts accordingly.

- `Benchmarking:` Compare churn rates and performance metrics against industry benchmarks or competitors to assess relative performance and identify areas for improvement.

- `Drill-Down and Interactivity:` Allow users to drill down into specific segments, time periods, or cohorts for deeper analysis. Provide interactive features such as filters, tooltips, and dynamic visualizations to facilitate exploration and discovery.


### Acknowledgments
Special thanks to the `Telco company` for providing access to the anonymized customer data for `research and analysis purposes`.

### Other Reference

   1. [Altexsoft : Subscription-Businesses-Using-Machine-Learning](https://www.altexsoft.com/blog/customer-churn-prediction-for-subscription-businesses-using-machine-learning-main-approaches-and-models/)

