# Excel-Sales-Dataset-Project
# Retail Sales Data Analysis Project (Excel & Spreadsheet Skills Showcase)

## Project Overview

This repository features a comprehensive data analysis project utilizing a retail sales transactional dataset. The project serves as a showcase of essential spreadsheet software skills (e.g., Microsoft Excel or Google Sheets), focusing on data aggregation, analysis, interactive reporting, and professional formatting.

The core objective is to derive actionable business intelligence from the raw transaction data, focusing on sales performance trends, product category success, and customer demographics (`Gender`, `Generation`).

## Data Source

The analysis is built upon several CSV files derived from a master retail sales workbook. The main file providing the detailed transaction lines is **`retail_sales_dataset_Master - Savitha H Kikkeri.xlsx - retail_sales_dataset.csv`**.

| File Name | Content Description | Key Fields Used in Analysis |
| :--- | :--- | :--- |
| `retail_sales_dataset.csv` | **Main Transactional Data.** | `Total Sales`, `Date`, `Product Category`, `Gender`, `Generation`, `Price per Unit` |
| `Transactions.csv` | Supplementary log, useful for data linking exercises. | `Transaction ID`, `Total Sales` |
| `Sheet1.csv` & `Sheet2.csv` | Pre-aggregated summaries showing sales proportions. | `Sum of Total Sales`, `Generation` (Adult, Senior, Young Adult) |

## Excel Skills Demonstrated

The project highlights the following key spreadsheet competencies:

### 1. Core Functions and Conditional Logic

* **Totals & Means:** Applied `SUM`, `AVERAGE`, `MAX`, and `MIN` to establish overall performance benchmarks (e.g., total revenue, highest single sale amount).
 <img width="361" height="176" alt="image" src="https://github.com/user-attachments/assets/c1a7dd67-1d7a-4ffc-8944-d0ce7ffbb66e" />
 <img width="380" height="100" alt="image" src="https://github.com/user-attachments/assets/8ec556ea-e563-40a7-83bd-45adc2b4d78d" />

  

* **Conditional Aggregation:** Used **`SUMIF`** and **`AVERAGEIF`** to calculate metrics based on specific criteria (e.g., average sales for 'Female' customers, or total sales for 'Beauty' products).
   <img width="275" height="82" alt="image" src="https://github.com/user-attachments/assets/511b8347-abb1-40e2-b7e1-7cafc87dc9af" />
* **Data Integration:** Employed **`VLOOKUP`** to integrate or retrieve information across different sheets using a common identifier like the `Transaction ID`.
<img width="155" height="153" alt="image" src="https://github.com/user-attachments/assets/8a093d21-1562-4081-bc6f-6f47a9e55eee" />



### 2. Interactive Reporting (Pivot Tools)

* **Pivot Table:** Created multi-dimensional summaries (e.g., showing the sum of `Total Sales` broken down by `Product Category` and `Gender`).
  <img width="392" height="168" alt="image" src="https://github.com/user-attachments/assets/6e9f4ed5-e2ae-4110-b5f3-31914e348a9a" />

* **Pivot Chart:** Generated a dynamic visual (e.g., Clustered Column Chart) directly linked to the Pivot Table for quick insight into comparative sales performance.
  <img width="435" height="211" alt="image" src="https://github.com/user-attachments/assets/7c4e6b89-d1df-4ec0-b344-cb8362a5e59a" />

* **Slicers:** Implemented interactive Slicers linked to the Pivot Table/Chart, enabling one-click filtering by dimensions like **`Generation`** or **`Month Name`**.
<img width="424" height="172" alt="image" src="https://github.com/user-attachments/assets/877088e6-3501-457a-be30-4840915baecc" />

### 3. Data Presentation and Quality Control

* **Formatting:** Applied appropriate **Currency Formatting** (`$`) and **Date Formatting** (`DD-MMM-YYYY`) to ensure clarity and consistency.
  <img width="428" height="191" alt="image" src="https://github.com/user-attachments/assets/32496596-62b9-4d79-b70a-99a5169bdf7c" />

* **Conditional Formatting:** Used rules (e.g., **Data Bars** or **Color Scales**) on the `Total Sales` column to visually emphasize high-value transactions and quickly identify data trends.
  <img width="601" height="193" alt="image" src="https://github.com/user-attachments/assets/4df57f48-07a0-4102-a286-b714115ced61" />

* **Filtering & Sorting:** Utilized standard table tools to focus analysis, such as sorting the entire dataset by `Total Sales` from largest to smallest.
  <img width="430" height="14" alt="image" src="https://github.com/user-attachments/assets/560cfbe7-1ee8-4e19-bc11-ebe19496eb16" />



## Project Setup and Usage

To interact with the analysis and explore the formulas used:

1.  **Download the Files:** Clone this repository or download the attached CSV files locally.
2.  **Import to Spreadsheet:** Open the `retail_sales_dataset.csv` file in your preferred spreadsheet application (Excel, Sheets).
3.  **Explore Analysis:** Examine the formulas in the main data sheet and navigate to the dedicated Pivot Table/Chart sheets to interact with the Slicers and dynamic reports.

## License

This project is open-source and available under the MIT License.

***

**Author:** Savitha Kikkeri

**Date:** 07/10/2025
