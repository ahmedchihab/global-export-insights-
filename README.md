
# **Global Export Insights Dashboard (Power BI)**

## **Description**

This project provides a comprehensive analysis of **global exports** using raw Excel data. The data was cleaned and transformed with **Power Query** and then visualized in **Power BI** to highlight trends, key metrics, and top exporters.

To ensure **accurate insights**, statistical methods were applied to detect and **exclude outliers** (abnormal values) that could skew results. The outcome is an **interactive and reliable dashboard** designed for decision-making and trend monitoring.

---

## **Objectives**

* Clean and structure export data from multiple Excel files.
* **Apply statistical techniques (IQR) to detect and exclude outliers**.
* Handle null values and prepare high-quality datasets for analysis.
* Create **DAX measures** for key KPIs, such as:

  * Total export value
  * Number of exporters
  * Average unit price
  * Share of the **Top 5 exporters**
* Build **interactive dashboards** featuring:

  * Global export map
  * Time-series trends
  * Country/category comparisons

---

## **Features**

* **Multi-file import** directly from a folder (dynamic refresh).
* **Data cleaning and transformation** with Power Query.
* **Outlier detection** using IQR to maintain unbiased KPIs.
* **Advanced DAX calculations** for export metrics.
* **Interactive dashboards** with slicers and filters:

  * Top exporters visualization
  * Global map by export value
  * Unit price trend chart

---

## **Statistical Method Used**

Outliers were detected using the **Interquartile Range (IQR)** method:

1. Calculate **Q1 (25th percentile)** and **Q3 (75th percentile)**.
2. Compute the **IQR = Q3 – Q1**.
3. Exclude any data points outside **Q1 – 1.5×IQR** or **Q3 + 1.5×IQR**.

This ensures extreme values do not distort averages and comparisons.

---

## **Tools Used**

* **Excel** (Power Query for cleaning and transformation)
* **Power BI Desktop** (data modeling, DAX, and visualization)
* **Basic Statistics** (IQR for outlier detection)

---

## **How to Use**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/global-export-insights.git
   ```

2. Open the `.pbix` file in **Power BI Desktop**.

3. Update the data source path if needed (folder containing Excel files).

4. Refresh the data to load the latest information.

5. Explore the interactive dashboard (filters, slicers, charts).

---

## **Project Status**

* [x] Imported and cleaned raw Excel files
* [x] Applied outlier detection (IQR method)
* [x] Created main DAX measures for KPIs
* [x] Built Power BI visualizations (maps, charts)
* [ ] Add real-time data updates (future improvement)
* [ ] Detailed documentation of DAX formulas and data model

---

## **Preview**



---<img width="769" height="441" alt="image" src="https://github.com/user-attachments/assets/80832d98-7e3f-458e-a679-cd9f21a33e8a" />


## **Author**

Ahmed Chihab – Finance Student passionate about Data Analysis
[LinkedIn](#) | [GitHub](#)

---

Excel Files (.xlsx) Folder
          │
          ▼
Power Query (Excel)
- Import multiple files
- Clean data (handle nulls, duplicates)
- Detect & remove outliers (IQR method)
          │
          ▼
Power BI Desktop
- Import cleaned data
- Data modeling & relationships
- Create DAX measures (KPIs)
          │
          ▼
Interactive Dashboard
- Global export map
- Export trends charts
- Top exporters & country comparisons
- Dynamic filters and slicers

