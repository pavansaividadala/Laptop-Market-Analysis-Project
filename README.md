# 💻 Laptop Market Analysis

A data analysis project that scrapes real-world laptop listings from Flipkart and performs a complete Exploratory Data Analysis (EDA) to uncover pricing patterns, brand trends, and spec-to-price relationships.

## 📌 Overview

Online laptop listings hide a lot of useful market signal — which brands dominate, which configurations are most common, and what actually drives price. This project scrapes live Flipkart listings, cleans and structures the data, and analyzes it to answer those questions with visual, data-backed insights.

## 🎯 Objectives

- Collect laptop data from Flipkart using web scraping.
- Extract key details such as price, specifications, discounts, and ratings.
- Perform data cleaning and Exploratory Data Analysis (EDA).
- Identify market trends and generate meaningful insights through visualizations.

## 🗂️ Project Structure

```
├── laptop.ipynb                  # Web scraping, data cleaning, feature engineering & EDA
├── web_scrapping_project.pptx    # Project presentation with findings and visualizations
└── README.md
```

## 🔍 Workflow

1. **Web Scraping** — Scraped multiple Flipkart laptop listing pages for product details.
2. **Extraction** — Pulled out Brand, Processor, RAM, SSD, Display, Price, Discount, and Rating for each listing.
3. **Regex Parsing** — Applied Regular Expressions to pull structured values (RAM size, SSD size, processor type) out of raw, unstructured specification text.
4. **Data Cleaning** — Removed duplicates, handled missing values, standardized data types, converted SSD to GB, and converted discount to numeric.
5. **Feature Engineering** — Created new features: Price Category, Rating Flag, and Discount Category.
6. **EDA & Visualization** — Analyzed the cleaned dataset to surface pricing trends, brand distribution, and spec-to-price relationships.

## 📊 Data Overview

- **Source:** Flipkart
- **Dataset Size:** 500+ laptop records
- **Features:** Brand, Price, Processor, RAM, SSD, Display, Discount, Rating

## 🔎 Problem Statements

- Identify pricing trends across laptop brands.
- Compare processors, RAM, and SSD configurations.
- Analyze customer ratings and discounts.
- Discover factors influencing laptop prices.
- Identify the characteristics of premium laptops.

## 🏆 Key Insights

- **Intel Core i5** is the most common processor, followed by i3 and i7.
- **16 GB RAM** and **512 GB SSD** are the most common configurations in the market.
- HP, ASUS, Acer, Lenovo, and Dell have the largest product ranges.
- Premium laptops mostly feature Intel Core i7 processors with 16–32 GB RAM.
- **RAM and SSD** both show a positive correlation with price — higher specs generally mean higher prices.
- **Discount** shows a negative correlation with price.
- Higher-priced laptops don't always receive higher ratings — price doesn't determine customer satisfaction.
- Discounts vary significantly across brands and models.

## ⚙️ Tech Stack

- **Language:** Python
- **Scraping:** BeautifulSoup, Requests
- **Data Handling:** Pandas, NumPy, Regex
- **Visualization:** Matplotlib, Seaborn

## 🚀 Getting Started

### 1. Clone the repository

```
git clone https://github.com/pavansaividadala/Laptop-Market-Analysis-Project.git
cd Laptop-Market-Analysis-Project
```

### 2. Open the notebook

```
jupyter notebook laptop.ipynb
```

## 🔮 Future Improvements

- Automate scraping to keep the dataset refreshed with current listings.
- Build a price-prediction model on top of the cleaned dataset.
- Deploy an interactive dashboard for exploring the data.

## 🙋 Author

**Pavan Sai**
Aspiring Data Science Engineer | Python · SQL · Machine Learning

---

⭐ If you found this project useful, consider giving it a star!
