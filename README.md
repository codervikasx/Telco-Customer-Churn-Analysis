
# **📊 Telco Customer Churn Analysis**

## **📌 Project Overview**

The goal of this project was to analyze customer demographics, services, and tenure data to understand **why customers are leaving (churning)** the telecommunications company.

Using **Power BI**, I built an interactive dashboard to visualize key churn drivers and provide actionable insights for the retention team.

## **📂 Data Source**

* **Dataset:** Telco Customer Churn (Kaggle)  
* **Rows:** 7,043 customer records  
* **Fields:** 21 columns including Tenure, Contract Type, Payment Method, and Churn Status.

## **🛠️ Tools & Technologies**

* **Power BI Desktop:** Dashboard design and visualization.  
* **Power Query:** Data cleaning (Handling missing values in TotalCharges, changing data types).  
* **DAX (Data Analysis Expressions):** Calculated specific measures for accuracy.  
  * Churn Rate %  
  * Total Customers  
  * Churn Count  
  * Custom conditional columns for demographics.

## **🔍 Key Insights Discovered**

1. **Contract Risk:** Customers on **Month-to-Month contracts** have the highest churn rate (approx 40%+), whereas 2-year contract holders rarely leave.  
2. **Service Issues:** Customers with **Fiber Optic** internet are churning at a significantly higher rate than DSL users, suggesting potential dissatisfaction with price or service quality.  
3. **Demographic Hotspot:** A heat-map analysis revealed that **Senior Citizens** who are **New Customers (0-12 months tenure)** are the highest-risk group.

## **📊 Dashboard Features**

The report includes:

* **Executive Scorecard:** High-level KPIs (Churn Rate, Total Lost).  
* **Interactive Filtering:** Slicers to view data by Payment Method or Contract.  
* **Demographic Heatmap:** A matrix visual using conditional formatting to highlight risk zones.  
* **Contract Analysis:** Stacked bar charts comparing contract types.

## **🚀 How to View**

Since GitHub does not render .pbix files directly:

1. Download the **Telco\_Churn\_Analysis.pbix** file from this repository.  
2. Open it in **Power BI Desktop** (Free Download).  
3. Interact with the slicers and graphs to explore the data.

*Created by \[Vikas Chouhan\]*
