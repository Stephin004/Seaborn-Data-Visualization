# Seaborn Data Visualization & Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) and data visualization using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The objective is to analyze customer information, product details, and order data to identify meaningful patterns, understand customer behavior, explore product pricing, and evaluate sales and customer experience.

The project combines three datasets to perform analysis and generate visual insights that support business decision-making.

## Objectives

- Understand and explore customer, product, and order datasets.
- Perform data inspection and data quality checks.
- Analyze customer demographics and membership patterns.
- Explore product categories and pricing distributions.
- Analyze sales, order status, and payment methods.
- Understand delivery performance and customer ratings.
- Identify relationships between numerical variables.
- Generate business insights and actionable recommendations.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive analysis |

## Dataset Description

This project uses three CSV datasets:

### 1. customers.csv

Contains customer information.

- Customer_ID
- Customer_Name
- Age
- Gender
- City
- Membership

### 2. products.csv

Contains product information.

- Product_ID
- Product
- Category
- Price

### 3. orders.csv

Contains order and transaction information.

- Order_ID
- Customer_ID
- Product_ID
- Order_Date
- Quantity
- Discount_Percent
- Delivery_Days
- Rating
- Status
- Payment_Method

## Project Structure

```text
Seaborn-Data-Visualization/
│
├── Seaborn_Assignment.ipynb
├── customers.csv
├── products.csv
├── orders.csv
├── requirements.txt
└── README.md
```

## Analysis Performed

### Part A – Understand the Data
- Dataset dimensions and structure
- Data types and missing values
- Duplicate record identification
- Relationships between datasets
- Merging customer, product, and order information

### Part B – Customer Analysis
- Customer count by city
- Customer age distribution
- Age comparison across membership levels
- Membership distribution by gender

### Part C – Product & Category Analysis
- Product count by category
- Product price comparison
- Price range analysis
- Identification of unusual prices

### Part D – Sales & Order Analysis
- Order status distribution
- Payment method analysis
- Order quantities by product category
- Delivery time distribution
- Delivery time comparison across order statuses

### Part E – Customer Experience Analysis
- Customer rating distribution
- Rating comparison across payment methods
- Customer experience analysis

### Part F – Relationship Analysis
- Relationships between numerical variables
- Correlation analysis
- Scatter plot analysis

### Part G – Multi-Variable Exploration
- Pair plots
- Grouped comparisons
- Strong and weak variable relationships

### Part H – Business Decision Challenge
- Customer acquisition recommendations
- Product pricing review
- Delivery performance and customer satisfaction
- Membership-based customer experience analysis

### Part I – Final EDA Challenge
- Data cleaning and dataset merging
- Creation of multiple Seaborn visualizations
- Distribution and category comparisons
- Correlation heatmap
- Business findings and recommendations

## Visualizations

The project uses different visualization techniques, including:

- Bar Plots
- Histograms
- Box Plots
- Count Plots
- Scatter Plots
- Pair Plots
- Heatmaps
- KDE Plots

These visualizations help identify distributions, patterns, relationships, and differences across customer, product, and order data.

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Stephin004/Seaborn-Data-Visualization.git
```

### 2. Navigate to the project folder

```bash
cd Seaborn-Data-Visualization
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `Seaborn_Assignment.ipynb` and execute the cells.

**Note:** Keep all three CSV files in the same directory as the notebook.

## Key Outcomes

- Explored customer demographics and membership distribution.
- Analyzed product categories and pricing patterns.
- Examined order activity and payment preferences.
- Evaluated delivery performance and customer ratings.
- Identified numerical relationships using correlation analysis.
- Developed data-driven business findings and recommendations.

## Conclusion

This project demonstrates the application of Python-based Exploratory Data Analysis and data visualization techniques to real-world-style business datasets.

By combining customer, product, and order information, the analysis provides insights into customer behavior, product pricing, order activity, delivery performance, and customer satisfaction.

## Author

**Stephin Reji Mathew**

B.Tech Computer Science & Engineering (AI & ML)

GitHub: https://github.com/Stephin004

---

⭐ If you find this project useful, feel free to explore the repository!
