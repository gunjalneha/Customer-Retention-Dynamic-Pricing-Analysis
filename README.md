# Customer-Retention-Dynamic-Pricing-Analysis
**Project Title**

Travel, Tourism & Hospitality: Customer Retention and Dynamic Pricing Analysis

**Objective**

The objective of this project is to analyze hotel booking data to understand customer behavior, identify key factors influencing booking cancellations, and explore pricing patterns across different segments.

Scope (Week 1 & Week 2)

**This submission covers:**

Week 1: Data Cleaning & Preprocessing
Week 2: Exploratory Data Analysis (EDA)

**Tools & Technologies**
Python
Pandas
NumPy
Matplotlib
Seaborn

**Week 1: Data Preprocessing**
Tasks Performed:
-Handled missing values in key columns
-Removed duplicate records
-Treated extreme outliers in Average Daily Rate (ADR)
-Removed invalid bookings (zero guests)
-Converted date columns to proper format
-Feature Engineering:
-Created total_stay (weekend + weekday nights)
-Created total_guests
-Created is_family indicator
-Categorized lead time into booking segments

**Week 2: Exploratory Data Analysis**
Key Analysis Performed:
-Distribution analysis of ADR
-Cancellation trend analysis
-Correlation matrix to identify key influencing factors
-Lead time vs cancellation behavior
-Customer segmentation analysis
-Seasonal pricing trends

**Key Insights**
-Higher lead time is associated with increased cancellation probability
-Transient customers have higher cancellation rates
-Bookings without deposits show significantly higher cancellations
-Pricing varies across seasons, with higher ADR during peak periods

**Files Included**
-01_data_cleaning.ipynb → Data preprocessing and feature engineering
-02_eda.ipynb → Exploratory data analysis and insights
