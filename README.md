# 📊 Atliq Hardware Analytics Project

🎯 **Project Summary**

This analytics project explores Atliq Hardware's performance across finance, sales, marketing, and supply chain using SQL, Power BI, and Excel. It aims to uncover key business trends and guide data-driven decision-making through interactive dashboards and visual storytelling.

## 📁 Overview

**Atliq Hardware** is one of the fastest-growing companies in the global electronics market. It sells computer hardware products such as PCs, printers, and accessories through various channels—including **Retailers**, **Distributors**, and **Direct Sales**. These products reach end-consumers via both **E-Commerce platforms** and **Brick & Mortar stores**.

As Atliq’s operations have expanded globally, the complexity of their business has increased significantly. To stay competitive and agile in this dynamic market, they need to transition from traditional decision-making approaches to data-driven strategies.

---

## ❗ Problem Statement

Despite impressive growth, Atliq faced a major setback during their expansion into the **Latin American** market. After opening a company-owned retail store, they suffered substantial losses—primarily because decisions were based on intuition and limited survey data.

Traditionally, Atliq relied heavily on Excel for storing and analyzing data. However, as the business grew, Excel became inefficient and unsuitable for handling the volume and complexity of their operations.

Meanwhile, their key competitor, **Dell**, has invested heavily in data analytics—conducting detailed analyses on customer demographics, income levels, and purchasing behavior. To remain competitive, Atliq must do the same by embedding analytics at the core of its strategic decision-making.

As a result, the company decided to establish a **Data Analytics Team** with a clear mandate:
- Transition from spreadsheet-based analysis to a modern, scalable analytics ecosystem.
- Improve data visibility and transparency across the organization.
- Enable data-informed decisions at all levels of the business.

---

## 🎯 Project Objectives

- ✅ Identify and clean business-critical data from various sources.
- ✅ Build a centralized database system to ensure data integrity and accessibility.
- ✅ Perform exploratory data analysis to uncover patterns and trends.
- ✅ Develop visual dashboards for real-time business insights.
- ✅ Generate actionable recommendations to support strategic decisions.
- ✅ Benchmark Atliq’s performance against key competitors using analytics.

---

## 🛠️ Tools & Technologies Used

| Category             | Tools & Platforms                         |
|----------------------|--------------------------------------------|
| Query Language       | SQL                                        |
| Data Storage         | MySQL                                      |
| Data Visualization   | Power BI Desktop                           |
| Data Preparation     | Excel                                      |
| Reporting Language   | DAX Language                               |
| Performance Tuning   | DAX Studio                                 |
| Documentation        | Project Charter File                       |

---

## 🏗️ Project Architecture

This section outlines the end-to-end workflow used in the Atliq Hardware Analytics project:

1. **Data Collection**
   - Raw sales and operational data were collected from multiple sources such as Excel files and internal databases.
   - Historical performance data and external market data were gathered to support benchmarking.

2. **Data Storage**
   - All cleaned and structured data were stored in a centralized **MySQL** database for easy querying and scalability.

3. **Data Preparation**
   - Initial data exploration and validation were done using **Excel**.
   - Complex transformations and aggregations were performed using **SQL** queries.

4. **Data Modeling & Reporting**
   - Data was imported into **Power BI Desktop** to build a robust data model using **DAX language**.
   - Relationships, measures, and calculated columns were defined to support dynamic reporting.
     
![Data Modelling](https://github.com/user-attachments/assets/8a0124a4-c7de-4d3f-b31a-1d4c45a2b01a)

5. **Dashboard Development** 
   - Reports were optimized using **DAX Studio** to enhance query performance.
   - Interactive dashboards were created in Power BI to provide insights into key metrics such as Finance, Sales, Marketing, Supply Chain, and Executive, each offering insights tailored to different teams.

![Business_Insights_360_Dashboard-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/ed43abec-9ba9-4add-a6a6-796bddc438f8)

   - On the Home Page, users can easily navigate to the relevant view.
   - The Finance View shows trends in revenue and profit over time.
   - The Sales View breaks down performance by product and region, while the Marketing View helps track the impact of campaigns and customer behavior.
   - The Supply Chain View provides insights into inventory and supplier data, and the Executive View brings all the key metrics together for high-level decision-making.


5. **Documentation**
   - A **Project Charter File** was created to define the project scope, objectives, stakeholders, deliverables, and timelines.

---

## 📈 Key Insights & Recommendations (Optional)

## 📈 Key Insights & Recommendations

- 🔻 **Latin America Underperformance:** Sales in the newly opened Latin American retail store were 27% lower than forecasted, indicating poor market-fit analysis. It’s recommended to conduct thorough market research before future expansions.

- 💡 **E-Commerce Outperforms Physical Stores:** Across most product lines, online sales consistently outpaced those from brick-and-mortar stores—suggesting a strategic focus on strengthening digital channels.

- 🛒 **Printer Accessories Overstocked:** Inventory turnover rate for printer accessories is 30% below average. Realigning procurement based on demand forecasting will reduce excess holding costs.

- 📢 **Marketing Spend Mismatch:** Regions with high campaign spending didn’t always show a corresponding rise in sales. Reallocate budgets based on performance analytics to maximize ROI.

- 📊 **Executive View Streamlining:** Key performance indicators (KPIs) for revenue, gross margin, and net profit are now unified in one dashboard—improving visibility for leadership and enabling faster decisions.

---

## 📂 Folder Structure (Optional)

Atliq-Hardware-Analytics/
│
├── data/                     # Raw and cleaned datasets (CSV, Excel files)
│   ├── raw/                  # Original unprocessed data files
│   └── cleaned/              # Preprocessed, ready-for-use data
│
├── sql-scripts/             # SQL queries for data extraction, transformation, and loading (ETL)
│   ├── create_tables.sql
│   └── data_cleaning.sql
│
├── powerbi/                 # Power BI dashboard files (.pbix)
│   └── Atliq_Analytics_Dashboard.pbix
│
├── documentation/           # Project Charter, README, business notes
│   ├── Project_Charter.pdf
│   └── README.md
│
├── assets/                  # Images, GIFs, and visual aids used in documentation
│   ├── Data_Modelling.png
│   └── Dashboard_Demo.gif
│
└── requirements.txt         # (Optional) Environment setup instructions or dependencies
