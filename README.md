#  What the Data Analyst Job Market Is *Really* Asking For

This project is not just another exploratory data analysis notebook.
It is a **market decoding exercise** — built to answer one practical question:

> *If someone wants to get hired as a Data Analyst, what does the data say they should focus on?*

Using a real-world Glassdoor dataset of Data Analyst job postings, this project translates raw job listings into **clear career insights, skill priorities, and salary patterns**.

---

##  Why This Project Is Different

Most job-market analyses stop at charts and averages.

This project goes further by:

* Treating job listings as **market signals**, not just rows of data
* Cleaning messy, real-world fields exactly how analysts do on the job
* Converting analysis into **actionable recommendations** for job seekers

Every step mirrors how data is handled in professional analytics roles — from raw ingestion to business-ready insights.

---

##  Dataset Overview

**Source:** Glassdoor Data Analyst job postings
**Size:** 2,253 job listings × 16 features

Key attributes include:

* Job title & description
* Salary estimates
* Company rating, size, industry, and sector
* Location and ownership type
* Hiring signals such as *Easy Apply* and competitors

---

## 🔧 What Was Done (End-to-End)

### 1️. Data Cleaning (Real-World Style)

* Removed redundant index columns
* Cleaned salary ranges by stripping currency symbols and units (e.g., `$`, `K`)
* Extracted **minimum, maximum, and average salary** values
* Handled placeholder values like `-1` by replacing them with meaningful labels
* Corrected data types to enable reliable analysis

> This step intentionally handles *messy edge cases* to reflect real datasets, not textbook examples.

---

### 2️. Feature Engineering

New variables were created to make the data analysis-ready:

* `Min_Salary`, `Max_Salary`, `Avg_Salary`
* Binary indicators for in-demand skills (SQL, Python, Excel, Tableau, Power BI)
* Cleaned categorical fields for industry, sector, and company size

---

### 3️. Exploratory Data Analysis

The analysis focused on questions that matter:

* Where do most Data Analyst salaries actually fall?
* Do senior roles consistently pay more?
* Which industries hire the most analysts?
* Are higher-rated companies paying better?
* Which technical skills appear most frequently in job descriptions?

Visualizations were used only where they **added clarity**, not noise.

---

##  Key Insights (Market Signals)

* **SQL and Python** dominate job requirements — they are baseline skills, not optional
* Mid-level salaries cluster strongly, showing demand for analysts with some experience
* Senior roles clearly command higher pay
* IT and Healthcare sectors lead Data Analyst hiring
* Mid-to-large companies tend to offer more competitive salaries
* High company ratings loosely correlate with better compensation

---

##  Practical Recommendations

### For Aspiring Data Analysts

* Prioritize SQL and Python before chasing niche tools
* Build projects that show **business reasoning**, not just code
* Target technology-driven and data-heavy industries

### For Career Growth

* Moving from reporting to insight generation unlocks higher-paying roles
* Salary growth aligns closely with responsibility, not just tenure

---

##  Tools & Technologies

* **Python** (Pandas, NumPy)
* **Matplotlib & Seaborn** for visualization
* **Jupyter Notebook** for iterative analysis

---

##  How This Project Can Be Used

* Portfolio project for Data Analyst roles
* Interview discussion on real-world data cleaning
* Reference for job-market-driven skill planning
* Foundation for future predictive or dashboard-based analysis

---

##  Final Thought

This project shows that becoming a Data Analyst is not about learning *everything* —

It’s about learning the **right things**, at the **right depth**, for the **right market**.

The data makes that clear.

---

*If you’re reviewing this as a recruiter or hiring manager: this project reflects how the candidate thinks, cleans data, and turns analysis into decisions — not just charts.*
