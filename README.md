# 🧾 Supermarket Sales Dashboard

_visualizing superstore sales dataset_

---

Perfect 👍 You already have a **template** (Table of Contents + project breakdown). Since your project is on **Supermarket Sales Dashboard (Kaggle dataset)**, I’ll fill it with relevant details for you.

Here’s a ready-to-use **README.md style write-up** for your project:

---

## 📌 Table of Contents

* <a href="#overview">Overview</a>
* <a href="#business-problem">Business Problem</a>
* <a href="#dataset">Dataset</a>
* <a href="#tools--technologies">Tools & Technologies</a>
* <a href="#project-structure">Project Structure</a>
* <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
* <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
* <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
* <a href="#dashboard">Dashboard</a>
* <a href="#how-to-run-this-project">How to Run This Project</a>
* <a href="#final-recommendations">Final Recommendations</a>
* <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes supermarket sales data to uncover customer behavior, sales patterns, and branch performance. The goal is to build a **Power BI dashboard** that provides actionable insights into product line performance, customer segments, and revenue trends.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Retail businesses must monitor sales performance and customer preferences to stay competitive. This project aims to:

* Identify the **most profitable product lines**
* Compare **branch and city-wise performance**
* Analyze **customer type and payment method trends**
* Track **sales growth over time**
* Highlight **top customers contributing to revenue**

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

* **Source:** Kaggle – *Supermarket Sales Dataset*
* **Attributes:**Row ID, Order ID,order Date, Ship Date,	Ship Mode,	Customer ID,	Customer Name,	Segment	Country,	City,	State,	Postal Code,	Region,	Product ID	Category, Sub-Category,	Product Name,	Sales
* **Size:** \~9,8000 customer sales

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

* **Power BI** (Interactive Dashboard, DAX Measures)
* **Excel / Power Query** (Data Cleaning & Preprocessing)
* **GitHub** (Version control & documentation)

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
supermarket-sales-dashboard/
│
├── README.md
├── .gitignore
├── data/                       # Kaggle dataset
│   └── supermarket_sales.csv
│
├── dashboard/                  # Power BI dashboard file
│   └── supermarket_sales_dashboard.pbix
│
├── images/                     # Screenshots for documentation
│   └── dashboard.png
```

---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

* Checked and corrected data types (Date, Time, Categorical fields)
* Created new calculated columns:

  * **Total Sales** = (Sale price) 
  * **Month / Day / Hour** extracted for time-based analysis
* Handled missing or duplicate values
* Standardized categorical values (e.g., gender, payment method)

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **which is highest selling product ?**
   → **printer is highest selling product.**

2. **Which city has highest sales?**
   → **New York has highest sales.**

3. **which category contribute more revenue ?**
   → **technology category contribute more .**

4. **Who are the top customers by sales?**
   → **Top 5 customers contribute significantly higher than average.**

5. **When are sales the highest?**
   → **2018 year was highest sales.**

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

* KPI Cards: **Total Sales, Average Sales, Total customer**
* Bar/Column Charts: **sales by sub category, Sum of Sales by City**
* Donut Chart: **sum sales by sub category**
* Line Chart: **sales by yearly and quartely**
* Table: **Top 5 Customers by Sales, segment sales**

![Supermarket Sales Dashboard]img <img width="1324" height="741" alt="Screenshot 2025-09-24 214216" src="https://github.com/user-attachments/assets/8ab6baa4-a801-4466-9a2d-9b352afb3368" />



---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Download dataset from [Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales).
2. [Download Dashboard File](https://github.com/yourusername/supermarket-sales-dashboard/blob/main/dashboard/supermarket_sales_dashboard.pbix)
3. Refresh the data source (link to ).

---

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

* **Expand Technology line** due to high demand
* **Promote low-performing categories** like Art and fastener
* **Encourage Cities programs** (members spend more)
* **Boost Home Office partnerships** to increase Sales

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Tarun Burla**
Data Analyst | Business Intelligence Enthusiast
📧 Email: *\[tarunburla1234@gmail.com]*
🔗 [LinkedIn](https://www.linkedin.com/)
🔗 [Portfolio](https://github.com/)

---


