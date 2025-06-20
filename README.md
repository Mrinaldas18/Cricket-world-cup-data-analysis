# 🏏 T20 World Cup Cricket Data Analytics Project

This project is a complete **end-to-end sports data analytics case study** focused on the **ICC T20 World Cup 2022**. It combines data engineering, statistical analysis, and business intelligence to deliver deep insights into team and player performances. The project walks through every phase of a real-world analytics workflow—from data scraping to final visualization—making it an ideal showcase for data analysts, data scientists, and BI developers.

---

## 📌 Problem Statement

Cricket generates vast amounts of data, especially during major tournaments like the T20 World Cup. However, extracting actionable insights from such raw data can be challenging. The goal of this project is to build a data-driven model to:

* Scrape and clean live match data.
* Analyze batting and bowling performance.
* Visualize key metrics through interactive dashboards.
* Select a "Best XI" team from Earth that could theoretically challenge any opponent—even aliens.

---

## 🔧 Tools & Technologies Used

* **Bright Data** – Web Scraper IDE for extracting data from ESPN Cricinfo.
* **Python (Pandas)** – For cleaning, preprocessing, and transforming JSON into CSV.
* **Power Query** – For further data transformation within Power BI.
* **Power BI** – For dashboard creation and data visualization.
* **DAX (Data Analysis Expressions)** – For modeling relationships and KPIs.
* **ESPN Cricinfo** – Source of structured and unstructured cricket data.

---

## 📊 Project Workflow

### 1️⃣ Requirement Scoping

* Define key questions: top performers, best strike rates, ideal bowling attack, etc.
* Understand data requirements and expected output (dashboard + insights).

### 2️⃣ Web Scraping

* Used **Bright Data** to build collectors for match scorecards and player stats.
* Extracted data such as batting summaries, team stats, and match results.

### 3️⃣ Data Transformation (Python)

* Converted raw JSON data into structured CSV.
* Used **Pandas** to clean, normalize, and reshape data tables (fact & dimension format).

### 4️⃣ Power BI Dashboard

* Imported CSV files into Power BI.
* Applied **Power Query** to build calculated columns (e.g., match stages).
* Built relationships between tables (batting, matches, teams).
* Created **DAX measures**: total runs, average, strike rate, wickets, economy, etc.
* Designed an interactive and visually rich dashboard.

### 5️⃣ Insight Generation

* Identified top performers by filters: team, stage, opposition, venue, etc.
* Selected the **Best XI** based on statistical performance (e.g., Jos Buttler, Rilee Russouw, Marcus Stoinis).
* Balanced team with openers, power hitters, all-rounders, and bowlers.

---

## 📌 Key Features

* 🧠 **Real-time data extraction** using web scraping
* 🧹 **Data cleaning & transformation** with Python
* 📊 **Dynamic Power BI dashboard** with filters and slicers
* 🏅 **Selection logic** for fantasy cricket-style team building
* 📊 Performance metrics: strike rate, average, wickets, economy rate
* 📂 Modular folder structure and reusable codebase

---

## 📷 Screenshots

> *![Bright Data](https://github.com/user-attachments/assets/a1fbdd55-c2cd-4e58-bcf4-4e521b80c0cb)*
> *![Bi2](https://github.com/user-attachments/assets/be8d2269-76d2-4589-9e6e-09a150ec392c)*
> *![Bi1](https://github.com/user-attachments/assets/613d6b04-a299-4927-8247-30b096ae2903)*



---

## 💡 Learnings & Takeaways

* Gained hands-on experience in **data scraping** using Bright Data.
* Strengthened understanding of **ETL (Extract, Transform, Load)** pipelines.
* Practiced **data storytelling** and dashboard design for non-technical users.
* Understood real-world cricket metrics and applied **data-driven decision making**.
* Improved DAX skills by creating custom KPIs and analytical summaries.

---

## 📁 Folder Structure

```
📆 cricket-data-analytics/
👥🗂️ data/
    └️ batting_summary.csv
    └️ match_info.csv
👥🗂️ notebooks/
    └️ data_cleaning.ipynb
👥🗂️ powerbi/
    └️ dashboard.pbix
📄 README.md
📄 requirements.txt
```

---

## 🔗 Resources

* [Bright Data Web Scraper](https://brdta.com/codebasics)
* [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Python Official Site](https://www.python.org/)
  

---

## 🚀 How to Run This Project

1. Clone the repository
2. Run `data_cleaning.ipynb` to preprocess the JSON data
3. Open `dashboard.pbix` in Power BI Desktop
4. Explore filters, metrics, and insights

---

## ✅ Ideal For

* Data analytics beginners & intermediate learners
* Students building real-world project portfolios
* Job seekers preparing for analytics or BI roles
* Cricket fans who love combining sports with data

---

## 📣 Let’s Connect!

If you liked this project or want to collaborate on something similar, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/mrinal-das18/) or explore more on my [GitHub profile](https://github.com/Mrinaldas18).
