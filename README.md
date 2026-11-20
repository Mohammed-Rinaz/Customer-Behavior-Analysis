# Customer Shopping Behavior Analysis

## 1. Project Overview
An end-to-end Data Analytics project focused on understanding customer shopping patterns, purchasing behavior, product preferences, and revenue performance. The project uses Python, MySQL, and Power BI to transform raw transaction data into meaningful business insights and actionable recommendations.

## 2. Dataset
- **Records:** 3,900 customer transactions
- **Columns:** 18 original features
- **Format:** CSV
- **Key Information:** Customer demographics, product categories, purchase amounts, discounts, subscriptions, shipping preferences, and review ratings.

## 3. Tools & Technologies
- **Python:** Pandas, NumPy
- **Jupyter Notebook:** Data exploration and analysis
- **MySQL:** Database management and SQL queries
- **Power BI:** Interactive dashboard development
- **Gamma AI:** Project presentation
- **MS Word / PDF:** Project documentation and reporting

## 4. Project Workflow

### Step 1: Data Loading & Exploratory Data Analysis (Python)
- Imported the dataset using Pandas.
- Explored data structure, data types, and statistical summaries.
- Identified missing values and examined data quality.

### Step 2: Data Cleaning & Feature Engineering
- Handled 37 missing review ratings using category-wise median imputation.
- Standardized column names using snake_case.
- Created customer age groups.
- Converted purchase frequency into numerical day intervals.
- Identified and removed redundant columns.

### Step 3: MySQL Business Analysis
Loaded the cleaned dataset into MySQL and performed SQL queries to answer key business questions:

- Revenue comparison by gender.
- High-spending customers using discounts.
- Top-rated products.
- Standard vs. Express shipping performance.
- Subscribers vs. non-subscribers.
- Discount-dependent products.
- Customer segmentation (New, Returning, Loyal).
- Top-selling products by category.
- Repeat buyers and subscription behavior.
- Revenue contribution by age group.

### Step 4: Power BI Dashboard
Developed an interactive dashboard featuring:
- Total customer count.
- Average purchase amount.
- Average product rating.
- Revenue and sales by category.
- Customer subscription analysis.
- Revenue and sales by age group.
- Interactive filters for customer and purchase attributes.

### Step 5: Reporting & Presentation
- Created a structured project report documenting the analysis and findings.
- Prepared a professional project presentation using Gamma AI.
- Summarized key insights and business recommendations.

## 5. Dashboard & Results

The analysis revealed several important business insights:

- Identified customer segments based on purchase history.
- Compared revenue contribution across customer demographics.
- Analyzed subscription patterns and repeat purchases.
- Identified top-rated and frequently purchased products.
- Evaluated discount usage and shipping preferences.

**Key Dashboard Metrics:**
- Total Customers: 3.9K
- Average Purchase Amount: $59.76
- Average Review Rating: 3.75

## 6. Business Recommendations
- Introduce loyalty programs to encourage repeat purchases.
- Improve subscription adoption through exclusive benefits.
- Optimize discount strategies.
- Promote popular and highly rated products.
- Use customer segmentation for targeted marketing campaigns.

## 7. How to Run

### Prerequisites
- Python 3.x
- Jupyter Notebook
- MySQL Server and MySQL Workbench
- Power BI Desktop

### Step 1: Clone the Repository
```bash
git clone https://github.com/YOUR-USERNAME/Customer-Behavior-Analytics.git
```

### Step 2: Install Python Libraries
```bash
pip install pandas numpy sqlalchemy pymysql jupyter
```

### Step 3: Load the Dataset
Place `customer_shopping_behavior.csv` in the project directory.

### Step 4: Run the Notebook
Open Jupyter Notebook and execute the analysis notebook to perform data cleaning, EDA, feature engineering, and data preparation.

### Step 5: Connect to MySQL
Create a MySQL database named `customer_behavior`, configure your database credentials, and load the cleaned dataset into MySQL.

### Step 6: Run SQL Analysis
Execute the SQL queries in MySQL Workbench to reproduce the business analysis.

### Step 7: Explore the Dashboard
Open the Power BI `.pbix` file to explore the interactive dashboard.

## 8. Project Structure

```text
Customer-Behavior-Analytics/
│
├── dataset/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_analysis_queries.sql
│
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── reports/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── presentation/
│   └── Customer_Behavior_Presentation.pdf
│
└── README.md




---

**If you find this project useful, feel free to star the repository!**
