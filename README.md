# Online-Retail-Analysis

# Online Retail Analysis Using Python

This project focuses on analyzing retail data using Python libraries such as **pandas**, **numpy**, **matplotlib**, and others. It encompasses various processes like data preprocessing, cleaning, exploratory data analysis, trend analysis, RFM analysis, and customer churn analysis, along with insightful visualizations.


## About the Project
This project involves analyzing an online retail dataset to extract insights into customer behavior, sales trends, and product performance. The analysis includes data cleaning, statistical views, and interactive visualizations to explore and understand the dataset better.


## Key Features
- Preprocessing and cleaning of retail data.
- Statistical and exploratory data analysis.
- Monthly trend analysis and product performance metrics.
- Segmentation of customers using RFM (Recency, Frequency, Monetary) Analysis.
- Customer churn analysis and distribution visualization.
- Generation of insightful visualizations like bar charts, line graphs, histogram and more.


## Technologies Used
- **Python Libraries**: pandas, numpy, matplotlib, fireducks
- **Data Handling**: openpyxl
- **IDE/Editor**: Any Python-compatible editor
- **Visualization**: matplotlib, pandas built-in graphing


## Dataset Details
- **Source**: Online retail dataset downloaded as a zip file.
- **File Format**: Excel (`online retail.xlsx`)
- **Columns**: 
  - InvoiceNo
  - StockCode
  - Description
  - Quantity
  - InvoiceDate
  - UnitPrice
  - CustomerID
  - Country


## Project Workflow
1. **Data Preprocessing**:
   - Loaded the Excel dataset using `openpyxl`.
   - Converted all columns to string format.
2. **Data Cleaning**:
   - Identified and handled missing values.
   - Created a separate table for frequent customers.
   - Joined this table with the main dataset to reduce null values.
   - Dropped `Description` column with null values.

3. **Quantile Segmentation**:
   - Segregated the dataset into four quantiles for deeper analysis.

4. **Trend Analysis**:
   - Created a `TotalPrice` column (`Quantity` × `UnitPrice`).
   - Conducted month-wise total price analysis.


## Insights & Visualizations
- **Month-wise Total Price Analysis**: 
  - Visualized using bar charts and line graphs.
- **Top 5 Countries by Total Sales**:
  - Presented as bar charts with percentage representations.
- **Product-wise Sales**:
  - Focused on `StockCode` and total price.
- **Top 5 Customers and Products**:
  - Analyzed and displayed.


## RFM Analysis and Customer Segmentation
- **RFM Analysis**:
  - Based on Recency, Frequency, and Monetary values of customer purchases.
- **Customer Segmentation**:
  - Segregated customers into segments for targeted analysis.


## Customer Churn Analysis
- **Churn Analysis**:
  - Identified customers who did not purchase for more than 90 days.
  - Visualized churn distribution graphically.


## How to Run the Project
1. Clone the repository.
2. Ensure Python and necessary libraries (pandas, numpy, matplotlib, openpyxl) are installed.
3. Place the dataset in the project directory.
4. Run the script in your preferred Python environment.
