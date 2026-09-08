# 🏎️ Beyond the Fastest Car
### Formula 1 Data Analysis Using Python, Statistics, SQL, and Power BI

## 📌 About the Project

**Beyond the Fastest Car** is a Formula 1 data analytics project developed as the final capstone project of a Data Analytics bootcamp.

The goal of the project is to investigate which factors are most associated with competitive performance in Formula 1, going beyond the idea that race results depend only on having the fastest car.

The project follows an end-to-end data analytics workflow, including data exploration and preparation, statistical analysis, SQL queries, data visualization, and presentation of business insights.

---

## 🎯 Business Problem

The analysis is guided by the following main question:

> **Which factors are most associated with competitive performance in Formula 1?**

Three analytical questions were investigated:

1. **How is starting grid position associated with race performance?**
2. **Which drivers show the greatest ability to gain positions during races?**
3. **What is the relationship between qualifying performance and final race results?**

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - SciPy

- **Jupyter Notebook**
  - Data exploration
  - Data preparation
  - Statistical analysis

- **MySQL**
  - Relational data modeling
  - JOINs
  - Aggregations
  - Analytical queries

- **Power BI**
  - Data visualization
  - Dashboard development

- **PowerPoint**
  - Presentation of findings and recommendations

---

## 🔄 Project Workflow

```text
Data
  ↓
Python / EDA
  ↓
Statistical Analysis
  ↓
MySQL / SQL
  ↓
Power BI
  ↓
Insights & Recommendations
```

Each stage of the project was designed to support a different part of the analysis, creating a structured workflow from raw data to actionable insights.

---

## 📊 Dataset

The project uses historical Formula 1 data publicly available on Kaggle.

The dataset includes information related to:

- Races
- Drivers
- Constructors
- Race results
- Starting grid positions
- Qualifying results
- Pit stops
- Lap times
- Seasons
- Race status
- Other historical Formula 1 information

The data was explored in Python and organized into relational tables for SQL analysis.

---

## 🔍 Methodology

### 1. Python & Exploratory Data Analysis

The first stage focused on understanding and preparing the data.

The process included:

- Importing and inspecting the datasets
- Reviewing table structures
- Checking data types
- Handling relevant missing values
- Preparing variables required for the analysis
- Performing exploratory data analysis
- Investigating relationships between starting position and race performance

---

### 2. Statistical Analysis

Statistical tests were used to evaluate whether the differences observed between starting-position groups were statistically significant.

Drivers were divided into two groups:

- **Grid positions 1–10**
- **Grid positions above 10**

The analysis included:

- **Levene's Test**
- **Welch's t-test**
- **Mann–Whitney U Test**

This stage provided statistical evidence to complement the exploratory analysis.

---

### 3. SQL & Relational Analysis

The data was structured in MySQL to answer the project's business questions using SQL.

The analysis included:

- `JOIN`
- `GROUP BY`
- `AVG`
- `COUNT`
- `SUM`
- `CASE WHEN`
- `ORDER BY`
- `LIMIT`

The `results` table served as one of the central tables in the analysis, connecting race results with drivers, constructors, and races.

---

### 4. Power BI

The main analytical results were transformed into visualizations using Power BI.

The dashboards focused on the three main business questions:

- Starting grid position vs. race performance
- Drivers with the highest average positions gained
- Qualifying position vs. final race result

The visualizations were designed to communicate the findings clearly and concisely.

---

## 📈 Key Findings

The analysis identified a strong association between starting position and race performance.

Key findings include:

- Drivers starting from **pole position won 58.24%** of the races analyzed.
- **86.10% of race victories** were achieved by drivers starting within the top three grid positions.
- Drivers starting closer to the front generally achieved better finishing positions and earned more points.
- Qualifying performance showed a consistent association with final race results.
- Although starting position is important, some drivers demonstrated a stronger ability to recover positions during races.

These findings suggest that competitive performance in Formula 1 is influenced by multiple factors, while qualifying and starting position represent significant competitive advantages.

---

## 💡 Recommendations

### Prioritize Qualifying Performance

The strong relationship between starting position and race results suggests that improving qualifying performance can provide a significant competitive advantage.

### Optimize Race Execution

Starting position alone does not determine the final result. Race strategy, consistency, and the ability to gain positions remain important factors in maximizing performance.

---

## 📁 Repository Structure

```text
Formula1-FinalProject/
│
├── README.md
│
├── notebooks/
│
├── data/
│
├── sql/
│
├── dashboard/
│
├── presentation/
│
└── images/
```

The final repository structure will reflect the notebooks, datasets, SQL files, dashboards, and presentation materials used in the project.

---

## ⚠️ Limitations

The project includes several limitations that should be considered when interpreting the results:

- Data availability varies across Formula 1 seasons.
- Some historical records contain missing values.
- Certain modeling tools had limitations when representing database relationships.
- Some dashboard elements were simplified to improve readability.

The findings should therefore be interpreted within the context of the dataset and analytical scope used in this project.


---

## 📚 Data Source

Historical Formula 1 dataset available on Kaggle:

**Formula 1 World Championship (1950–2020)**  
Rohan Rao — Kaggle
