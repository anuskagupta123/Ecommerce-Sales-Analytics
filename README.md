# E-Commerce Sales Analytics

## Final Data Analytics Project

## 1. Project Overview

E-Commerce Sales Analytics is an end-to-end data analytics project developed to analyze e-commerce sales performance and identify meaningful business insights.

The project analyzes transactional sales data related to orders, customers, products, categories, regions, customer segments, and shipping methods.

The project follows a complete data analytics workflow:

**Data Preparation → Data Cleaning → Exploratory Data Analysis → Data Visualization → Power BI Dashboard → Business Insights → Recommendations**

Python was used for data preparation, exploratory analysis, and visualization. Microsoft Power BI was used to create an interactive business intelligence dashboard.

---

## 2. Problem Statement

E-commerce businesses generate large amounts of transactional data, but raw data does not directly provide meaningful information for business decision-making.

The objective of this project is to analyze e-commerce sales data and identify:

- Sales trends over time
- High-performing regions
- Best-performing product categories
- Top-selling products
- Customer segment contribution
- Shipping performance
- Important business opportunities

The analysis transforms raw transactional data into meaningful insights that can support data-driven business decisions.

---

## 3. Project Objectives

The main objectives of the project are:

1. Inspect and understand the e-commerce dataset.
2. Clean and prepare the data for analysis.
3. Identify missing and duplicate records.
4. Perform exploratory data analysis.
5. Analyze sales trends.
6. Compare regional sales performance.
7. Analyze product category performance.
8. Identify top-performing products.
9. Analyze customer segments.
10. Analyze shipping performance.
11. Create meaningful visualizations.
12. Develop an interactive Power BI dashboard.
13. Identify key business insights.
14. Provide data-driven recommendations.

---

## 4. Dataset Description

The cleaned dataset contains:

- **9,800 records**
- **24 columns**
- Data covering **2015–2018**
- **4,922 orders**
- **793 customers**
- **1,861 products**
- **3 product categories**
- **4 regions**
- **3 customer segments**
- **4 shipping modes**

### Main Dataset Fields

| Field | Description |
|---|---|
| Row ID | Unique identifier for each row |
| Order ID | Unique order identifier |
| Order Date | Date on which the order was placed |
| Ship Date | Date on which the order was shipped |
| Ship Mode | Shipping method |
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Segment | Customer segment |
| Country | Customer country |
| City | Customer city |
| State | Customer state |
| Postal Code | Customer postal code |
| Region | Geographical sales region |
| Product ID | Unique product identifier |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Product name |
| Sales | Revenue generated |
| Year | Order year |
| Month | Order month |
| Month_Name | Name of the order month |
| Year_Month | Year and month combination |
| Quarter | Order quarter |
| Shipping_Days | Number of days between order and shipment |

---

## 5. Tools and Technologies

### Python

Python was used for:

- Data loading
- Data inspection
- Data cleaning
- Exploratory Data Analysis
- Statistical analysis
- Data visualization

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Microsoft Power BI

Power BI was used for:

- KPI creation
- Interactive visualizations
- Slicers and filters
- Business dashboard development
- Business performance analysis

### Git and GitHub

Git and GitHub were used for:

- Version control
- Project organization
- Commit management
- Repository management
- Project documentation

---

## 6. Data Cleaning and Preparation

The dataset was cleaned and prepared before performing analysis.

The following steps were performed:

### Data Inspection

The dataset was inspected to understand:

- Number of records
- Number of columns
- Column names
- Data types
- Missing values
- Duplicate records

### Missing Value Check

The dataset was checked for missing values.

After the cleaning process, the final dataset contained:

**No missing values.**

### Duplicate Check

Duplicate records were checked to prevent double counting.

After cleaning:

**No duplicate records were present.**

### Date Preparation

Date-related fields were prepared for time-based analysis.

The following analytical fields were used:

- Year
- Month
- Month_Name
- Year_Month
- Quarter

### Shipping Analysis

A `Shipping_Days` field was prepared using the difference between Order Date and Ship Date.

This field was used to analyze shipping performance.

---

## 7. Exploratory Data Analysis

Exploratory Data Analysis was performed to identify important patterns and relationships within the dataset.

The analysis focused on:

- Overall sales
- Year-wise sales trends
- Regional sales
- Category performance
- Customer segments
- Top products
- Shipping performance

---

## 8. Data Visualizations

The following visualizations were created:

### 1. Sales Trend by Year

Shows the change in sales across different years.

### 2. Sales by Region

Compares sales performance across the four regions.

### 3. Sales by Category

Compares sales across Technology, Furniture, and Office Supplies.

### 4. Top 10 Products by Sales

Identifies the products generating the highest sales.

### 5. Sales by Customer Segment

Shows the contribution of Consumer, Corporate, and Home Office customers.

### 6. Average Shipping Days by Ship Mode

Compares average delivery time across different shipping methods.

---

## 9. Power BI Dashboard

An interactive **E-Commerce Sales Analytics** dashboard was developed using Microsoft Power BI.

### KPI Cards

The dashboard contains four major KPIs:

| KPI | Value |
|---|---:|
| Total Sales | 2.26M |
| Total Orders | 4,922 |
| Total Customers | 793 |
| Total Products | 1,861 |

### Dashboard Visualizations

The dashboard includes:

- Sales Trend by Year
- Sales by Region
- Top 10 Products by Sales
- Sales by Category
- Sales by Customer Segment
- Average Shipping Days by Ship Mode

### Interactive Filters

The dashboard includes slicers for:

- Year
- Region
- Category
- Segment
- Ship Mode

The Power BI dashboard was developed as part of the project analysis. A screenshot of the final dashboard is included in the `visualizations` folder.

---

## 10. Key Business Insights

### Insight 1 – Regional Performance

The **West region** is the highest-performing region, generating approximately **0.71M** in sales.

The South region has the lowest sales among the four regions.

### Insight 2 – Category Performance

**Technology** is the highest-performing category with approximately **0.83M** in sales.

Furniture and Office Supplies also contribute significantly to total revenue.

### Insight 3 – Customer Segment

The **Consumer segment** contributes the largest share of sales, representing approximately **50.76%**.

Corporate contributes approximately **30.44%**, while Home Office contributes approximately **18.79%**.

### Insight 4 – Sales Growth

Sales increased significantly during the later years, with **2018 recording the highest annual sales**.

### Insight 5 – Shipping Performance

**Standard Class** has the highest average shipping duration at approximately **5 days**.

First Class and Same Day provide faster delivery options.

---

## 11. Business Recommendations

### Recommendation 1 – Strengthen Regional Strategies

The business should maintain its strong performance in the West and East regions while investigating the lower performance of the South region.

Possible strategies include:

- Region-specific marketing
- Local promotions
- Customer segmentation
- Improving product availability

### Recommendation 2 – Prioritize High-Performing Products

The company should focus on high-performing products and the Technology category through:

- Better inventory planning
- Targeted marketing
- Product promotions
- Avoiding stock shortages

### Recommendation 3 – Improve Shipping Efficiency

The business should investigate the longer delivery time associated with Standard Class shipping.

Possible improvements include:

- Better warehouse allocation
- Improved logistics planning
- Optimized delivery routes
- Inventory positioning

### Recommendation 4 – Focus on Consumer Customers

Since the Consumer segment contributes more than half of the sales, the company can introduce:

- Customer loyalty programs
- Personalized offers
- Targeted promotions
- Repeat-purchase incentives

---

## 12. Project Structure

```text
Ecommerce-Sales-Analytics/
│
├── data/
│   └── Dataset files
│
├── notebooks/
│   └── ECommerce_Analytics.ipynb
│
├── report/
│   └── ECommerce_Sales_Analytics_Report.pdf
│
├── visualizations/
│   ├── Sales Trend by Year
│   ├── Sales by Region
│   ├── Sales by Category
│   ├── Top 10 Products
│   ├── Customer Segment
│   ├── Shipping Analysis
│   └── Power BI Dashboard Screenshot
│
└── README.md
```

> **Note:** The Power BI `.pbix` file and presentation file are maintained separately and are not included in this GitHub repository.

---

## 13. Git Workflow

Git was used to maintain the project and track changes.

The basic Git workflow included:

```bash
git clone
git add
git commit
git push
git pull
```

Meaningful commits were created during the development of the project.

Example:

```bash
git add .
git commit -m "Add final project analysis and documentation"
git push origin main
```

---

## 14. Project Outcomes

The project successfully demonstrates the complete data analytics workflow.

The major outcomes include:

- Cleaned e-commerce dataset
- Exploratory Data Analysis
- Multiple business visualizations
- Interactive Power BI dashboard
- Identification of important business trends
- Data-driven recommendations
- GitHub project documentation

---

## 15. Conclusion

The E-Commerce Sales Analytics project demonstrates how raw transactional data can be transformed into meaningful business insights using data analytics and business intelligence techniques.

The analysis identified important trends in regional sales, product categories, customer segments, product performance, and shipping efficiency.

The Power BI dashboard provides an interactive way to explore these metrics and supports data-driven decision-making.

Overall, the project provided practical experience in **Python, Pandas, data visualization, Exploratory Data Analysis, Power BI, Git, GitHub, and business analytics**.

---

## 16. Repository

**GitHub Repository:**

https://github.com/anuskagupta123/Ecommerce-Sales-Analytics

---

## 17. Author

**Anuska Gupta**

B.Tech Artificial Intelligence and Data Science  
KPR Institute of Engineering and Technology
