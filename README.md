# Job Market Analyzer 📊

> **Also see:** [Interactive Power BI Dashboard](https://app.powerbi.com/groups/me/reports/57fd1d03-881f-4366-9f9c-67cb151b5aa9/0f8da061594394de6575?experience=power-bi)
 — a visual companion to this analysis, built from the same dataset using Power BI. Together, these two projects demonstrate end-to-end data analysis capability: raw Python analysis → business-ready dashboard.
 ![Job Market Dashboard Preview](job-market-BIdashboard.png)

A data analysis project exploring **61,953 real job postings** scraped from Google Search, uncovering trends in the data industry using Python, Pandas, Matplotlib, and Seaborn.

---

## 🔍 What This Project Answers

- Which job titles are most in demand right now?
- Which companies post the most data jobs?
- Is the market more remote or on-site?
- What technical skills do employers actually ask for?
- What schedule types dominate data hiring?

---

## 💡 Key Findings

| Insight | Finding |
|---|---|
| #1 Most In-Demand Skill | **SQL** — 30,000+ job postings |
| #1 Most Common Job Title | **Data Analyst** — 6,000+ postings |
| Top Hiring Company | **Upwork** — reflecting strong freelance demand |
| Remote vs On-Site | **45.2% remote**, 54.8% on-site |
| Dominant Schedule Type | **Full-time** — 72.7% of all postings |

---

## 📊 Visualizations

1. **Top 10 Most Common Job Titles** — Bar chart
2. **Top 10 Hiring Companies** — Bar chart
3. **Remote vs On-Site Split** — Pie chart
4. **Top 20 Most In-Demand Skills** — Bar chart
5. **Job Schedule Type Distribution** — Bar chart

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3.13** | Core language |
| **Pandas** | Data loading, cleaning, aggregation |
| **Matplotlib** | Chart generation |
| **Seaborn** | Styled visualizations |
| **Jupyter Notebook** | Analysis environment and documentation |

---

## 📁 Dataset

[Data Analyst Job Postings — Google Search](https://www.kaggle.com/datasets/lukebarousse/data-analyst-job-postings-google-search)
- **61,953** job postings
- **27** features including title, company, location, skills, salary, and schedule type
- Source: Kaggle

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/nestorNiloy/job-market-analyzer

# Install dependencies
pip install pandas matplotlib seaborn notebook

# Launch Jupyter
jupyter notebook

# Open job-market-analysis.ipynb
```

---

## 🔗 Related Project

This notebook pairs with an **interactive Power BI dashboard** built from the same dataset:
👉 [Job Market Dashboard — Power BI](https://app.powerbi.com/groups/me/reports/57fd1d03-881f-4366-9f9c-67cb151b5aa9/0f8da061594394de6575?experience=power-bi)

The two projects together demonstrate the full data workflow:
**Raw data → Python analysis → Business dashboard**
