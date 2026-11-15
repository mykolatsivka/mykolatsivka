### Hi, I'm Mykola 👋

**Aspiring Data Analyst from Ukraine 🇺🇦, studying in Slovakia 🇸🇰.** I like taking messy real-world data, cleaning it, finding what matters, and turning it into something people can use.

🔎 **Looking for:** Junior Data Analyst / Data Analyst Intern roles

---

### 🎓 Background

- **Applied Computer Science**, Technical University of Košice (2025–2030, in progress)
- **Mate Academy, Data Analytics course** (2026, in progress): mentor-reviewed SQL practice in Google BigQuery on realistic e-commerce datasets (web sessions, orders, payments, email campaigns, ad spend)
- Scored **200/200** on Ukraine's national exams in Mathematics and English
- Spent ~1.5 years on front-end development, then deliberately switched to data analytics
- **Languages:** Ukrainian (native), English and Slovak (upper-intermediate)

---

### 🛠 Skills

**SQL (Google BigQuery), my main focus:** JOINs (incl. through bridge tables and time-interval conditions), GROUP BY / HAVING, CASE WHEN, UNION ALL, subqueries, window functions (RANK, DENSE_RANK, AVG OVER PARTITION BY), date/time and string functions
**Python:** pandas, NumPy, matplotlib; core Python
**Visualization:** Tableau (calculated fields, dashboards), matplotlib, Google Sheets
**Data foundations:** relational databases, ER diagrams, normalization (1NF–3NF), data quality checks, descriptive statistics
**Data pipelines:** web scraping, APIs, ETL, scheduled jobs (GitHub Actions)
**Tools:** Google BigQuery, Git & GitHub, Google Workspace, LeetCode (SQL), AI tools for analysis and automation

#### Examples of SQL tasks I've solved
- Combined daily ad spend and order revenue with `UNION ALL`, grouped by year and month, and found why `SUM(DISTINCT)` after a JOIN gives wrong totals
- Calculated email unsubscribe rates by country through bridge tables, and segmented countries into revenue tiers with `CASE WHEN` over aggregates
- Measured session duration from event timestamps, plus revenue per session for registered vs. guest users
- Ranked employees by salary within departments and compared them to the department average without collapsing rows (window functions)

---

### ⭐ Featured projects

#### ⚡ [Power outages in Ukraine: what 3 weeks of official schedules show](https://github.com/mykolatsivka/ukraine-power-outages-analysis)
An end-to-end analysis of **1,643 snapshots** of official outage schedules from 6 regional grid operators (Oct 25 – Nov 14, 2026).
- Built the dataset from the git history of my own data pipeline: versioning, deduplication, final schedules, Kyiv time
- Answered 5 questions with SQL (CTEs, JOINs, `CASE WHEN`, `HAVING`, window functions): regional ranking, weekly trend, time-of-day profile, schedule stability, fairness between queues
- **Findings:** Kyiv city averaged 13.4 h a day without power per queue (about 3× Odesa); outages peak at 14:00–17:00; in Mykolaiv the schedule changed on 92% of days, almost always on the day itself

`SQL` `Python` `pandas` `matplotlib` `Jupyter` `Tableau`

#### 📊 [DataLens Desktop](https://github.com/mykolatsivka/semester-project-python)
A desktop app for exploratory data analysis of any CSV file.
- Data quality report: missing values, duplicates and an overall quality score
- Filters for numeric, categorical, text and date columns
- Descriptive statistics, a correlation matrix, and group comparison by mean, median or sum
- Histograms, box plots, scatter plots and bar charts, plus export of the filtered data
- History of analysis snapshots saved to SQLite, covered by unit tests

`Python` `pandas` `NumPy` `matplotlib` `SQLite` `PySide6` `pytest`

#### 🌻 [Sonyakh](https://github.com/mykolatsivka/sonyakh): live at [sonyakh.pp.ua](https://sonyakh.pp.ua)
An app used by people in Ukraine during blackouts. Behind it is an automated data pipeline:
- **ETL from 11 different sources:** collects power outage schedules from regional grid operators every 15 minutes. The sources include REST APIs, HTML tables and legacy encodings, all normalized into one consistent dataset.
- **Data quality first:** ambiguous or unexpected values are flagged instead of shown, and a failed source keeps its last valid data marked as stale.
- **Text classification:** scores and filters news from 5 media feeds hourly using weighted keywords, blocklists and de-duplication.
- **Privacy-friendly usage analytics** without cookies, with PostgreSQL row-level security on user data.

`JavaScript` `Node.js` `SQL` `PostgreSQL` `ETL` `GitHub Actions`

#### ⏰ [Arduino Alarm Clock](https://github.com/mykolatsivka/Arduino)
Embedded project: reads temperature, humidity and real-time clock data on an Arduino UNO, with a menu-driven LCD interface.

`C++` `Arduino`
