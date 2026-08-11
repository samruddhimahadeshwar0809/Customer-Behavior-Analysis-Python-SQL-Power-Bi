# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across multiple product categories. The objective is to identify spending patterns, customer segments, product preferences, and subscription behavior to generate actionable business insights.

## 🛠️ Tools & Technologies

* **Python** – Data Cleaning & Exploratory Data Analysis
* **Pandas** – Data Manipulation
* **PostgreSQL** – Database Integration & SQL Analysis
* **SQL** – Business Analysis
* **Power BI** – Interactive Dashboard & Data Visualization

## 📊 Dataset

The dataset contains **3,900 rows and 18 columns**, covering:

* Customer demographics
* Purchase details
* Product categories
* Purchase amount
* Subscription status
* Discounts and promotions
* Previous purchases
* Purchase frequency
* Review ratings
* Shipping type

There were **37 missing values** in the Review Rating column.

## 🔍 Data Preparation & EDA

Python and Pandas were used to:

* Load and explore the dataset
* Analyze data structure and summary statistics
* Handle missing values using category-level median ratings
* Standardize column names
* Create `age_group`
* Create `purchase_frequency_days`
* Check data consistency and remove redundant fields
* Load the cleaned dataset into PostgreSQL for SQL analysis

## 🧮 SQL Analysis

PostgreSQL was used to answer key business questions, including:

* Revenue by gender
* High-spending customers using discounts
* Top 5 products by rating
* Standard vs. Express shipping performance
* Subscriber vs. non-subscriber spending
* Discount-dependent products
* Customer segmentation into New, Returning, and Loyal
* Top 3 products by category
* Repeat buyers and subscription behavior
* Revenue contribution by age group

## 📈 Power BI Dashboard

An **interactive Power BI dashboard** was created to visually present customer shopping behavior and business insights.

## 💡 Business Recommendations

Based on the analysis:

* **Boost Subscriptions:** Promote exclusive benefits for subscribers.
* **Customer Loyalty:** Reward repeat customers to encourage movement into the Loyal segment.
* **Review Discount Policy:** Balance discount-driven sales with margin control.
* **Product Positioning:** Promote top-rated and best-selling products.
* **Targeted Marketing:** Focus on high-revenue age groups and express-shipping users.

## 🎯 Key Skills Demonstrated

**Python | Pandas | SQL | PostgreSQL | Data Cleaning | EDA | Feature Engineering | Customer Segmentation | Business Analysis | Power BI | Data Visualization**
