# 📱 Google Play Store Data Analysis

## 📌 Overview

This project focuses on cleaning, analyzing, and transforming Play Store data to uncover meaningful patterns and insights. It involves comprehensive data preprocessing, exploratory data analysis (EDA), and feature engineering to prepare the dataset for further use in machine learning workflows.

---

## 🔍 Key Features

* 🧹 **Data Cleaning:** Handled missing values in key columns such as Rating, Type, and Content Rating
* ⚙️ **Feature Engineering:** Converted columns like `Reviews`, `Size`, `Installs`, and `Price` into usable numeric formats
* 📅 **Date Transformation:** Extracted Day, Month, and Year from the `Last Updated` feature
* 🗑️ **Duplicate Removal:** Removed 1,181 duplicate records to ensure data consistency
* 📊 **EDA & Visualization:** Analyzed distributions of categories, ratings, and app types (Free vs Paid)

---

## 📊 Dataset Information

The dataset contains information on 10,000+ apps with key attributes such as:

* **App:** Application name
* **Category:** App category (e.g., Family, Game, Tools)
* **Rating:** User rating (1.0 to 5.0)
* **Reviews:** Number of user reviews
* **Installs:** Number of installations
* **Type:** Free or Paid
* **Price:** Cost of the app

---

## 📈 Key Insights

* 📌 **Top Categories:** Family (18.9%), Game (9.9%), and Tools (8.5%) dominate the dataset
* 📌 **App Type:** ~92% of apps are Free
* 📌 **Content Rating:** Over 81% of apps are rated for “Everyone”

---

## 🛠️ Tech Stack

Python | Pandas | NumPy | Matplotlib | Seaborn

---

## 🚀 How to Run

1. Clone the repository
2. Ensure `googleplaystore.csv` is available in the project directory
3. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Run the Jupyter Notebook to explore the analysis

---

## ⚠️ Note

The notebook may take time to load on GitHub due to visualizations. For better performance, run it locally.

---

## ⭐ If you found this useful, consider giving a star!
