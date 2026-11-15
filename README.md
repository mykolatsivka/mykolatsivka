### Hi, I'm Mykola 👋

**Aspiring Data Analyst from Ukraine.** I like taking messy real-world data, cleaning it, finding what matters, and turning it into something people can use.

🔎 **Looking for:** Junior Data Analyst / Data Analyst Intern roles

---

### 🛠 Skills

**Data analysis:** Python (pandas, NumPy), SQL (PostgreSQL, SQLite), descriptive statistics, correlations, group comparisons, data quality checks
**Visualization:** matplotlib, charts for non-technical users
**Data pipelines:** web scraping, APIs, ETL, scheduled jobs (GitHub Actions)
**Tools:** Git & GitHub, VS Code, Excel

---

### ⭐ Featured projects

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
