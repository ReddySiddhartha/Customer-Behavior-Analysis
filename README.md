
# Customer Behavior Analysis

## About the Project
This project analyzes e-commerce customer transaction data to understand purchasing patterns, identify customer segments, and explore recorded churn behavior. It was completed as part of the Alfido Tech Data Analyst Internship.

## Objectives
- Analyze customer purchasing behavior.
- Perform data cleaning and basic statistical analysis.
- Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
- Visualize product category sales, monthly purchase trends, and customer segments.
- Provide actionable business recommendations.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab
- ReportLab

## Analysis Performed
1. Inspected dataset structure, data types, missing values, and duplicate records.
2. Analyzed total purchase amount across product categories.
3. Examined monthly purchase trends.
4. Created five rule-based customer segments using RFM analysis:
   - Champions
   - Loyal Customers
   - Recent Customers
   - At Risk
   - Needs Attention
5. Examined recorded customer churn labels and their distribution.
6. Prepared a PDF report with findings and recommendations.

## Key Findings
- Dataset contains 250,000 transaction records and 49,661 unique customers.
- Total recorded purchase amount is 681,346,299 (currency not specified).
- The Returns column contains missing values.
- Champions have the highest average recorded spending among the defined RFM segments.
- The recorded customer-level churn rate is approximately 19.99%. The dataset's churn definition should be verified before interpreting this as actual churn.

## Business Recommendations
1. Re-engage customers in the Needs Attention segment with relevant reminders and offers.
2. Reward Champions through loyalty benefits and exclusive offers.
3. Run measurable win-back campaigns for At Risk customers.
4. Encourage repeat purchases through relevant product recommendations.
5. Monitor customer behavior and investigate additional factors associated with churn.

## Project Files
- `Customer_Behavior_Analysis (1).ipynb` — analysis notebook.
- **PDF Report:** [View the report on Google Drive](https://drive.google.com/drive/folders/11oZ4XhiZ1QeVXc7InszKypGWK7NE-uaO?usp=sharing)

## Limitations
RFM segments are rule-based and are not a validated churn prediction model. The meaning of the churn label needs confirmation, and the final month contains only partial-month data.
