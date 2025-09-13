# Sprint 03 - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project is part of the TripleTen Data Analytics Post Graduation (Sprint 03).  
The main goal was to practice **Exploratory Data Analysis (EDA)** using Python, focusing on analyzing a retail dataset from Instacart.

The tasks included loading datasets with pandas, exploring data structures, handling missing values, summarizing statistics, and visualizing distributions and relationships among variables.

## 🎯 Objective
Gain hands-on experience in **data cleaning, exploration, and visualization**, identifying patterns and insights in a retail dataset.

## 📂 Dataset
**Files:**
- `/aisles.csv` – list of product aisles  
- `/departments.csv` – list of product departments  
- `/products.csv` – product information  
- `/instacart_orders.csv` – orders made by users  
- `/order_products.csv` – products included in each order  

**Key Columns:** `order_id`, `user_id`, `product_id`, `aisle_id`, `department_id`, `add_to_cart_order`, `reordered`.

## 📝 Steps

1. **Data Overview**  
   - Checked column types, unique values, and missing data.  
   - Observed relationships between products, departments, and aisles.

2. **Data Cleaning**  
   - Handled missing values and verified data consistency.  
   - Extracted useful information for analysis (e.g., number of products per order, reorder rates).

3. **Exploratory Analysis**  
   - Aggregated product counts by department and aisle.  
   - Analyzed user ordering behavior, including frequency and reorder patterns.  
   - Created visualizations to show distributions, trends, and correlations.

## 📊 Results
- Certain departments and aisles have higher reorder rates.  
- Most users tend to reorder the same products multiple times.  
- Visualization helped identify popular products and seasonal trends.

## 🏁 Conclusion
EDA provides a clear understanding of the dataset structure and user behavior patterns, forming a foundation for predictive modeling or deeper analytics in future sprints.

## 🛠 Tools & Technologies
- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 🗂 Repository Structure
sprint-03-EDA/  
│  
├── README.md  
├── aisles.csv  
├── departments.csv  
├── instacart_orders.csv  
├── order_products.csv  
├── products.csv  
└── sprint-03-EDA.ipynb  

- `README.md` –  Project documentation and overview  
- `sprint-03-EDA.ipynb` – Jupyter Notebook containing all tasks and solutions  
- CSV files – raw data used for analysis
