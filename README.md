# 📊 Data Analytics Portfolio

A collection of data analytics projects, case studies, and scripts showcasing work in **exploratory data analysis (EDA)**, **data visualization**, and **applied machine learning**. This repository serves as a portfolio of hands-on work with real-world datasets across socio-economic, public health, and scientific domains.

---

## 📌 About

This repository contains my data analytics projects, case studies, and scripts. It showcases work in exploratory data analysis (EDA), visualization, and applied machine learning, with a focus on turning raw data into actionable insight.

---

## 📂 Projects

| Project | Description | Type | Tools |
|---------|-------------|------|-------|
| 🌍 **Youth Unemployment & Digital Access in Africa (2015–2023)** | Interactive Excel dashboard analysing youth unemployment vs. internet penetration across 14 African nations using World Bank Development Indicators. | Dashboard · Case Study | Excel (PivotTables, PivotCharts, Slicers, KPI cards) |
| 🚖 **Automatidata Project Lab (Course 2: Get Started with Python)** | Initial data inspection, DataFrame construction, variable identification, and summary statistics for the NYC TLC dataset. | Course Project · Python | Python, Pandas, NumPy, Jupyter |
| 🚖 **Automatidata Project Lab (Course 3: Go Beyond the Numbers)** | Exploratory data analysis, box plots, time series plots, and Tableau storytelling for the NYC Taxi and Limousine Commission dataset. | Course Project · EDA | Python, Pandas, NumPy, Matplotlib, Seaborn, Tableau Public |
| 🧠 **Stroke Risk Analysis Capstone** | End-to-end analysis of stroke risk factors using exploratory data analysis and predictive modeling. | Capstone · ML | Python, Pandas, Scikit-learn, Matplotlib, Seaborn |
| 🌌 **BRICS Astronomy Data Analytics** | Cross-country analysis of astronomy-related data across BRICS nations, exploring research output and policy relevance. | Case Study · EDA | Python, Jupyter, Visualization |
| 🚗 **Automatidata Project Lab (Course 4)** | Data analytics lab from the Google Advanced Data Analytics program focused on real-world business insights. | Course Project · EDA | Python, Pandas, Jupyter |

---

## 🚖 Featured Course Project: Automatidata (Course 2 – Get Started with Python)

**Project/Client:** New York City Taxi and Limousine Commission (NYC TLC) / Automatidata
**Stage:** Course 2 End-of-Course Project (Inspect and Analyze Data)

### 📖 Overview

An introductory data inspection and analysis activity designed to examine data provided by the NYC TLC, ensuring it is ready to answer questions, yield insights, support visualizations, and prepare for future statistical methods.

### 🎯 Project Goals & PACE Framework

- **Plan:** Define business objectives, load datasets into Pandas DataFrames, and categorize variables.
- **Analyze:** Build DataFrames, run summary inspections (`df.head()`, `df.info()`, `df.describe()`), and investigate specific variables like `trip_distance` and `total_amount`.
- **Execute:** Summarize data quality findings, data type conversions, and key behavioral insights for supervisor DeShawn Washington and the data team.

### 🔍 Key Findings & Summary for DeShawn

- **Data Quality Issues:** Identified negative values in `fare_amount` and `total_amount`, zero passenger counts, and inflated totals for short or zero-distance trips.
- **Data Type Conversions:** Highlighted that trip datetime columns (`tpep_pickup_datetime`, `tpep_dropoff_datetime`) need to be converted from strings to proper datetime objects.
- **Behavioral Insights:** Observed that credit card payments feature significantly higher average tips (~$2.73) compared to cash payments (~$0.0).
- **Key Predictive Variables:** Determined that `trip_distance` and `payment_type` are among the most helpful variables for future predictive modeling.

---

## 🌍 Featured Project: Youth Unemployment & Digital Access in Africa (2015–2023)

**Prepared for:** YouthUp Global Ecosystem — People & Culture Team
**Role:** Volunteer Data Analyst Assessment
**Author:** Andre Philip Nyanjahia

### 📖 Overview

An analysis of **14 African nations** using **World Bank Development Indicators** to test whether digital expansion is translating into improved youth employment outcomes across the region.

### 🎯 Why This Dataset

Selected because it directly aligns with YouthUp Global's mission of **youth empowerment, workforce development, and digital skills expansion**. By combining an economic indicator (youth unemployment) with a digital access indicator (internet penetration), the analysis tests whether digital growth is improving youth employment outcomes. World Bank data provides highly credible, standardized, and comparable indicators across all 14 nations.

### 🔍 Key Insights

- **2023 Regional Snapshot:** Average youth unemployment = **8.3%**; average internet penetration = **35.7%**.
- **Highest Risk Country:** **Rwanda** — highest youth unemployment in 2023 at **18.2%**.
- **Trend Volatility:** Regional youth unemployment declined from **9.1% (2015)** to **8.3% (2023)**, but peaked at **9.0% (2018–2019)**, showing vulnerability to economic shocks.
- **Digital Correlation:** Countries with higher internet penetration showed **mixed** youth unemployment outcomes.
- **Takeaway:** Digital access is a **critical enabler**, but **not a standalone solution** — digital skills must be paired with economic opportunities and job creation.

### ✅ Recommendations

1. **Targeted Digital-Skills Training** — Prioritise digital literacy and advanced IT training in high-unemployment, low-penetration countries (e.g., Rwanda, Tanzania, Uganda).
2. **Public-Private Job Pipelines** — Partner with local employers, tech hubs, and startups in the highest-unemployment countries to create structured internship and job placement pipelines.
3. **Continuous Monitoring** — Institutionalise this dashboard annually to track KPIs year-over-year, adapt interventions, and allocate resources to critical regions.

### 🛠️ Technical Highlights

- Clean dashboard layout with **3 KPI cards**
- **4 charts:** Scatter Plot, Line Chart, Bar Chart, Column Chart
- **Interactive Slicer** connected to a backend PivotTable
- Built entirely in **Advanced Microsoft Excel**

### 📦 Deliverables

- 🗂️ **Interactive Dashboard:** `Andre_Philip_Nyanjahia_Data_Analyst_Dashboard.xlsx`
- 📄 **Source Dataset:** `Andre_Philip_Nyanjahia_Dataset.xlsx`
- 📝 **Executive Summary:** `Andre_Philip_Nyanjahia_One_Page_Summary.pdf` / `.docx`

> **Data Source:** World Bank — World Development Indicators
> **Indicators Used:**
> - `SL.UEM.1524.ZS` — Unemployment, youth total (% of labour force ages 15–24)
> - `IT.NET.USER.ZS` — Individuals using the Internet (% of population)

---

## 🧰 Tools & Technologies

**Languages & Libraries**

- Python — `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `Plotly`
- SQL — data extraction, joins, aggregations, window functions

**Environments & Tools**

- Advanced Microsoft Excel (PivotTables, PivotCharts, Slicers, KPI dashboards)
- Tableau / Tableau Public
- Jupyter Notebooks / Google Colab
- Git & GitHub

---

## 📁 Repository Structure

```
Data_Analytics/
│
├── Andre_Philip_Nyanjahia_Data_Analyst_Dashboard.xlsx   # YouthUp Global dashboard
├── Andre_Philip_Nyanjahia_Dataset.xlsx                  # YouthUp Global source data
├── Andre_Philip_Nyanjahia_One_Page_Summary.pdf          # YouthUp Global summary
├── Course 2 Automatidata project lab.ipynb              # NYC TLC Python inspection course lab
├── Course 3 Automatidata project lab.ipynb              # NYC TLC EDA & Tableau course lab
├── AndreNyanjahia_Capstone_StrokeRiskAnalysis.ipynb     # Stroke risk ML capstone
├── BRICS_ASTRONOMY_DATA_ANALYTICS_CAPSTONE_PROJECT.pdf  # BRICS astronomy case study
├── Course 4 Automatidata project lab.ipynb              # Automatidata course lab
└── README.md                                            # Project documentation
```

---

## 🎯 Skills Demonstrated

- **Exploratory Data Analysis (EDA)** — cleaning, summarising, and visualising datasets
- **Data Visualization** — building clear, narrative-driven plots, dashboards, and Tableau visualisations
- **KPI Development & Dashboard Engineering** — designing interactive Excel dashboards
- **Trend Analysis & Correlation Modeling** — identifying relationships between indicators
- **Applied Machine Learning** — classification, predictive modeling, and model evaluation
- **Data Storytelling** — translating data into insight for technical and non-technical audiences
- **Reproducible Workflows** — documented notebooks and version-controlled scripts

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Andre-tech671/Data_Analytics.git
   cd Data_Analytics
   ```

2. **Set up your Python environment** *(for notebooks)*
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn plotly jupyter
   ```

3. **Open any notebook**
   ```bash
   jupyter notebook
   ```
   Or upload the `.ipynb` files directly to [Google Colab](https://colab.research.google.com/).

4. **Open the Excel dashboard**
   - Launch `Andre_Philip_Nyanjahia_Data_Analyst_Dashboard.xlsx` in Excel (2016 or later recommended for full slicer/pivotchart support).

---

## 📈 Highlights

- ✅ Interactive Excel dashboard delivering actionable insight for a real youth-development organisation
- ✅ End-to-end capstone project applying ML to healthcare data
- ✅ Comprehensive EDA and Tableau visual storytelling for NYC taxi ridership patterns
- ✅ Structured data inspection and Python workflow from Course 2 of the Google Advanced Data Analytics certificate
- ✅ Cross-disciplinary case study (astronomy + policy) across BRICS nations
- ✅ Clean, documented, and reproducible analysis assets

---

## 📜 License

This repository is licensed under the **MIT License**. Feel free to use and adapt the code with attribution.

---

## 🤝 Connect

**Author:** Andre Philip Nyanjahia ([@Andre-tech671](https://github.com/Andre-tech671))
**Role:** Data Analyst · MEL Specialist
**📧 Email:** nyanjahia@gmail.com
**📞 Phone:** +265 882098484
**🔗 LinkedIn:** [andre-nyanjahia-ab664228](https://linkedin.com/in/andre-nyanjahia-ab664228)

> *"Leveraging data to empower the next generation of African youth through strategic workforce development."*

If you find this repository useful, consider giving it a ⭐ — it helps others discover the work!

---

*Last Updated: September 2026*
