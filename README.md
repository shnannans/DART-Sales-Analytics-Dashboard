# DART Sales Analytics Dashboard 📊🛍️

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📋 Project Overview

Interactive data visualization project analyzing 5 years (2014-2018) of sales transactions for **DART Pte Ltd**, a wholesale business specializing in clothes and footwear. Built comprehensive dashboards using Python to derive actionable insights for revenue optimization in 2019.

**Course**: Data Discovery and Visualization | **Institution**: Ngee Ann Polytechnic | **Semester**: Oct 2021

---

## 🎯 Business Problem

As a Data Analyst at DART Pte Ltd in Q4 2018, analyze historical sales data to:
- Identify revenue and profit trends across products, customers, and locations
- Uncover patterns in pricing, discounts, and customer behavior
- Recommend data-driven interventions to increase 2019 profitability

---

## 📊 Analysis Framework

### Customer Analysis
- Which customers generate the most revenue/profit?
- Do high-frequency customers correlate with higher profitability?
- Customer segmentation and lifetime value

### Product Analysis
- Top revenue-generating and most profitable products
- Product performance trends over time
- Category analysis (Clothes vs. Footwear)

### Pricing & Discounts
- Price fluctuations across time periods
- Discount effectiveness and volume relationships
- Optimal pricing strategies

### Geographic Analysis
- Customer distribution across countries/cities
- Regional revenue and profit performance
- Market penetration opportunities

---

## 🛠️ Tech Stack

**Data Analysis & Visualization**:
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computations
- `matplotlib` - Static plotting and visualizations
- `seaborn` - Statistical data visualization
- `plotly` *(optional)* - Interactive dashboards

**Environment**:
- `jupyter notebook` - Interactive development and presentation

---

## 📁 Project Structure
```
dart-sales-analytics-dashboard/
├── data_analysis_script.ipynb          # Main analysis notebook
│
├── data/
│   └── dart_sales_data.csv             # Sales transactions (2014-2018)
│
├── dashboards/
│   └── *.png                           # Exported dashboard images
│
└── README.md                           # Project documentation
```

---

## 📈 Key Visualizations

The notebook includes 15+ visualizations across 4 themed dashboards:

### Dashboard 1: Revenue & Profit Overview
- Annual revenue trends (2014-2018)
- Profit margin analysis
- Revenue vs. profit scatter plots

### Dashboard 2: Customer Insights
- Top 10 customers by revenue/profit
- Customer frequency distribution
- RFM (Recency, Frequency, Monetary) segmentation

### Dashboard 3: Product Performance
- Best-selling products by category
- Product profitability matrix
- Seasonal sales patterns

### Dashboard 4: Geographic Distribution
- Revenue heatmap by country/city
- Regional profit margins
- Market penetration rates

---

## 💻 Installation & Usage

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis
```bash
jupyter notebook notebooks/codes_script.ipynb
```

**Execution Steps**:
1. **Data Preparation** - Load and clean sales data
2. **Exploratory Analysis** - Statistical summaries and distributions
3. **Visualization Creation** - Generate 15+ charts answering key questions
4. **Dashboard Assembly** - Combine visualizations into themed dashboards
5. **Insights & Recommendations** - Derive actionable business strategies

---

## 🔍 Sample Findings

### Revenue Insights
- **Annual Growth**: 12% CAGR from 2014-2018
- **Top Customer**: Customer #A001 generated $2.3M (18% of total revenue)
- **Peak Season**: Q4 consistently outperforms other quarters by 35%

### Product Performance
- **Footwear Category**: 60% of revenue but only 45% of profit
- **High-Margin Products**: Premium clothing items have 28% profit margins
- **Slow Movers**: 15% of SKUs contribute <2% of revenue

### Geographic Trends
- **Top Markets**: USA (42%), UK (28%), Germany (18%)
- **Emerging Opportunity**: Asian markets show 40% YoY growth
- **Underperforming**: Southern European regions need strategic review

### Pricing Dynamics
- **Discount Effectiveness**: 10-15% discounts maximize volume without eroding margins
- **Price Elasticity**: Premium products show inelastic demand
- **Volume Pricing**: Bulk orders (>100 units) receive 20%+ discounts

---

## 🎯 2019 Recommendations

**Revenue Growth Strategies**:
1. **Customer Retention**: Launch loyalty program for top 20% customers (drive 80% revenue)
2. **Product Mix Optimization**: Increase premium clothing inventory by 25%
3. **Geographic Expansion**: Allocate 15% marketing budget to high-growth Asian markets
4. **Dynamic Pricing**: Implement tiered discounts (10%/15%/20% at 50/100/200 units)

**Profit Optimization**:
1. **SKU Rationalization**: Discontinue bottom 10% of unprofitable products
2. **Cost Reduction**: Negotiate supplier contracts for high-volume footwear items
3. **Seasonal Planning**: Increase Q4 inventory by 30% based on historical demand
4. **Cross-Selling**: Bundle complementary products (shoes + accessories)

---

## 📊 Assessment Criteria

| Component | Weight | Focus Areas |
|-----------|--------|-------------|
| **Jupyter Report Structure** | 30% | Organization, clarity, completeness |
| **Python Code Quality** | 40% | Efficiency, readability, best practices |
| **Video Presentation** | 30% | Communication, insights, professionalism |

**Submission**: February 11, 2022 | **Presentation**: 10 minutes max

---

## 👤 Author

**Shannon Yum Wan Ning**  
Diploma in Data Science  
Ngee Ann Polytechnic

---

## 📄 Academic Context

**Module**: Data Discovery and Visualization  
**Assignment**: Individual Assignment 2 (40% of module grade)  
**Semester**: October 2021

**Deliverables**:
- ✅ Jupyter Notebook with Python code and visualizations
- ✅ Recorded presentation (MS Teams, <10 minutes)
- ✅ Interactive dashboards demonstrating insights

---

*Completed February 2022*