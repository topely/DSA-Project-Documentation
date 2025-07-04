
# 📦 Amazon Product Review Analysis

**Author:** Temitope Noah  
**Role:** Junior Data Analyst, RetailTech Insights  
**Date:** 4th July, 2025  

---

## 🏢 About the Company

**RetailTech Insights** is a data analytics firm that empowers Amazon sellers with actionable insights derived from e-commerce data. This project is part of a data analysis initiative focused on helping sellers make informed decisions through customer review analytics.

---

## 📌 Project Overview

This case study involved a comprehensive analysis of Amazon product review data to:

- Identify top-performing products
- Evaluate pricing and discount strategies
- Understand customer sentiment and engagement
- Provide actionable insights for:
  - Product improvement
  - Marketing strategies
  - Customer engagement

---

## 📊 Dataset Overview

- **Total Products:** 1,465  
- **Categories:** 16  
- **Key Variables:**  
  - Product Name & Category  
  - Actual Price & Discounted Price  
  - Discount %  
  - Ratings (1–5 stars)  
  - Review Counts  
  - Review Titles & Content  

### 🔧 Data Cleaning

- Removed duplicates and nulls  
- Standardized formats  
- Created calculated fields:
  - `Discounted_Price = Actual_Price * (1 - Discount%)`
  - `Potential_Revenue = Actual_Price * Review_Count`

---

## 🛠 Tools & Techniques

### Tools Used

- **Primary:** Microsoft Excel (PivotTables, Charts, Dashboarding)  
- **Secondary:** Python (Pandas, Matplotlib for exploratory plots)

### Analysis Methods

- Descriptive Statistics  
- Comparative Analysis  
- Correlation Analysis  
- Segmentation (Price Buckets, Rating Tiers)

---

## 📈 Key Insights

### 🔹 Product Performance

| Category         | Avg. Rating | Avg. Discount | Total Reviews |
|------------------|-------------|----------------|----------------|
| Electronics      | 4.3         | 35%            | 250,000        |
| Home & Kitchen   | 4.5         | 20%            | 180,000        |
| Books            | 4.1         | 10%            | 50,000         |

- **Insight:** Electronics lead in reviews and discounts, while Home & Kitchen leads in ratings.

### 🔹 Pricing Strategy

- 120 products (8%) have discounts ≥ 50%  
- Price distribution:
  - `< ₹200`: 25%
  - `₹200 – ₹500`: 60%
  - `> ₹500`: 15%

### 🔹 Customer Engagement

- Top-rated products (4.8+): 15  
- Products with <1,000 reviews: Over 700  
- **Action:** Promote high-rated, low-review products via ads

### 🔹 Correlation Analysis

- Weak correlation between rating and discount (R² = 0.12)  
- Indicates that large discounts don’t always result in better ratings

---

## 📊 Dashboard Features (Excel)

- Dynamic filters: Category, Rating, Price Range
- Visualizations:
  - Discount % by category (Bar Chart)
  - Rating Distribution (Histogram)
  - Price vs Rating (Scatter Plot)
  - Top Products Table (Sortable)

---

## ✅ Deliverables

- ✔️ Cleaned Dataset (Excel)  
- ✔️ Analysis Notebook (Python/Jupyter)  
- ✔️ Interactive Excel Dashboard  
- ✔️ Final Presentation Slides  

📁 **Project Repository Structure**

```
/Amazon_Product_Review_Analysis
│
├── Data/
│   └── amazon_product_reviews.csv
│
├── Analysis_Notebooks/
│   └── product_review_analysis.ipynb
│
├── Visualizations/
│   └── charts_and_graphs.png
│
├── Dashboard/
│   └── amazon_dashboard.xlsx
│
└── README.md
```

---

## 🧠 Recommendations

### For Sellers

- Focus mid-range products with discounts (₹200–₹500)
- Promote well-rated, low-review products with ads
- Use tiered discount strategies (e.g., 3-for-30% deals)

### For RetailTech Insights

- Develop a “Product Health Score” metric
- Implement sentiment analysis for deeper customer understanding
- Predict discount timing based on review & sales trends

---

## 📌 Future Enhancements

- NLP-based Sentiment Analysis of review content  
- Integration with sales data to track post-campaign performance  
- Power BI or Tableau integration for advanced dashboards  

---

## 📬 Contact

**Temitope Noah**  
📧 [temitopenoah12@gmail.com]  
🔗 [LinkedIn] | [GitHub]
