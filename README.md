# 🚗 used-car-market-analysis-hyderabad
### *Web scraping and EDA of Hyderabad's used car market using Python*
This project analyzes Hyderabad’s growing used car market by combining **web scraping** and **exploratory data analysis**, uncovering insights on pricing, market trends, and buyer–seller behaviors.

## 📌 Project Overview
The goal of this project is to extract real-time used car listings from **CarTrade.com**, clean and analyze the data, and generate insights into the dynamics of Hyderabad’s pre-owned car market.

The project demonstrates:
- End-to-end web scraping
- Data cleaning & wrangling
- EDA & visualization
- Real-world business insights

## 🔍 Problem Statement
Hyderabad’s used car buyers and sellers lack transparency on factors influencing pricing, such as:

- Car brand
- Vehicle age
- Mileage
- Fuel type
- Location

This results in inconsistent pricing and poor decisions.

## 🎯 Objective
To scrape and analyze used car listings in order to understand:

- Pricing trends
- Resale value behavior
- Location-wise price variation
- Brand dominance and demand patterns
- Depreciation trends

The ultimate goal is to enable **data-driven decision making** for buyers, sellers, and listing platforms.

## 🛠 Tech Stack
| Component | Tools |
|----------|-------|
| **Web Scraping** | BeautifulSoup |
| **Data Handling** | pandas |
| **Visualization** | matplotlib, seaborn |
| **Language** | Python |

## ⚙ Methodology
### ✔ Data Extraction
- Scraped **700+ used car listings** from CarTrade.com
- Fetched brand, model, price, km driven, fuel type, owner type, and location

### ✔ Data Cleaning
- Removed duplicates
- Cleaned missing fields
- Converted price & mileage into numeric formats

### ✔ Exploratory Data Analysis
Conducted:
- **Univariate Analysis**
- **Bivariate Analysis**
- **Multivariate Analysis**

Created visualizations for:
- Price distribution
- Brand dominance
- Depreciation trends
- Location-based price differences

## 📈 Key Insights
### 🔹 Market Patterns
- **Maruti and Hyundai** dominate listings.
- **Petrol cars** are most common, while **diesel cars** retain value better at high mileage.

### 🔹 Depreciation Insights
- **3–7 year-old vehicles** offer the best value.

### 🔹 Location Insights
- **Somajiguda & Madhapur** → higher price zones.
- **LB Nagar** → budget-friendly listings.

### 🔹 Behavioral Insight
- Cars without **test-drive availability** often fall in higher price brackets.

## 📊 Impact & Use Cases
### ✅ For Buyers
- Identify high-value deals
- Avoid overpriced cars

### ✅ For Sellers
- Set competitive prices
- Understand depreciation

### ✅ For Platforms
- Improve recommendations
- Build pricing intelligence tools

## 📁 Project Structure
```
Used-Cars-EDA/
│── EDA_Project.ipynb
│── Web_Scraping.ipynb
│── Car_data.csv
│── README.md
```

## ▶ How to Run This Project
### 1. Clone the Repository
```
git clone https://github.com/SaiPraneethMarripelli/used-car-market-analysis-hyderabad.git
```

### 2. Install Dependencies
```
pip install pandas matplotlib seaborn beautifulsoup4
```

### 3. Open Notebook
```
jupyter notebook EDA_Project.ipynb
```

## 🚀 Future Improvements
- Multi-city expansion
- ML-based price prediction
- Automated scraping
- Power BI/Tableau dashboard
- Web app deployment

## 👤 Author
**Sai Praneeth Marripelli**  
📧 saipraneethmarripelli@gmail.com  
🔗 LinkedIn: http://www.linkedin.com/in/saipraneeth-marripelli-2003sai

## ⭐ Support
If this project helped you, please ⭐ the repository!
