# 📊 E-Commerce Sales Analysis

An end-to-end Exploratory Data Analysis (EDA) of an e-commerce sales dataset, built in Python. The notebook covers data cleaning, KPI reporting, segmentation analysis, trend analysis, statistical hypothesis testing, and predictive modeling.

## 🔧 Tech Stack
- **Pandas / NumPy** – data wrangling
- **SQLite3** – SQL-based aggregations
- **Matplotlib / Seaborn** – visualizations
- **SciPy** – statistical tests (T-Test, ANOVA, Pearson correlation)
- **Scikit-learn** – linear regression models

## 📁 Project Structure
```
.
├── SalesAnalysis.ipynb     # Main analysis notebook
├── ecommerceSales.csv      # Dataset (add this file yourself - see below)
└── README.md
```

## ▶️ How to Run
1. Clone this repository.
2. Place `ecommerceSales.csv` in the project's root folder (same folder as the notebook).
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn
   ```
4. Open `SalesAnalysis.ipynb` in Jupyter Notebook / JupyterLab / VS Code and run all cells.

## 📈 What's Inside
- **KPI Summary** – revenue, profit, orders, AOV, and profit margin at a glance
- **Product Category Analysis** – sales, profit, growth %, margins, and discount impact per category
- **Region Analysis** – performance breakdown by region
- **Customer Segment Analysis** – Consumer vs Corporate vs Home Office
- **Country-Level Analysis** – top countries by revenue and profit
- **Monthly & Yearly Trends** – seasonality and YoY growth
- **Top / Least Buying Customers** & **Payment Method Analysis**
- **Correlation Heatmap** of numeric features
- **Statistical Tests** – T-Test, ANOVA, Pearson correlation to validate findings
- **Predictive Modeling** – Linear Regression to predict Total Sales and Profit
- **Overall Summary** – consolidated insights and business recommendations

## 🔑 Key Findings (TL;DR)
- Total Revenue: **$484,559.34** | Total Profit: **$158,872.32** | Profit Margin: **32.79%**
- **Furniture** drives the most revenue and profit but is heavily discounted, suppressing margins.
- **Technology** offers strong margins (28.6%) and YoY growth (+6.59%) — a good investment target.
- **Europe** is the top-growth region (+34.88% YoY); **North America** and **South America** are declining.
- The **Consumer** segment is most profitable, driven largely by lower average discounts.
- A linear regression model explains ~95% (R² = 0.95) of the variance in profit using sales, discount, category, and payment method.

See the **Overall Summary** section at the end of the notebook for the full write-up and recommendations.

## 📊 Power BI Dashboard

An interactive Power BI dashboard built on the same dataset with two pages:

### Sales Dashboard
- KPIs: Total Orders, Customers, Sales, YoY Growth, MoM Growth
- Product Category Sales breakdown
- Customer Segment analysis (Consumer/Corporate/Home Office)
- Month-wise sales trend
- Country-wise average sales with conditional formatting

### Profit Dashboard  
- KPIs: Total Profits (158.87K), Profit Margins (32.79%)
- Product Category Profits
- Month-wise profit trends
- Country-wise average profits (Germany highest, Colombia lowest)

### Dashboard Screenshots
Sales Dashboard :
Profit Dashboard:

**Tool:** Microsoft Power BI Desktop  
**File:** `Ecommerce_Dashboard.pbix`
## 📥 Download Dashboard
[Download Power BI File (.pbix)](https://github.com/MohamedNalif/Ecommerce-Sales-Profit-Analysis/blob/main/Ecommerce.pbix)
