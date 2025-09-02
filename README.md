# TELECOM_CUSTOMER_CHURN-ANALYSIS-USING -GENAI
<img width="800" height="428" alt="image" src="https://github.com/user-attachments/assets/bf866f4a-6058-49b6-83b1-8b5a70b6955a" />

# Objective:
The objective of this project is to analyze customer behavior and identify the key factors influencing customer churn in a telecom company. By leveraging exploratory data analysis (EDA), statistical methods, and machine learning models, the project aims to:

Understand patterns and drivers of churn (e.g., contract type, tenure, payment method, service usage).

Build predictive models to classify customers as likely to churn or stay.

Provide actionable insights and recommendations to improve customer retention, reduce revenue loss, and enhance business decision-making.

# Dataset Description

The dataset used in this project is the Telco Customer Churn dataset, containing information about telecom customers, their services, billing details, and churn status. It has 7,043 rows (customers) and 21 columns (features).

Key Features

1. Customer Information

a. customerID – Unique ID for each customer

b. gender – Male or Female

c. SeniorCitizen – Indicates if the customer is a senior citizen (1 = Yes, 0 = No)

d. Partner – Whether the customer has a partner (Yes/No)

e. Dependents – Whether the customer has dependents (Yes/No)

2. Account Information

a. tenure – Number of months the customer has stayed with the company

b. Contract – Type of contract (Month-to-month, One year, Two year)

c. PaperlessBilling – Whether the customer uses paperless billing (Yes/No)

d. PaymentMethod – Payment method (Electronic check, Mailed check, Bank transfer, Credit card)

3. Services Signed Up

a. PhoneService – Whether the customer has phone service (Yes/No)

b. MultipleLines – Whether the customer has multiple lines (Yes/No/No phone service)

c. InternetService – Type of internet (DSL, Fiber optic, No internet)

d. OnlineSecurity – Whether the customer has online security (Yes/No/No internet)

e. OnlineBackup – Whether the customer has online backup (Yes/No/No internet)

f. DeviceProtection – Whether the customer has device protection (Yes/No/No internet)

g. TechSupport – Whether the customer has tech support (Yes/No/No internet)

h. StreamingTV – Whether the customer uses streaming TV (Yes/No/No internet)

i. StreamingMovies – Whether the customer uses streaming movies (Yes/No/No internet)

4. Billing Information

a. MonthlyCharges – Amount charged per month

b. TotalCharges – Total amount charged to the customer

5. Target Variable

a. Churn – Whether the customer left the company (Yes/No)

# Exploratory Data Analysis (EDA) is done by following questions:

 generate  the python code for the following task :  
 
code for uploading data into python dataframe:
.write a code to read this file in dataframe 

.write a code to see few line of data    

.write a python code for changing datatype of column totalcharges and replace blank sapce with "0".

.write a code for checking is there any null value present in dataset. 

.write a code to describe the numerical column

.define function convert with value and apply condition as if value==1,print "yes "else "no". 

. apply this to column senior citizen

# FOR VISUALIZATION

.write a code for count plot for column "churn" with displaying no on them

.write a code for pie plot for column "churn " with display the percentage

.write a code for count plot for column "gender " with churn status

.write a code for count plot for column "senior citizen" with churn status

.write a code for ploting histogram for column "tenure" along with churn status

.write a code for count plot for column contract with churn status

.'PhoneService', 'MultipleLines', 'InternetService', 'OnlineSecurity', 'OnlineBackup', 'DeviceProtection',

'TechSupport', 'StreamingTV', 'StreamingMovies' the above are the column from table . 

generate a python code for creating a subplot for them with considering each of them would be countplot.

.write a code for count plot for column "Payment Method" with churn status.


# Key Insights

1.Churn Rate

* Around 26–27% of customers have churned.

* Indicates a class imbalance problem in the dataset.

2.Customer Tenure

* Customers with low tenure (<12 months) are much more likely to churn.

* Long-term customers (2+ years) show strong loyalty.

3.Contract Type

* Month-to-month contracts have the highest churn rate.

* Yearly and two-year contracts significantly reduce churn.

4.Payment Method

* Customers paying via Electronic Check churn at a much higher rate.

* Automatic payments (Bank Transfer, Credit Card) have lower churn.

5.Internet Service

* Fiber optic users show the highest churn compared to DSL.

* Customers with no internet service churn the least.

6.Value-added Services

* Lack of Online Security and Tech Support strongly correlates with churn.

* Customers subscribed to these add-ons are more likely to stay.

7.Monthly Charges

* High MonthlyCharges (above $70) are associated with more churn.

* Customers paying lower monthly bills tend to remain longer.

8.Demographics

* No strong churn difference between gender categories.

* Senior Citizens are slightly more likely to churn.

# Overall Insight:
* Churn is driven primarily by short contracts, higher costs, lack of additional services, and inconvenient payment methods.
*  Addressing these issues can significantly improve retention.

# RECOMMENDATIONS

* Encourage long-term contracts
Offer discounts/incentives for customers to switch from month-to-month to annual contracts.

* Improve Fiber Optic service quality
Since churn is higher among fiber users, investigate service reliability, speed, or pricing issues.

* Bundle value-added services
Promote Online Security, Tech Support, Device Protection as add-ons to increase stickiness and reduce churn.

* Targeted retention campaigns

* Identify new customers (<6 months tenure) and offer welcome benefits.

* Flag customers with electronic check payments for retention offers (e.g., discounts if they switch to auto-pay).

* Customer support intervention
Deploy predictive churn scores to proactively reach out to high-risk customers before they cancel.

* Continuous monitoring
Retrain churn prediction models quarterly with updated data to keep retention strategies relevant.

* DATASET LINK:https://github.com/Ayushi0214  
