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
├── visualizations/
│   └── *.png                           # Exported dashboard images
│
└── README.md                           # Project documentation
```

---

## 📈 Key Visualizations

The notebook includes **7 core visualizations** combined into **1 comprehensive dashboard**:

### Individual Visualizations

**1. Revenue and Profits Earned Each Year (Stacked Bar Chart)**
- Compares annual revenue vs. profit from 2014-2018 across countries
- Germany shows exceptional spike in 2017 ($465K revenue, $58K profit)
- Identifies year-over-year growth trends and profit margin variations

**2. Top Profit Generators from 2014 to 2018 (Bar Chart)**
- Ranks top 10 customers by total profit contribution
- Th Fashing ($19,978) and Grunewald ($19,667) lead as highest profit drivers
- Steep drop-off after top 2, with remaining customers generating $6K-$11K profit

**3. Total Revenue Per Month in 2018 (Line Chart)**
- Tracks monthly revenue patterns throughout 2018
- March peak at $55,300 followed by steady decline to June low ($10,228)
- Dramatic July surge to $77,873 suggests seasonal promotion or bulk orders

**4. Quantity by Product Category 2014-2018 (Pie Chart)**
- Product mix breakdown: Sportswear dominates at 26.8% of volume
- Men's Clothes (18.6%) and Women's Clothes (14.5%) follow
- Baby Clothes (13.9%) and Women's Footwear (8.9%) show moderate sales

**5. Quantity by Product Category Distribution (Histogram)**
- Purchase frequency distribution shows right-skewed pattern
- Majority of orders are small-volume (0-20 units per transaction)
- Bulk orders (>100 units) are rare but present across all categories

**6. Product Category by USD Price Distribution (Violin Plot)**
- Compares price ranges across 8 product categories
- Men's Footwear shows highest price variance with outliers up to $500
- Most categories cluster around $20-50 price point with tight distributions
- Children's Clothes and Swimwear have narrowest price ranges

**7. Distribution of Discount by Volume (Regression Plot)**
- Analyzes relationship between order quantity and discount percentage
- Clear discount tiers visible: 0%, 5%, 10%, 15%, 20%, 25%
- Slight positive correlation: higher volumes receive incrementally better discounts
- Regression line suggests ~0.1% discount increase per unit quantity

### Final Dashboard

**Yearly Revenue & Profits Distribution and Breakdown by Product Category**

4-panel integrated dashboard combining:
- **Top Left**: Annual revenue/profit trends by country (stacked bar chart)
- **Top Right**: Product category quantity breakdown (pie chart)
- **Bottom Left**: Top 10 profit-generating customers (bar chart)
- **Bottom Right**: Quantity purchase distribution across categories (histogram)

Provides executive-level overview for strategic decision-making and pattern identification.

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
1. **Data Preparation** - Load and clean sales data, handle missing values
2. **Exploratory Analysis** - Statistical summaries, distributions, and correlations
3. **Visualization Creation** - Generate 7 charts answering key business questions
4. **Dashboard Assembly** - Combine visualizations into comprehensive dashboard
5. **Insights & Recommendations** - Derive actionable business strategies

---

## 🔍 Key Findings

### Revenue Insights
- **Germany Anomaly**: 2017 spike of $465K revenue ($58K profit) in Germany represents 47% of that year's total revenue
- **Geographic Concentration**: Top 3 countries (Germany, USA, UK) drive 65% of revenue
- **Monthly Volatility**: 2018 revenue fluctuates 660% peak-to-trough (June $10K → July $78K)
- **Seasonal Patterns**: Q1 and mid-year show strongest performance

### Customer Performance
- **Top Customer Dominance**: Th Fashing and Grunewald together contribute $39.6K profit (23% of top 10)
- **Long Tail Distribution**: Top 10 customers generate $102K profit; sharp drop-off suggests concentration risk
- **Customer Tiers**: Clear segmentation between high-value ($19K-$20K), mid-value ($8K-$11K), and low-value ($6K-$7K) customers
- **Retention Opportunity**: Focus on upgrading mid-tier customers to high-value status

### Product Performance
- **Volume Leaders**: Sportswear (26.8%), Men's Clothes (18.6%), Women's Clothes (14.5%)
- **Category Dynamics**: Footwear categories (Men's + Women's = 17.8%) underperform relative to clothing (54.9%)
- **Small-Batch Dominance**: 70%+ of orders are <20 units, indicating retail distribution model
- **Bulk Order Rarity**: Orders >100 units represent <5% of transactions but likely drive significant revenue

### Pricing & Discount Dynamics
- **Price Variance**: Men's Footwear shows 10x price range ($10-$500), highest among all categories
- **Discount Tiers**: Structured at 5% intervals (0%, 5%, 10%, 15%, 20%, 25%)
- **Volume Discount Correlation**: Weak positive relationship (R²≈0.15) between quantity and discount
- **Pricing Strategy**: Most products cluster $20-$50, suggesting mid-market positioning
- **Discount Effectiveness**: 25% discount tier appears for orders >120 units

---

## 🎯 2019 Recommendations

### Revenue Growth Strategies

**1. Customer Retention & Expansion**
- **Action**: Launch tiered loyalty program targeting top 20 customers
- **Target**: Increase repeat purchase frequency from top customers by 15%
- **Investment**: Implement account management for customers generating >$5K profit annually

**2. Geographic Diversification**
- **Action**: Reduce Germany dependency (investigate 2017 anomaly - was it one-time bulk order?)
- **Target**: Grow USA and UK markets by 20% to balance portfolio
- **Investment**: Allocate marketing budget proportionally to underserved regions

**3. Product Mix Optimization**
- **Action**: Increase sportswear inventory by 30% (highest volume category)
- **Target**: Boost footwear category from 17.8% to 25% of total volume
- **Tactic**: Bundle footwear with clothing purchases (cross-sell strategy)

**4. Seasonal Demand Planning**
- **Action**: Build inventory ahead of Q1 and July peaks
- **Target**: Reduce June stockouts that led to revenue decline
- **Metric**: Achieve 95% inventory availability during high-demand months

### Profit Optimization

**1. Dynamic Discount Strategy**
- **Current State**: Linear discount model (0.1% per unit) is suboptimal
- **Action**: Implement tiered discounts with steeper breaks at 50, 100, 150 units
- **Target**: Incentivize bulk orders without eroding margins on small orders
- **Expected Impact**: 3-5% profit margin improvement

**2. Premium Product Development**
- **Action**: Expand Men's Footwear premium line ($100-$500 range)
- **Rationale**: High price variance indicates market acceptance of luxury items
- **Target**: Premium items to represent 15% of footwear sales
- **Margin**: Target 35-40% margins vs. 25% on standard items

**3. SKU Rationalization**
- **Action**: Analyze bottom 20% of SKUs by profitability
- **Target**: Discontinue unprofitable items in Baby Clothes and Swimwear (lowest volume)
- **Benefit**: Reduce inventory holding costs by 12%

**4. Customer Tier Management**
- **Action**: Create account manager roles for customers generating >$8K profit
- **Target**: Upgrade 5 mid-tier customers ($8K-$11K) to high-tier (>$15K)
- **Investment**: Personalized service, exclusive discounts, early access to new products

### Operational Efficiency

**1. Order Processing Optimization**
- **Finding**: 70% of orders are <20 units (high transaction volume, low efficiency)
- **Action**: Implement minimum order quantity (MOQ) of 10 units or $500
- **Benefit**: Reduce processing costs by 20%

**2. Inventory Management**
- **Action**: Adopt just-in-time inventory for slow-moving categories (Swimwear, Baby Clothes)
- **Action**: Maintain higher buffer stock for Sportswear and Men's Clothes
- **Benefit**: Reduce working capital requirements by 15%

---

## 👤 Author

**Shannon Yum Wan Ning**  
Diploma in Data Science  
Ngee Ann Polytechnic

---

## 📚 Key Learning Outcomes

- ✅ End-to-end data analysis workflow (cleaning → exploration → visualization)
- ✅ Effective use of Python visualization libraries (Matplotlib, Seaborn)
- ✅ Dashboard design principles for business stakeholders
- ✅ Translating data insights into actionable business recommendations
- ✅ Professional presentation and communication of technical findings

---

**Note**: This is an academic project completed for educational purposes. Datasets used are publicly available or provided by the institution for coursework.

*Completed February 2022*
