# 📊 Blinkit Sales Analysis — Data Analytics Project

This repository contains an end-to-end Exploratory Data Analysis (EDA) performed on the Blinkit dataset using Python in Jupyter Notebook. The primary objective of this project is to uncover actionable insights related to sales performance, product characteristics, and outlet attributes, helping understand the factors that influence revenue across different categories.

# 🗂️ Project Overview

In this analysis, we explore how different features—such as Item Type, Item Fat Content, Outlet Size, Outlet Location, Item Visibility, and Item Weight—affect Sales and Customer Ratings.

The notebook includes:

🔹 Data Cleaning & Preprocessing

🔹 Descriptive Statistics

🔹 Visual Exploratory Data Analysis

🔹 Correlation Study

🔹 Key Business Insights & Findings

# 📁 Dataset Description

The dataset includes 1,000+ retail product entries with the following key features:

Column Name	Description
Item Identifier	Unique code assigned to each product
Item Type	Category of the product (e.g., Fruits & Vegetables, Snacks, Frozen Foods, etc.)
Item Fat Content	Indicates whether the item is Low Fat / Regular
Item Weight	Weight of the product
Item Visibility	The shelf visibility of the item
Outlet Identifier	Unique ID for each outlet
Outlet Establishment Year	Year in which the outlet was opened
Outlet Size	Size category — Small / Medium / High
Outlet Location Type	Location Tier — Tier 1, Tier 2, Tier 3
Outlet Type	Type of store (Supermarket Type1/2/3, Grocery Store)
Sales	Total sales value for each item
Rating	Customer ratings for the item
# 🔧 Technologies Used

Python

Pandas & NumPy — Data Cleaning & Manipulation

Matplotlib & Seaborn — Data Visualization

Jupyter Notebook

# 🧹 Data Cleaning Steps

Handled missing values in Item Weight

Standardized inconsistent categories in Item Fat Content

Converted data types where necessary

Removed outliers based on Item Visibility and Sales

# 📈 Key Visualizations

This analysis includes:

Distribution plots (Sales, Ratings, Weight)

Category-wise sales comparison (Item Type, Outlet Size, Outlet Type)

Outlet Performance Comparison

# 🧠 Insights & Conclusions

Some insights derived (you can adjust based on your notebook results):

💡 Outlet Size and Outlet Type have a strong influence on sales. Medium-sized and Supermarket Type1 outlets perform better.

💡 Item Visibility is inversely correlated with Sales — heavily visible items sometimes sell less due to overexposure.

💡 Fruits & Vegetables, Snacks, and Household items contribute majorly to sales.

💡 Low Fat vs Regular Fat items showed minimal difference in sales performance.

💡 Outlets established earlier show more stable and higher sales trends.
