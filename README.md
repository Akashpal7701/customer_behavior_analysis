# 🛍️ Customer Shopping Behavior Analysis

## 📌 Overview

This project analyzes customer shopping behavior to understand purchasing patterns, customer preferences, product performance, and spending trends.

Using **Python, MySQL, and Power BI**, this project follows an end-to-end data analytics workflow, from data cleaning and exploratory data analysis (EDA) to SQL-based business analysis and interactive dashboard development.

**🎯 Project Goal:** Transform raw customer data into meaningful business insights that support data-driven decision-making.

## 📂 Dataset

The dataset contains customer shopping and purchasing information, including:

- 👥 Customer demographics
- 🛒 Product categories and purchase amounts
- 🏷️ Discounts and subscription status
- 🚚 Shipping preferences
- ⭐ Customer ratings and purchase frequency

| Dataset Details | Value |
|---|---|
| Total Records | 3,900 |
| Total Columns | 19 |
| File Format | CSV |

## 🛠️ Tools & Technologies

- **Python** — Data processing and analysis
- **Pandas & NumPy** — Data cleaning and manipulation
- **Jupyter Notebook** — Exploratory Data Analysis (EDA)
- **MySQL Workbench** — SQL queries and business analysis
- **Power BI** — Interactive dashboards and data visualization
- **Gamma** — Presentation creation
- **Git & GitHub** — Version control and project hosting

## 🔄 Project Workflow

### 1. 📥 Data Loading
- Imported the dataset into Python using Pandas.
- Examined the dataset structure, columns, and data types.

### 2. 🔍 Exploratory Data Analysis (EDA)
- Explored customer demographics and purchasing patterns.
- Analyzed purchase amounts, product categories, discounts, and ratings.
- Identified missing values and potential data quality issues.

### 3. 🧹 Data Cleaning
- Handled missing values.
- Reviewed data types and data consistency.
- Created age groups for customer segmentation.
- Standardized purchase-frequency categories.
- Prepared the cleaned dataset for further analysis.

### 4. 🗄️ SQL Analysis

Used **MySQL** to analyze customer shopping behavior and answer key business questions, including:

- Revenue comparison across customer genders.
- Customers who used discounts but spent above the average purchase amount.
- Highest-rated products.
- Comparison of Standard and Express shipping preferences.
- Spending patterns based on subscription status.
- Segmentation of new, returning, and loyal customers.
- Top-performing products within each category.
- Repeat customers and subscription behavior.
- Revenue contribution across different age groups.

### 5. 📊 Power BI Dashboard

- Connected the customer dataset to Power BI.
- Created measures and key performance indicators (KPIs).
- Designed visualizations to explore customer behavior and purchasing trends.
- Developed an interactive dashboard to communicate key findings.

### 6. 📝 Report & Presentation

- Organized the analysis and key findings into a project report.
- Created a presentation using Gamma to communicate insights clearly.

## 📈 Dashboard

The Power BI dashboard provides an interactive overview of customer shopping behavior, purchasing patterns, product performance, and customer segments.

**Dashboard File:** `powerbi/customer_shopping_behavior_dashboard.pbix`

## 💡 Results & Business Insights

The analysis focuses on identifying:

- 📌 Customer segments contributing to revenue.
- 👥 Differences in purchasing behavior across age groups.
- 🏷️ Relationships between discounts and spending.
- 🚚 Customer preferences for shipping and subscriptions.
- 🛒 Product performance based on purchasing activity and ratings.
- 📈 Opportunities to improve customer engagement and business decisions.

*Specific numerical findings can be added after validating the final SQL results and Power BI metrics.*

## 🚀 How to Run

### Prerequisites

Make sure the following tools are installed:

- Python
- Jupyter Notebook
- MySQL Server and MySQL Workbench
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/Akashpal7701/customer_behavior_analysis.git
cd customer_behavior_analysis
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy jupyter
```

### Step 3: Run the Python Notebook

1. Open Jupyter Notebook.
2. Open `notebooks/customer_shopping_behavior_analysis.ipynb`.
3. Update the dataset path if necessary.
4. Run the notebook cells to perform data loading, EDA, and data cleaning.

### Step 4: Run the SQL Queries

1. Open MySQL Workbench and connect to your MySQL server.
2. Open `sql/customer_behavior_analysis_queries.sql`.
3. Select the correct database and execute the analysis queries.

### Step 5: Open the Power BI Dashboard

1. Open `powerbi/customer_shopping_behavior_dashboard.pbix` in Power BI Desktop.
2. Configure the data source connection if prompted.
3. Refresh the data if required.

## 🔮 Future Improvements

- Develop advanced customer segmentation.
- Explore purchasing trends over time.
- Add more KPIs and dashboard features.
- Automate data refresh and reporting.
- Extend the project with predictive analytics.

## 👨‍💻 Author

**Akash Pal**

*Aspiring Data Analyst | Python | SQL | Power BI | Excel*

- **GitHub:** [Akashpal7701](https://github.com/Akashpal7701)
- **LinkedIn:** [Akash Pal](https://www.linkedin.com/in/akashpal01/)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
