# Telecom-Churn-Analysis
End-to-end telecom customer churn analysis using Python, Pandas, NumPy, Matplotlib, and Seaborn
**PROBLEM STATEMENT**
“A telecom company is facing high customer churn. Your task is to analyze customer data, identify why customers are leaving, build visual insights, and propose data-driven solutions to reduce churn.”
**Project Overview**
Customer churn is a major problem in the telecom industry.
This project performs a complete Exploratory Data Analysis (EDA) on telecom customer data to identify:
Which customers churn
Why they churn
What patterns indicate churn behaviour
What the business can do to reduce churn
This project focuses on data cleaning, analysis, visualizations, and insights
**Dataset**
**Dataset**: Telco Customer Churn Dataset (7,043 rows, 21 columns)
Columns include customer demographics, services used, billing information, and churn status.
**Key features**:
tenure, Contract, MonthlyCharges, TotalCharges, PaymentMethod,
PaperlessBilling, InternetService, TechSupport, Churn
Dataset included in repository: telco_churn.csv
**Project Structure**
telecom-churn-analysis/
│── telecom_churn_analysis.ipynb   → Main analysis notebook
│── telco_churn.csv                → Dataset
│── README.md                      → Project documentation
└── images/                        → Exported charts
**Phase 1: Data Understanding**
Loaded dataset with Pandas
Inspected shape, data types, duplicates
Standardized column names
Converted totalcharges to numeric
Checked missing values
**Phase 2: Data Cleaning**
Cleaned inconsistent entries
Converted Yes/No to categorical
Filled or handled missing values
Removed duplicates
Verified dataset quality
**Phase 3: Exploratory Data Analysis (EDA)**
Visuals created using Matplotlib & Seaborn:
Churn distribution
Tenure distribution
Monthly charges distribution
Churn by Contract Type
Churn by Internet Service
Churn by Payment Method
Monthly Charges vs Churn
Correlation heatmap
**Phase 4: Key Insights**
Overall churn rate is high (~26–28%)
Significant business risk.
Month-to-Month contract customers churn the most
Strongest churn driver.
High monthly charges increase churn probability
Price-sensitive customers leave faster.
Short-tenure customers churn early
Most churn happens in the first 6 months.
Electronic Check payment method has the highest churn
Unstable customer segment.
Fiber Optic internet users churn more
Higher pricing → higher dissatisfaction.
Customers with add-on services churn less
Tech support / Device Protection increases retention.
Paperless billing customers churn more
More price-sensitive segment.
Senior citizens show higher churn
Requires targeted support.
High-risk churn customer profile
Month-to-month contract
High monthly charges
Electronic check
Fiber optic
Paperless billing
No TechSupport
Tenure < 6 months
**Conclusion**
This project identifies key churn drivers and provides actionable business insights.
It demonstrates a full analytics workflow: data cleaning → analysis → visualization → insights.
