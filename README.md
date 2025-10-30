# 🚀 Comprehensive Sales Performance Analytics (SQL & Power Pivot Data Model)

## ✨ Project Overview

This repository showcases a complete data analysis lifecycle project, starting from raw data processing using **SQL** to building an advanced **Data Model** within **Microsoft Excel** (leveraging Power Query and Power Pivot), and concluding with the creation of an interactive **Dashboard** for actionable business insights.

The project utilizes seven linked tables to conduct a deep dive into sales performance across multiple dimensions: Product, Customer, Geography, and Time.

---

## 📂 Data Model Schema: The Star Schema

The analysis is based on a robust Star Schema design, centralizing all quantitative metrics in the `Sales` Fact Table and linking them to dedicated Dimension Tables.

| File Name | Schema Type | Key Columns | Description |
| :--- | :--- | :--- | :--- |
| `Sales.csv` | **Fact Table** | `CustomerKey`, `ProductKey`, `OrderDate` | Details of each transaction (Sales Amount, Cost, Profit). |
| `CustomerInfo.csv` | Dimension | `CustomerKey`, `GeographyKey` | Customer demographics (Occupation, Income, Marital Status). |
| `DimProduct.csv` | Dimension | `ProductKey`, `ProductSubcategoryKey` | Product details (Color, Size, Cost, Price). |
| `Geography.csv` | Dimension | `GeographyKey` | Geographical location (City, State, Country). |
| `Date.csv` | Dimension | `Date` | Time attributes (Year, Month, Quarter). |
| `ProductSubCategories.csv` | Dimension | `ProductSubcategoryKey` | Names of product subcategories. |
| `ProductCategories.csv` | Dimension | `ProductCategoryKey` | Names of product main categories (e.g., Bikes, Clothing). |

---

## 🛠️ Tools and Technologies

| Tool | Primary Purpose |
| :--- | :--- |
| **SQL** | Initial data cleaning, aggregation, pre-processing, and generating analytical queries. |
| **Power Query (Excel)** | Extract, Transform, Load (ETL) process, data type conversion, and handling initial data cleansing. |
| **Power Pivot (Excel)** | Building the Star Schema Data Model, managing **One-to-Many relationships**, and creating powerful calculated measures (DAX). |
| **Excel (Pivot Tables & Charts)** | Designing dynamic visualizations and the interactive dashboard. |

---

## ⚙️ Methodology

### 1. Data Processing and Cleaning (SQL & Power Query)

* **SQL Queries:** Executed **7 unique SQL queries** to validate data quality, check for data consistency, and calculate derived metrics like `Profit`.
* **Data Loading:** Utilized Power Query to efficiently load the large CSV files and enforce correct data types.

### 2. Data Modeling (Power Pivot)

* The data was loaded into the Excel Data Model.
* **Relationships:** Established robust **One-to-Many** relationships to seamlessly connect the `Sales` Fact Table with all relevant Dimension Tables.

### 3. Analysis and Visualization

* **Pivot Tables:** Created tables to analyze key metrics by Customer, Product, and Date.
* **Dashboard:** Designed an interactive dashboard using **Pivot Charts** and linked **Slicers** for dynamic filtering.

---

## 📊 Dashboard Snapshot and Key Findings

The final dashboard provides critical insights for strategic decision-making:

### Key Metrics Tracked:

* **Total Revenue**
* **Total Profit**
* **Gross Margin % (GM%)**
* **Average Order Value (AOV)**

### Dashboard Screenshot:

A high-resolution image showcasing the final interactive dashboard.



***

### Key Business Insights:

* **[Insight 1 related to Product Performance]**: *(Example: Bikes dominate revenue, but Accessories have the highest Gross Margin %)*.
* **[Insight 2 related to Geography]**: *(Example: Sales are highest in the US, but Australia shows the fastest YoY growth)*.
* **[Insight 3 related to Customers]**: *(Example: Professional and High-Income customers drive the highest Average Order Value)*.

---

## 📁 Repository Contents

| Path | Description |
| :--- | :--- |
| `Data` | Contains all **7 original CSV & SQL Queries File &Excel File** datasets. |
| `Visualizations/Dashboard_Snapshot.png` | A high-quality image of the final dashboard. |

---

## 🤝 Contributors and Contact

### 🧑‍💻 Project Collaborators

This project was developed in collaboration with the following colleagues:

<table style="width:100%; border:none;">
  <tr>
    <td style="text-align:center; padding:10px; border:none;">
      <a href="https://github.com/HassanZoghly">
        <img src="https://avatars.githubusercontent.com/u/114166268?v=4?s=100&v=4" alt="Colleague 1 GitHub Avatar" width="80" style="border-radius: 50%; border: 3px solid #0077b5;">
        <br>
        <strong>Hassan Hamid</strong>
      </a>
    </td>
    <td style="text-align:center; padding:10px; border:none;">
      <a href="https://github.com/AsemFared435/">
        <img src="https://avatars.githubusercontent.com/u/200077218?v=4?s=100&v=4" alt="Colleague 2 GitHub Avatar" width="80" style="border-radius: 50%; border: 3px solid #0077b5;">
        <br>
        <strong>Asem Farid</strong>
      </a>
    </td>
  </tr>
</table>

<br>
📞 Contact the Developer

Feel free to connect or reach out regarding this project:

| Platform | Link |
| :--- | :--- |
| **GitHub** | [Mostafa Nasser On GitHub](https://github.com/moustafa-nasser) |
| **LinkedIn** | [Mostafa Nasser On LinkedIn](https://www.linkedin.com/in/mostafa-nasser-876442322/) |
| **Email** | [Gmail](mailto:mostafa4businesses@gmail.com) |
