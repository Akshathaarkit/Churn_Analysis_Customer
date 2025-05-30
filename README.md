# Customer Churn Analysis

This project explores a telecom customer dataset to identify factors that influence customer churn. Churn refers to customers who stop using a company's service. Using Python and data visualization tools, this analysis uncovers patterns and insights to help improve customer retention strategies.

## Dataset Overview

The dataset contains information about 7,043 customers, including:

- Demographics: gender, senior citizen status, partner, dependents
- Services used: phone, internet, streaming, backup, security, tech support
- Account details: contract type, billing method, monthly and total charges
- Churn status (target variable)

## Tools & Libraries

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for visualizations
- Jupyter Notebook

## Key Steps Performed

1. **Data Cleaning**
   - Converted `TotalCharges` to numeric and handled blanks
   - Verified no missing values or duplicate `customerID`s

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution overall and by:
     - Gender and senior citizen status
     - Tenure and contract type
     - Internet and phone services
     - Streaming, backup, and security services
     - Payment methods
   - Used bar charts, pie charts, and subplots for comparison

## Key Insights

- Around **26%** of customers have churned.
- Customers with **monthly contracts** and **electronic check payments** show higher churn rates.
- **Senior citizens** and those without services like **online security** or **tech support** tend to leave more.
- Customers with **longer tenure** and **yearly contracts** are more likely to stay.

## Conclusion

Engagement with essential services and contract commitment plays a major role in customer retention. This analysis provides useful insights for targeting at-risk customers and improving service offerings.

## How to Run

1. Open the `Customer_Churn_Analysis.ipynb` notebook
2. Run each cell in order to perform data cleaning, visualization, and insight generation

## Author

Akshatha Arkit  
Data Analyst | Python, Power BI, SQL

## License

This project is for learning and portfolio purposes only.
