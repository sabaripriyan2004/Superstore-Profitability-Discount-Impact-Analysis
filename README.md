# Superstore-Sales-Profitability-Analysis
Retail Sales Analysis using Python, MySQL and Power BI

 📌 Project Overview

This project focuses on analyzing retail sales data to identify business performance, profitability trends, loss-making products, and opportunities for improving business decisions.

Using **Python, SQL, and data visualization**, I performed exploratory data analysis (EDA) and business analysis to understand how product categories, discounts, customer segments, shipping methods, and geographical locations influence profitability.

The primary objective is to transform raw sales data into meaningful business insights and provide actionable recommendations to improve overall profitability.

---

## 🛠️ Tools & Technologies

- **Python:** Data analysis and preprocessing
- **Pandas:** Data manipulation and aggregation
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualization
- **Seaborn:** Statistical visualization
- **MySQL:** SQL-based business analysis
- **Jupyter Notebook:** Analysis environment
- **GitHub:** Project documentation and version control

---

## 📁 Dataset Overview

The project uses the Superstore retail sales dataset.

| Metric | Value |
|---|---:|
| Total Records | 9,994 |
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Total Quantity Sold | 37,873 |
| Overall Profit Margin | 12.47% |

### Key Dataset Columns

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

---

## 🔍 Project Workflow

### 1. Data Loading and Inspection
- Imported the dataset using Pandas.
- Examined dataset structure, dimensions, and data types.
- Identified missing values and duplicate records.
- Checked numerical and categorical columns.

### 2. Data Cleaning and Preprocessing
- Handled missing and duplicate records where appropriate.
- Standardized column names and data formats.
- Validated numerical values.
- Checked data consistency and quality.

### 3. Exploratory Data Analysis (EDA)
- Analyzed sales and profit distributions.
- Examined category and sub-category performance.
- Investigated regional and state-level profitability.
- Analyzed discount distribution.
- Compared customer segment performance.

### 4. SQL Business Analysis
Used MySQL to answer six key business questions through aggregation, filtering, grouping, conditional logic, and ranking.

---

## 🎯 Key Business Questions

1. Which product categories and sub-categories are the most profitable, and which are consistently losing money?
2. Which regions and states generate the highest profit, and which are reducing overall profitability?
3. Is there a relationship between discount percentage and profit? At what discount level does profitability become negative?
4. Which customer segments are the most and least profitable?
5. Does shipping mode have a noticeable relationship with profit margins?
6. What are the top 10 loss-making products, and what do they have in common in terms of category, discount level, and region?

---

## 📈 Key Business Findings

### 1. Category Profitability

| Category | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Furniture | $741,999.80 | $18,451.27 | 2.49% |
| Office Supplies | $719,047.03 | $122,490.80 | 17.04% |
| Technology | $836,154.03 | $145,454.95 | 17.40% |

**Insight:** Technology is the most profitable category, while Furniture has significantly lower profitability despite generating substantial sales.

### 2. Sub-Category Profitability

**Loss-making sub-categories:**
- Tables: -$17,725.48
- Bookcases: -$3,472.56
- Supplies: -$1,189.10

**Insight:** Tables generate the highest financial loss among the identified loss-making sub-categories.

Copiers are the most profitable sub-category, generating $55,617.82 in profit with a 37.20% margin.

### 3. Regional Performance

| Region | Profit | Profit Margin |
|---|---:|---:|
| West | $108,418.45 | 14.94% |
| East | $91,522.78 | 13.48% |
| South | $46,749.43 | 11.93% |
| Central | $39,706.36 | 7.92% |

**Insight:** West is the strongest-performing region, while Central has the lowest profit margin.

### 4. Discount Analysis

| Discount Bucket | Profit Margin |
|---|---:|
| No Discount | 29.5% |
| Low | 11.9% |
| Medium | -15.3% |
| High | -40.7% |
| Very High | -122.6% |

**Insight:** Higher discount levels are associated with declining profitability. The very high discount bucket demonstrates substantial negative profitability.

### 5. Customer Segment Analysis

| Segment | Profit Margin |
|---|---:|
| Consumer | 11.55% |
| Corporate | 13.03% |
| Home Office | 14.03% |

**Insight:** Home Office customers generate the highest profit margin, while Consumer customers have the lowest.

### 6. Geographical Loss Analysis

The analysis identified 10 loss-making states.

- Texas: Highest total loss (-$25,729.36).
- Ohio: Lowest profit margin (-21.69%).
- Pennsylvania: -$15,559.96.
- Illinois: -$12,607.89.

**Insight:** Texas and Ohio require further investigation to identify the products, discounts, and transactions contributing to their losses.

### 7. Product-Level Analysis

The top 10 loss-making products were identified using product-level profit aggregation.

Products including Cubify CubeX 3D printers and the Lexmark MX611dhe printer appeared among the largest loss-making products.

**Insight:** Product-level investigation helps identify specific products that require pricing, discount, and cost optimization.

---

## 📊 Visualizations

The project includes visualizations to communicate business performance and analytical findings.

Key visualizations include:

- Profit Margin by Discount Bucket
- Discount vs Profit Scatter Plot
- Loss-Making States
- Profit Margin by Customer Segment
- Top 10 Loss-Making Products
- Category and Sub-Category Profitability

---

## 💡 Business Recommendations

Based on the analysis, the following recommendations were identified:

1. **Discount Optimization:** Review excessive discount strategies, particularly discounts above 30%, to protect profitability.
2. **Product Optimization:** Investigate loss-making products such as Tables and Bookcases.
3. **Regional Improvement:** Analyze underperforming states, particularly Texas and Ohio.
4. **Category Strategy:** Focus on maintaining the profitability of Technology and Office Supplies.
5. **Customer Strategy:** Investigate the factors contributing to higher Home Office profitability.
6. **Pricing Strategy:** Review product pricing and associated costs for consistently loss-making products.

---

## 🏁 Conclusion

This project demonstrates how Python and SQL can be used to analyze retail sales data, identify profitability trends, investigate loss-making products, and answer real-world business questions.

The analysis highlights that high sales do not necessarily translate into high profits. Discount management, product-level profitability, customer segmentation, and geographical performance are important factors to consider when improving business profitability.

The project strengthened my practical understanding of data cleaning, exploratory data analysis, SQL querying, data visualization, and business insight generation.

---


*If you find this project useful, feel free to explore the repository and share your feedback.*
