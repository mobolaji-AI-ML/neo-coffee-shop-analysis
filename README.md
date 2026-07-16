# neo-coffee-shop-analysis
# ☕ neo-coffee-shop-sales-intelligence-project

📌 Project Overview

This project was completed as the final examination project for AltSchool Africa. It focuses on exploring, cleaning, and analyzing a multi-national retail coffee transaction dataset to uncover actionable business insights. The primary objectives are to understand customer purchasing behaviors across different geographical markets (United States, United Kingdom, and Ireland), identify key drivers of product profitability, and clean transactional data profiles to help improve revenue tracking, optimize menu offerings, and protect operational margins[cite: 5].

🛠️ Tech Stack & Tools

* **Language:** Python
* **Environment:** Google Colab
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Business Intelligence:** Tableau Desktop (.twbx format)
* **Version Control:** Git & GitHub

📊 Key Analysis Focus Areas

1. Data Cleaning & Transformation

* Handled 206 missing customer emails and 135 missing phone numbers by cleanly imputing them with an 'Unknown' flag to preserve transactional records[cite: 5].
* Standardized dates into proper datetime64 formats and coerced transactional numeric fields into consistent data types[cite: 5].
* Investigated and treated row-level duplicates and eliminated logical entry anomalies (e.g., ensuring quantity, sizes, and profit values are strictly greater than zero)[cite: 5].

2. Spending Behavior Analysis

* Evaluated distributions of purchase quantities and package sizes (0.2kg, 0.5kg, 1.0kg, 2.5kg) across different customer segments[cite: 5].
* Visualized structural spending patterns utilizing detailed boxplots and histograms to ensure clean baseline distributions for downstream analysis[cite: 5].

3. Product Performance & Profitability Analysis

* Identified core operational variables correlated with higher revenue generation (such as coffee bean type and roast profile combinations)[cite: 5].
* Segmented profit metrics across Arabica, Robusta, Liberica, and Excelsa varieties to highlight top-performing products[cite: 5].

4. Geographical Market Assessment

* Profiled sales volumes and profit margins across different physical regions, comparing store performance trends across the United States, United Kingdom, and Ireland[cite: 5].
* Grouped transactional habits by loyalty card holders to determine membership program impact on regional store revenue[cite: 5].

📂 Repository File Directory

├── Neo_Coffee.csv                     # Raw sales transaction logging (1,000 records)
├── altschool_second_semester_exam.ipynb # Core Python data transformation & pipeline script
├── altschoolfinalexam .twbx           # Packaged interactive Tableau dashboard workbook
├── Proposal Document neo_coffee_shop.pdf # Initial project scoping and goals
├── neo coffee shop analysis report.pdf   # In-depth statistical analysis report
└── finalsemesteraltschoolprojectExcecutive summary.pdf # Business-ready executive brief

🚀 Quick Start

1. Clone this repository:
   git clone https://github.com/your-username/neo-coffee-sales.git

2. Install dependencies:
   pip install pandas numpy matplotlib seaborn

3. Open the cleaning notebook inside Google Colab or your local Jupyter server to view the pipeline execution.
