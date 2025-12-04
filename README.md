# Uncovering Smartphone Market Patterns in Singapore Through API Data Collection and EDA
This project explores smartphone market patterns in Singapore using data collected from an API. Through data cleaning and exploratory analysis, it uncovers brand popularity, pricing trends, and customer rating behavior to provide data-driven insights into consumer preferences.


## 📦 Data Source
- **API:** Real-Time Amazon Data  
- **Provider:** RapidAPI  
- **Link:** https://rapidapi.com/letscrape-6bRBa3QguO5/api/real-time-amazon-data

## 🛠 Tools Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 📘 About the Data
- **Rows/Columns:** 306 rows × 24 columns  
- **Collection Method:** API request  
- **Domain:** Smartphone listings from Amazon Singapore (sorted by Best Seller)

---

## 🧹 Data Cleaning
Steps performed:
- Handling missing values  
- Handling duplicates  
- Standardizing formats (including currency conversion)  
- Outlier detection using IQR  
- Flagging invalid/incomplete records  

---

## 📊 Exploratory Data Analysis (EDA)
The analysis covers:
- Brand popularity  
- Price distribution  
- Price segmentation (<600 SGD)  
- Correlation between price and star rating  
- Rating distribution by brand  

---

## 🔍 Insights
- **Samsung and Xiaomi** are the most frequently searched smartphone brands on Amazon Singapore, followed by **Oppo**.  
- Most smartphone products are **priced below 600 SGD**, indicating a market dominated by **budget and mid-range devices**.  
- When focusing on smartphones under 600 SGD, **Samsung, Xiaomi, and Oppo** remain the **top three most-searched brands**.  
- There is **no significant correlation** between price and star rating — customer satisfaction does not depend on how expensive a device is.  
- The same pattern holds when analyzing only sub-600 SGD products.  
- Brands with **higher average ratings** can help set expectations for product reliability and customer satisfaction.

---

## 💡 Recommendations
- **Prioritize stocking Samsung and Xiaomi** devices due to high search demand.  
- **Highlight mid-range phones (<600 SGD)**, as they dominate the market distribution.  
- Promote **Oppo and Xiaomi** for budget-focused segments due to strong search presence and value positioning.  
- Since **price does not influence ratings**, emphasize **quality, features, and user reviews** in marketing strategies.  
- Create curated sections like **“Top Rated Phones Under 600 SGD”** to boost consumer trust.  
- Run **A/B tests** comparing feature-based vs. price-based promotional content to optimize conversions.

---

## ⚠️ Limitations
- The dataset only includes **search data**, not purchase or transaction data.  
- No **demographic** information is available.  
- Data represents a **limited time period**, so long-term trends may differ.

---
