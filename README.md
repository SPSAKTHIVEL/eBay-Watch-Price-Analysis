# eBay-Watch-Price-Analysis

## Introduction

This project presents an end-to-end data science solution focused on analyzing and predicting watch prices using real-world e-commerce data. The workflow covers data collection through web scraping, exploratory data analysis, supervised and unsupervised machine learning, database integration using SQL, and visualization using Power BI.

---

## Web Scraping Using Python

The dataset was collected using Python-based web scraping techniques. Requests were used to fetch web pages, and BeautifulSoup was used to parse HTML content. Product details such as name, brand, department, display type, and price were extracted from multiple product listings and stored in a structured dataset for further analysis.

---

## Dataset

The dataset contains product-level information including watch name, brand, department, display type, and price. Data preprocessing was performed to clean the price field, handle missing values, standardize text formats, and ensure consistency across all columns.

---

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand price distributions and relationships between features. Analysis revealed significant variation in pricing across brands and departments. EDA helped identify patterns, outliers, and trends that influenced feature selection and model design.

---

## Supervised Learning

Supervised machine learning models were trained to classify watches into price categories such as low, medium, and high. Models including Logistic Regression, Random Forest, Gradient Boosting, and K-Nearest Neighbors were implemented. Data was split into training and testing sets, and categorical features were encoded before training.

---

## Unsupervised Learning

Unsupervised learning techniques were applied to identify natural groupings in the data. K-Means clustering was used after dimensionality reduction with Principal Component Analysis. The optimal number of clusters was determined using the Elbow Method and Silhouette Score.

---

## Model Evaluation

Models were evaluated using accuracy and weighted F1-score metrics. Ensemble-based models showed better overall performance compared to linear and distance-based approaches. The evaluation helped determine the most suitable model for price category prediction.

---

## SQL Integration

The processed dataset was stored in a MySQL database using SQLAlchemy. Structured tables were created, and SQL queries were used to analyze pricing trends, retrieve high-value products, and support downstream visualization tasks.

---

## Power BI Dashboard

The MySQL database was connected to Power BI to create an interactive dashboard. Key metrics such as highest-priced products and price distribution by brand and department were visualized using DAX measures and interactive filters.

---

## Conclusion

This project successfully demonstrates an end-to-end data science workflow, integrating data collection, analysis, machine learning, database management, and visualization. The solution provides actionable insights into watch pricing patterns and establishes a scalable foundation for further enhancements.
