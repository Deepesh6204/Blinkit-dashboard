# Blinkit Sales Analysis Dashboard | Power BI

![Blinkit Power BI Dashboard](dashboard.png)

## 📊 Project Overview

This project is an interactive **Blinkit Sales Analysis Dashboard** built using **Microsoft Power BI**. The dashboard provides a clear view of sales performance, item distribution, outlet characteristics, customer ratings, and outlet-level metrics.

The goal of this project is to transform raw retail sales data into an interactive business dashboard that can help analyze **sales trends, product performance, outlet performance, and key KPIs**.

---

## 🎯 Project Objectives

- Analyze overall sales performance.
- Understand sales distribution across different outlet types and sizes.
- Identify high-performing item categories.
- Analyze the relationship between fat content and sales/items.
- Compare outlet tiers and outlet location characteristics.
- Monitor important KPIs such as sales, item count, average sales, and ratings.
- Provide interactive filtering for deeper analysis.

---

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| **Total Sales** | **$1.2M** |
| **Average Sales** | **141.0** |
| **Number of Items** | **8,523** |
| **Average Rating** | **3.92** |

> KPI values shown above are based on the dashboard view included in this project and may change when filters are applied.

---

## 🔎 Dashboard Features

### 1. Interactive Filters

The dashboard includes filters for:

- **Outlet Location Type**
- **Outlet Size**
- **Item Type**

These filters allow users to analyze the dashboard dynamically.

### 2. Sales Trend Analysis

The **Outlet Establishment** chart shows sales performance across outlet establishment years and helps identify changes in sales over time.

### 3. Fat Content Analysis

The dashboard compares items based on:

- **Low Fat**
- **Regular**

This analysis is presented through a donut chart and outlet-level comparison.

### 4. Item Type Analysis

The item type visual compares the number of items across categories such as:

- Fruits and Vegetables
- Snack Foods
- Household
- Frozen Foods
- Dairy
- Canned
- Baking Goods
- Health and Hygiene
- Soft Drinks
- Meat
- Breads
- Hard Drinks
- Others
- Starchy Foods
- Breakfast
- Seafood

### 5. Outlet Size Analysis

The dashboard compares sales across different outlet sizes:

- Small
- Medium
- High

### 6. Outlet Location Analysis

Outlet performance is analyzed across different location tiers:

- Tier 1
- Tier 2
- Tier 3

### 7. Outlet Type Performance

A detailed table compares outlet types using:

- Total Sales
- Number of Items
- Average Sales
- Average Rating
- Item Visibility

---

## 📈 Dashboard Insights

From the displayed dashboard:

- Total sales are approximately **$1.2M**.
- The dataset contains **8,523 items**.
- Average sales are approximately **141**.
- The overall average rating is approximately **3.92**.
- **Supermarket Type1** contributes the largest sales amount among the displayed outlet types.
- **Tier 3** outlets show the highest sales among the displayed outlet location tiers.
- The dashboard provides a comparison between **Low Fat** and **Regular** products.
- **Fruits and Vegetables** and **Snack Foods** are among the highest-volume item categories in the displayed view.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and KPI calculations
- **Data Modeling**
- **Interactive Visualizations**
- **Excel / CSV** – Source data format

---

## 📂 Dashboard Components

The dashboard contains:

- KPI Cards
- Slicers
- Donut Chart
- Bar Charts
- Area/Line Chart
- Detailed Matrix/Table
- Conditional formatting
- Interactive report navigation/filtering

---

## 🧮 Example Measures

Some of the key calculations used in the dashboard can be represented as:

```DAX
Total Sales = SUM(Sales[Sales])
```

```DAX
Average Sales = AVERAGE(Sales[Sales])
```

```DAX
Number of Items = COUNTROWS(Sales)
```

```DAX
Average Rating = AVERAGE(Sales[Rating])
```

> The exact DAX expressions may differ depending on the final Power BI data model and column names.

---



## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Refresh the data if the source dataset is available.
4. Use the slicers to filter the dashboard.
5. Explore sales, item, outlet, and rating metrics.

---

## 💡 Business Questions Answered

This dashboard can help answer questions such as:

- What are the total sales?
- Which outlet type generates the highest sales?
- Which outlet location tier performs better in terms of sales?
- Which item categories have the highest number of items?
- How do Low Fat and Regular products compare?
- How does outlet size affect sales?
- What is the average rating?
- How does item visibility vary across outlet types?

---

## 👨‍💻 Author

**Deepesh Kumar**

MCA Graduate | Data Analytics Enthusiast

**Skills:**  
SQL • Excel • Power BI • Python • Tableau • Data Analysis

---

## ⭐ Project Purpose

This project was created as a **Data Analytics / Power BI portfolio project** to demonstrate skills in data cleaning, data modeling, DAX, KPI creation, interactive dashboard design, and business-oriented data visualization.

If you find this project useful, consider giving the repository a ⭐ on GitHub.
