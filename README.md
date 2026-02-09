# 📊 Retail Sales Data Analysis using Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a retail sales dataset to understand
revenue trends, customer behavior, pricing impact, and regional performance.
The goal is to extract **actionable business insights** that help in data-driven decision making.

---

## 🎯 Objectives
- Analyze overall sales and revenue performance  
- Understand customer behavior (New vs Returning customers)  
- Identify top-performing cities, regions, and categories  
- Study the impact of pricing and discounts on revenue  
- Detect outliers and data quality issues  
- Provide meaningful business recommendations  

---

## 🗂 Dataset Description
The dataset contains transactional sales data with the following columns:
- order_id  
- order_date  
- city, region  
- product, category  
- customer_type  
- unit_price, final_unit_price  
- quantity  
- discount_percent  
- revenue  
- payment_method  
- sales_channel  

---

## 🧹 Data Cleaning & Preprocessing
The following steps were performed:
- Handling missing values  
- Removing duplicate order IDs  
- Fixing invalid quantities and prices  
- Standardizing city and region names  
- Converting date columns to datetime format  
- Detecting outliers using **IQR and Z-score methods**  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Descriptive Analysis
- Total and average revenue  
- Top products, categories, cities, and regions  
- Median quantity per order  
- Sales channel contribution  

### 2. Time-Based Analysis
- Monthly revenue trend  
- Highest and lowest sales months  
- Seasonality patterns  
- Weekend vs weekday sales  
- Quarterly revenue analysis  

### 3. Customer Behavior Analysis
- New vs Returning customer spending  
- Revenue share by customer type  
- City-wise returning customer ratio  
- Discount usage analysis  

### 4. Pricing & Discount Insights
- Average discount percentage  
- Category-wise discount comparison  
- Correlation between price, discount, quantity, and revenue  
- Identification of loss-making transactions  

### 5. Geographic Analysis
- Top revenue-generating cities  
- Lowest-performing regions  
- Category preference across regions  
- City-wise demand for Electronics and Fashion  

### 6. Outlier Detection
- Price and revenue outliers using IQR  
- Identification of premium vs erroneous transactions  
- Impact of outlier removal on average revenue  

---

## 📊 Visualizations
- Monthly revenue line chart  
- Top products bar chart  
- Category-wise revenue pie chart  
- Correlation heatmap  
- City vs category pivot heatmap  

---

## 💡 Key Business Insights
- Revenue is concentrated in a few major cities  
- Returning customers generate higher value  
- Heavy discounts do not always improve revenue  
- Certain categories show strong expansion potential  
- Data quality issues can distort business metrics  

---

## 🧠 Business Recommendations
- Increase marketing budget for top-performing cities  
- Focus expansion on high-revenue categories  
- Reduce blanket discounts and use targeted offers  
- Prioritize the best-performing sales channel  
- Improve data validation and quality checks  

---

## 🛠 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📁 Project Structure
