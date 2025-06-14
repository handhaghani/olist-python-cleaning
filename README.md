# 🧹 Olist E-Commerce Dataset – Data Cleaning in Python

This repository contains Python code for cleaning the **Olist E-Commerce dataset**, a Brazilian retail dataset frequently used in data analytics and machine learning projects. Dataset is found here:  https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce


## 📦 Dataset Description

The original dataset is provided by Olist and contains information about customer orders, products, sellers, and more. It includes **100K+ records across 9 different CSV files**, each with a unique role in understanding the e-commerce ecosystem.

For efficiency and memory optimization, **the original CSV files were shortened before being loaded into Python**. The cleaning steps demonstrated here still reflect realistic scenarios involving missing values, duplicate records, and formatting inconsistencies.

---

## 📁 Cleaned Datasets

The following 9 datasets were cleaned and exported with a `_1` suffix to indicate the cleaned version:

1. `orders_1.csv`
2. `order_items_1.csv`
3. `order_payments_1.csv`
4. `order_reviews_1.csv`
5. `customers_1.csv`
6. `geolocation_1.csv`
7. `products_1.csv`
8. `sellers_1.csv`
9. `category_translation_1.csv`

However due to the size of the datasets, the cleaned datasets are not uploaded here. 
---

## 🧼 Cleaning Summary

Each dataset underwent:
- **Structural inspection** using `.info()` and `.head()`
- **Missing value checks** and appropriate handling (e.g., row drops)
- **Duplicate detection** and resolution
- **Data type formatting**, such as converting date fields
- **Validation of key fields** (e.g., checking for uniqueness or expected distributions)

---

## 🛠 Tools Used

- Python (Pandas, NumPy)
- Jupyter Notebook

---

## 📊 What’s Next?

The cleaned datasets are ready to be imported into **MySQL** for **Exploratory Data Analysis (EDA)**. The next steps involve running SQL queries to uncover insights about customer behavior, sales trends, and product performance.

---

## 📌 Notes

- This repository only covers **data cleaning**, not modeling or visualization.
- The datasets have been truncated to simplify processing and reduce computational load for demonstration purposes.

---

## 📂 Repository Structure
├── notebooks/
│ └── olist_data_cleaning.ipynb
├── README.md

## 📧 Contact

For feedback or collaboration, feel free to reach out!
