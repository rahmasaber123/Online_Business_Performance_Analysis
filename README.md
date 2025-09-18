# 🛒 Online Business Sales Analysis  

A data-driven analysis of an **online retail company’s sales performance**, focusing on **revenue, profit, customers, and discounts**.  
Includes **feature engineering, time-series analysis, and actionable business insights**.  

---

##  Project Overview  
This project explores an **online business sales dataset** with features related to customers, products, pricing, and transactions.  
It applies **data cleaning, feature engineering, exploratory analysis, and visualization** to uncover patterns and provide **strategic recommendations**.  

---

## 📂 Repository Structure  
├── Online_Business_Sales.ipynb # Main analysis notebook
├── data/ # Dataset(s)
├── images/ # Visualizations for README
├── README.md # Project documentation
└── requirements.txt # Python dependencies

---

### 🔹 Data Cleaning & Preprocessing  
- Handled missing values and formatting issues  
- Converted dates into time-based features  
- Outlier detection (IQR method)  
- Normalized categorical values (e.g., product categories, payment methods)  

### 🔹 Exploratory Data Analysis (EDA)  
- **Univariate & Bivariate analysis** of sales, revenue, and profit  
- Customer demographics vs sales performance  
- Correlation heatmaps for numeric features  
- Regional and seasonal sales breakdowns  
- Discounts vs profit analysis  

### 🔹 Feature Engineering  
- `Revenue` → Derived as `Quantity × Sale Price`  
- `Profit Margin %` → Profitability ratio  
- `Discount Level` → Categorized discount impact  
- `Age Group` → Customer segmentation  
- `Is Weekend` → Flag for weekend vs weekday sales  
- `YearMonth` → Aggregated for time-series trends  

---

## 📊 Key Insights  

### Revenue & Profit Trends  
- 📉 Overall revenue showed **fluctuations** with certain months peaking (e.g., February).  
- 💰 Profit margins were impacted by **discount levels**, showing a trade-off between volume and profitability.  

### Customer Behavior  
-  Male customers contributed slightly more revenue than females.  
-  Age group **30–40 years** was the most active in purchases.  

### Product Performance  
-  Certain **categories and product types** consistently drove higher profits.  
- 📉 Some low-margin products dragged overall profitability despite high sales volume.  

### Discounts & Profitability  
- High discounts → Increased sales volume but **eroded profit margins**.  
- Moderate, well-targeted discounts performed better in balancing **revenue growth** and **profitability**.  

### Regional & Seasonal Insights  
-  Specific regions (e.g., Pennsylvania) contributed steadily to revenue.  
- 🌸 Seasonal impact was limited, though some months showed **spikes in demand** (possibly promotions).  
- 📅 Weekdays consistently outperformed weekends in sales.  

---

## ✅ Suggested Business Actions  
1. **Optimize Discount Policy** → Avoid blanket discounts; use **targeted offers** on underperforming products.  
2. **Customer Segmentation** → Focus marketing on the **30–40 age group**, while expanding appeal to younger buyers.  
3. **Product Strategy** → Promote **high-margin products** and reduce dependence on low-margin, high-discount items.  
4. **Regional Scaling** → Replicate success strategies from strong-performing regions across weaker ones.  
5. **Weekday Promotions** → Leverage **weekday dominance** but create **weekend-exclusive deals** to balance demand.  

---

## 📈 Visualizations  

Here are some of the plots used in the analysis (replace with actual charts):  

- **Monthly Revenue **  
  ![Monthly Revenue](https://github.com/rahmasaber123/Online_Business_Performance_Analysis/blob/main/Month_Revenue.png?raw=true)  
   

- **Top Shipment Providers by Revenue**  
  ![Top Shipment Providers by Revenue](https://github.com/rahmasaber123/Online_Business_Performance_Analysis/blob/main/shipment_reveneu.png?raw=true)  

- **Profit Margin by Discount Level**  
  ![Profit vs Discount](https://github.com/rahmasaber123/Online_Business_Performance_Analysis/blob/main/Revenue_Discount.png?raw=true)
  
- **Top 20 Products by Revenue**
-  ![Top 20 Products by Revenue](https://github.com/rahmasaber123/Online_Business_Performance_Analysis/blob/main/Top_Products_Revenue.png?raw=true)
  

---

## 🚀 Next Steps  
- Apply **predictive modeling** to forecast sales and optimize pricing strategies.  
- Perform **customer segmentation with clustering** for targeted marketing.  
- Build an **interactive dashboard** for real-time monitoring of sales KPIs.  

---

## 🛠️ Tech Stack  
- **Python** (Pandas, NumPy, Seaborn, Matplotlib)  
- **Feature Engineering**  
- **EDA & Visualization**  
- Jupyter Notebook for analysis  

---

## 👩‍💻 Author  
**Rahma Saber**  

---

✨ *This project demonstrates how online business sales data can be leveraged to improve strategy, optimize revenue, and strengthen customer engagement.*  
