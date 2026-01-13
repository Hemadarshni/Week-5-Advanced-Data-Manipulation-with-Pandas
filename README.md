# Week-5-Advanced-Data-Manipulation-with-Pandas

## 📖 Project Overview

The Customer Sales Analysis Project aims to analyze customer purchasing patterns, identify top customers, and provide actionable insights to improve sales performance and customer retention. Using historical sales and customer data, the project leverages Python and pandas to perform data aggregation, pivoting, and visualization.

## Objectives:

Identify the most valuable customers and products

Analyze regional and seasonal sales trends

Evaluate customer retention and churn patterns

Provide actionable business recommendations to improve sales and retention

## 🛠️ Project Setup & Installation

1. Clone the Repository

git clone https://github.com/YourUsername/customer-sales-analysis.git
cd customer-sales-analysis


2. Create a Python Virtual Environment

python -m venv venv
source venv/bin/activate    # Linux/macOS
venv\Scripts\activate       # Windows


3. Install Dependencies

pip install -r requirements.txt


4. Run the Jupyter Notebook

jupyter notebook customer_analysis.ipynb

## 📂 Project Structure
customer-sales-analysis/
│
├─ customer_analysis.ipynb       # Main Jupyter notebook with full analysis
├─ sales_data.csv                # Sales transaction dataset
├─ customer_data.csv             # Customer dataset
├─ analysis_report.pdf           # Detailed insights and recommendations
├─ requirements.txt              # Python dependencies
└─ README.md                     # Project documentation

## 🧮 Data & Analysis

Datasets Used:

sales_data.csv – contains product, quantity, total sales, month, and region

customer_data.csv – contains customer information, contract type, tenure, and churn

### Key Analysis Steps:

#### Data Loading & Exploration

Explored datasets for structure and missing values

Data Cleaning & Preparation

Handled missing values

Converted date columns

Created calculated columns for metrics like revenue per customer

#### Customer Analysis

Identified top customers by total spend

Analyzed regional sales distribution

Sales Pattern Analysis

Aggregated sales by month, product, and region

Identified best-selling products and seasonal trends

#### Advanced Analysis

Created pivot tables 

Evaluated churn by tenure and contract type

Analyzed opportunities for cross-selling and up-selling

Built 4-5 visualizations using line charts, bar charts, and heatmaps

Visualized trends, top products, and regional performance

## 📊 Sample Findings

Top Product by Sales: Laptop – $3,889,210

Region with Highest Sales: South

Month with Highest Sales: March – 44,85,006

Churn Analysis: Month-to-month customers show the highest churn; longer contracts improve retention

Insights & Recommendations:

Promote longer-term contracts and loyalty offers to reduce churn

Offer bundle deals to encourage cross-selling of products

Focus marketing campaigns in high-performing regions

Monitor seasonal trends to optimize inventory and promotions

## 💻 Technical Details

Language & Tools: Python, pandas, matplotlib, seaborn

Data Manipulation: Merging, grouping, pivot tables, aggregation functions

Visualization: Line charts, bar charts, heatmaps for insights

## 🧪 Testing & Validation

Data integrity checks were implemented to ensure no missing or duplicate records

Calculations of sales, churn, and tenure metrics were cross-verified

Pivot tables validated aggregated totals with raw dataset values

## 📤 Submission Contents

customer_analysis.ipynb – Complete Jupyter Notebook

sales_data.csv & customer_data.csv – Source datasets

analysis_report.pdf – Executive summary with visualizations and recommendations

requirements.txt – Python library dependencies
