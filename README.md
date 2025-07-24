# Tech Company Fundings Dashboard

---

## 🔗 Access the Dashboard

* 📊 **Interactive Tableau Dashboard:**
  👉 [Click here to view the live dashboard on Tableau Public](https://public.tableau.com/views/techcompanyfunding/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
 
* 📄 **Dashboard Report:**
  👉 [Click here to view the dashboard](./Dashboard/)

---


## 1. Background and Overview

This personal project was built using **Power BI & Tableau** to present a comprehensive analysis of **tech company funding data**, focusing on global investment patterns, top-funded companies, industry categories, and regional dynamics.

The purpose of this project is to:

* Identify which companies and sectors attract the most investment
* Observe monthly funding trends
* Understand funding behavior across different regions and stages

---

## 2. Data Structure Overview

The dataset is structured in a single fact table with the following fields:

| Column Name            | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| `Company`              | Name of the tech company receiving funding                         |
| `Funding Amount (USD)` | Amount of funding received in US dollars                           |
| `Funding Date`         | Date when the funding event occurred                               |
| `Funding Stage`        | Investment stage (e.g., Seed, Series A, Series B, Private Equity)  |
| `Region`               | Country or geographic region of the company                        |
| `Vertical`             | Industry category or focus of the company (e.g., AI, B2B Software) |

---

## 3. Executive Summary

**Overall Statistics:**

* **Total Tech Companies:** 3,575
* **Categories Covered:** 141
* **Total Funding Amount:** \$205 Billion USD
* **Average Funding Per Company:** \$57.56 Million USD

**Top 10 Regions by Company Count:**

| Country        | Number of Companies |
| -------------- | ------------------- |
| United States  | 2,034               |
| United Kingdom | 319                 |
| India          | 156                 |
| Canada         | 111                 |
| Germany        | 101                 |
| France         | 96                  |
| Israel         | 93                  |
| Australia      | 53                  |
| Netherlands    | 35                  |
| Brazil         | 24                  |

**Top Funded Companies:**

* **WestConnex** (\$17B)
* **SpaceX, Databricks, Articulate** (\~\$2B each)
* **Relativity Space, Robinhood, Gojek, Thrasio, Gopuff, Nubank** (\~\$1B each)

---

## 4. Insight Deep Dive

### a. Funding Trend in 2025 (Jan–Nov)

* **March 2025** shows a sharp increase in **Total Funding** reaching **\$21B**
* The trend peaks in **September 2025**, with an **Average Funding** of **\$91M**
* A steep drop follows in **October** (Average: \$23M), before recovering slightly in **November** to **\$47M**

### b. Top 10 Funding Stages

| Funding Stage  | Total Amount (USD) |
| -------------- | ------------------ |
| Series C       | \$26B              |
| Series D       | \$25B              |
| Series B       | \$19B              |
| Private Equity | \$18B              |
| Series E       | \$15B              |
| Series A       | \$12B              |
| Series F       | \$8B               |
| Series G       | \$4B               |
| Series H       | \~\$2B             |
| Seed           | \~\$2B             |

**Insight:**

* The fact that **Series C (\$26B)** and **Series D (\$25B)** dominate funding shows strong investor confidence.
* Funding sharply declines from **Series E (\$15B)** to **Series F (\$8B)** and **Series G (\$4B)**.
* **Seed** and **Series A** only receive \~$2B and \$12B respectively.


### c. Top 10 Categories by Funding

| Category                | Funding (USD) |
| ----------------------- | ------------- |
| B2B Software            | \$24B         |
| Transportation          | \$20B         |
| Finance                 | \$20B         |
| Cloud Computing         | \$17B         |
| Artificial Intelligence | \$13B         |
| Health Care             | \$10B         |
| Blockchain              | \$7B          |
| Food and Beverage       | \$7B          |
| Cyber Security          | \$7B          |
| Education               | \$6B          |

**Insight:**

* **B2B Software (\$24B)** and **Cloud Computing (\$17B)** combined account for **20%+ of total funding**.
* **Transportation** and **Finance** Both received **\$20B**.
* Categories like **Artificial Intelligence (\$13B)** and **Blockchain (\$7B)** despite being nascent or volatile are still attracting significant capital.
* **Health Care (\$10B)** and **Education (\$6B)**, attract less funding than more commercially scalable verticals.