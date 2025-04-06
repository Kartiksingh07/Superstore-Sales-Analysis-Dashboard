# Superstore-Sales-Analysis-Dashboard

📌 Overview
This project analyzes sales data from a Superstore using SQL for data cleaning and transformation, and Power BI for creating interactive visual dashboards.

The goal is to uncover business insights like:

Top-performing regions

Sales vs Profit trends

Category-wise analysis

Shipping performance

Key KPIs & performance metrics

🧰 Tools & Technologies
🛢️ SQL (MySQL Server): For querying and preparing the dataset

📊 Power BI: For building the dashboard and visuals

🗃️ Superstore Dataset: Standard retail sales data

📈 Key Features
Cleaned and transformed raw data using SQL

Created KPIs like Total Sales, Total Profit, Avg Discount, Profit Ratio

Filtered insights using:

Region

Segment

Category

Order Date (Time series)

Identified loss-making segments and profitable regions

Custom slicers and visual filters added for interactivity

🧪 Sample SQL Query Used
sql
Copy
Edit
SELECT 
    Region, 
    Category, 
    SUM(Sales) AS Total_Sales, 
    SUM(Profit) AS Total_Profit 
FROM Superstore
GROUP BY Region, Category
ORDER BY Total_Profit DESC;

📊 Dashboard Preview

![image](https://github.com/user-attachments/assets/7ac0d260-67ee-490a-ae57-e323bb94e6ab)

![image](https://github.com/user-attachments/assets/1aa9c6c6-51b9-4974-bab0-071add9b72b1)

📁 Folder Structure
plaintext
Copy
Edit
Superstore-Analysis/
│
├── SQL/                       # All SQL queries used
│   └── superstore_queries.sql
│
├── Dashboard/                 # Power BI (.pbix) file
│   └── Superstore_Analysis.pbix
│
├── README.md
└── Data/
    └── Superstore_Raw.csv
👨‍💻 Author
Kartik Dhatwalia

🎓 B.Tech CSE, Chandigarh University

📫 kartikdhatwaliaaz@gmail.com
