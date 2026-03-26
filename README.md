<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Data%20Analysis%20Internship&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Month%201%20%7C%20Rhombix%20Technologies&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

<p>
  <img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-Visualization-4C8CBF?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Charts-11557c?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Dataset-Titanic-critical?style=flat-square&logo=kaggle&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square"/>
</p>

</div>

---

## 🌟 Overview

> *A hands-on data analysis internship project completed as part of the **Month 1** curriculum at **Rhombix Technologies**. This notebook walks through two core data science disciplines — data cleaning and exploratory analysis — applied to the iconic Titanic dataset.*

This project demonstrates real-world proficiency in:
- **Collecting** and loading datasets programmatically (no manual downloads)
- **Cleaning** messy, incomplete data with industry-standard techniques
- **Exploring** patterns, statistics, and correlations through rich visualizations

---

## 📁 Repository Structure

```
📦 Data-Analysis-Internship-Month1
 ┣ 📓 Project1_Data_Analysis.ipynb   ← Main notebook (both projects)
 ┣ 📄 cleaned_titanic.csv            ← Output from Project 1
 ┗ 📖 README.md                      ← You are here
```

---

## 🚀 Projects

### 📌 Project 1 — Data Collection & Cleaning

| Step | Task | Technique |
|------|------|-----------|
| 1 | Import libraries & load dataset | `pd.read_csv()` via GitHub URL |
| 2 | Inspect structure & missing values | `df.info()`, `df.isnull().sum()` |
| 3 | Remove duplicate rows | `df.drop_duplicates()` |
| 4 | Handle missing values | Median fill (Age), Mode fill (Embarked), Drop (Cabin) |
| 5 | Fix formatting issues | `.str.strip()`, `.str.lower()` |
| 6 | Export clean data | Saved as `cleaned_titanic.csv` |

**Goal:** Transform raw, messy data into a reliable, analysis-ready dataset.

---

### 📌 Project 2 — Exploratory Data Analysis (EDA)

| Step | Task | Output |
|------|------|--------|
| 1 | Basic statistics | Mean, Median, Min, Max via `df.describe()` |
| 2 | Survival analysis | Survival rates by gender & class |
| 3 | Outlier detection | Age & Fare distribution using boxplots |
| 4 | Correlation analysis | Heatmap of numeric feature correlations |
| 5 | Visualizations | Bar charts, Histograms, Line graphs |

**Goal:** Extract meaningful insights and understand the story hidden in the data.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `Python 3.10` | Core programming language |
| `Pandas` | Data manipulation & cleaning |
| `Matplotlib` | Base plotting library |
| `Seaborn` | Statistical data visualizations |
| `Google Colab` | Cloud notebook environment |

---

## ▶️ How to Run

### Option 1 — Google Colab (Recommended)
1. Open `Project1_Data_Analysis.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Click **Runtime → Run all**
3. No setup required — dataset loads automatically from URL ✅

### Option 2 — Local Setup
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/Data-Analysis-Internship-Month1.git
cd Data-Analysis-Internship-Month1

# Install dependencies
pip install pandas matplotlib seaborn

# Launch Jupyter
jupyter notebook Project1_Data_Analysis.ipynb
```

---

## 📊 Dataset

| Field | Details |
|-------|---------|
| **Name** | Titanic Passenger Dataset |
| **Source** | [datasciencedojo/datasets](https://github.com/datasciencedojo/datasets) |
| **Rows** | 891 passengers |
| **Columns** | 12 features |
| **Target** | `Survived` (0 = No, 1 = Yes) |

**Key Features:** `PassengerId`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## 🎯 Key Learnings

- ✅ How to load real-world datasets directly from URLs using Pandas
- ✅ Strategies for handling different types of missing data (numeric vs categorical)
- ✅ When to fill vs when to drop missing columns
- ✅ How to detect and visualize outliers with boxplots
- ✅ Reading correlation heatmaps to understand feature relationships
- ✅ Building clear, labeled visualizations for non-technical audiences

---

## 👤 Author

<div align="center">

**Mumtaz Ali**
*Data Analysis Intern @ Rhombix Technologies*

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/YOUR_USERNAME)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

*Made with 💜 during the Rhombix Technologies Data Analysis Internship*

</div>
