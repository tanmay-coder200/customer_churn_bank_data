# Customer Churn Analysis Dashboard

An end-to-end Data Analytics project focused on analyzing customer retention and identifying key drivers behind customer churn. This project emphasizes the importance of data cleaning, modeling, and business logic implementation before visualizing insights in Power BI.

## 📊 Project Overview
Customer churn is a critical metric for any business. This project transforms raw customer data into actionable insights, helping stakeholders understand *who* is leaving and *why*, so they can implement targeted retention strategies.

### Key Metrics Tracked:
* **Total Customers:** 10,000
* **Total Customers Lost:** 2,000
* **Overall Churn Rate:** 20%

---

## 🛠️ Data Process & Workflow

1.  **Data Transformation (ETL):** Cleaned raw datasets and converted binary/numerical values into meaningful business categories (e.g., transforming `Churn Status` from `0/1` to `Churned/Not Churned`).
2.  **Data Modeling:** Established and managed star-schema relationships between multiple tables (e.g., Customer Data, Age Groups, Credit Score Groups, and Account Balances).
3.  **Feature Engineering:** Grouped continuous data (like Age, Credit Scores, and Balances) into categorical bins to discover deeper demographic patterns.
4.  **Data Visualization:** Designed an interactive Power BI dashboard focusing on user-friendly layout and actionable KPIs.

---

## 📈 Dashboard Features & Visuals

* **Executive KPIs:** High-level cards showcasing Total Customers, Lost Customers, and Churn Rate.
* **Demographic Breakdown:** Interactive doughnut charts analyzing customer distribution by **Gender**, **Activity Status**, **Credit Card Ownership**, and **Geography**.
* **Behavioral Trends:** Combination charts displaying the relationship between total customers and churn rates across different **Age Groups**, **Account Balances**, and **Credit Score Groups**.
* **Dynamic Filtering:** Slicers allowing users to instantly filter the entire report by Churn Status.

---

## 🚀 Tech Stack Used
* **SQL:** For initial data extraction and exploration.
* **Power Query:** For data cleaning, type casting, and conditional column creation.
* **Power BI:** For data modeling (relationships), DAX measures, and dashboard visualization.

---

## 💡 Key Takeaways
"Good analysis always comes before good visuals." This project reinforced the importance of robust data preparation—understanding the dataset's business context and structuring relationships correctly is what ultimately drives accurate and impactful visualizations.
