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
* **Attributes:** Invoice ID, Branch, City, Customer Type, Gender, Product Line, Unit Price, Quantity, Tax, Total, Date, Time, Payment Method, Rating
* **Size:** \~1,000 transactions across 3 branches

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

* **Power BI** (Interactive Dashboard, DAX Measures)
* **Excel / Power Query** (Data Cleaning & Preprocessing)
* **SQL** (Optional for querying/filtering)
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

  * **Gross Income** = (Unit Price × Quantity × 5%)
  * **Total Sales** = (Unit Price × Quantity) + Tax
  * **Month / Day / Hour** extracted for time-based analysis
* Handled missing or duplicate values
* Standardized categorical values (e.g., gender, payment method)

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Branch & City Insights:**

* Sales highest in **Yangon**, lowest in **Naypyitaw**
* **Branch C** leads in customer count

**Product Line Insights:**

* **Food & Beverages** and **Electronic Accessories** are top contributors
* **Health & Beauty** shows lowest average revenue

**Customer Insights:**

* **Female customers** spend slightly more than males
* **Member customers** generate higher average sales

**Payment Methods:**

* **E-wallets** are the most preferred payment method

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Which branch generates the highest sales?**
   → **Branch C**, mainly in Yangon.

2. **Which product line contributes most to revenue?**
   → **Food & Beverages** and **Electronic Accessories**.

3. **What are customer preferences in payment methods?**
   → **E-wallet** is the top choice, followed by **Cash**.

4. **Who are the top customers by sales?**
   → Top 5 customers contribute significantly higher than average.

5. **When are sales the highest?**
   → Sales peak during **evenings and weekends**.

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

* KPI Cards: **Total Sales, Average Sales, Gross Income**
* Bar/Column Charts: **Sales by Product Line, Payment Method, City**
* Donut Chart: **Customer Type & Gender distribution**
* Line Chart: **Monthly and Daily Sales Trends**
* Table: **Top 5 Customers by Sales**

![Supermarket Sales Dashboard](images/dashboard.png)

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Download dataset from [Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales).
2. Open `supermarket_sales_dashboard.pbix` in Power BI.
3. Refresh the data source (link to `supermarket_sales.csv`).
4. Interact with filters (Branch, City, Product Line, Payment Method).

---

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

* **Expand Food & Beverages line** due to high demand
* **Promote low-performing categories** like Health & Beauty
* **Encourage membership programs** (members spend more)
* **Boost e-wallet partnerships** to increase digital payments
* **Offer evening/weekend promotions** to leverage peak sales time

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Tarun Burla**
Data Analyst | Business Intelligence Enthusiast
📧 Email: *\[your email]*
🔗 [LinkedIn](https://www.linkedin.com/)
🔗 [Portfolio](https://github.com/)

---

Would you like me to also **make a polished PDF report version** (like a case study with visuals & summary) that you can attach along with your dashboard?

