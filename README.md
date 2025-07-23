# global-ai-job-market-2025
# 🤖 Power BI Project: Global AI Job Market & Salary Trends 2025

## 📌 Project Overview

This Power BI project analyzes the global job market and salary trends in the AI industry for the year 2025. The objective is to uncover key insights regarding regional demand, job roles, industry trends, and salary distributions across various AI specializations and geographies.

This dashboard is intended to assist recruiters, job seekers, and policy analysts in understanding the dynamics of the global AI labor market.

---

## 📁 Project Structure

```

global-ai-job-market-2025/
├── data/
│   ├── raw/                      # Original dataset (CSV/XLSX)
│   └── cleaned/                  # Cleaned and transformed data
├── report/
│   └── Global\_AI\_Jobs\_2025.pbix # Power BI report
├── images/
│   └── dashboard.png             # Dashboard screenshot
├── README.md                    # Project documentation
└── LICENSE                      # Optional license

```

---

## 📈 Dashboard Preview

![Dashboard Screenshot](images/dashboard.png)

---

## 🧮 Data Source

- **Dataset Name:** Global AI Job Market & Salary Trends 2025
- **Source:** [Kaggle]
- **Records:** [15,000+ job listings from 50+ countries]
- **Key Fields:**
  - `Country/Region`
  - `Job Title`
  - `Industry`
  - `Required Skills`
  - `Salary (USD)`
  - `Experience Level`
  - `Remote/Flexible`
  - `Posting Date`
- **Key Features:**
  - `Salary data in multiple currencies (normalized to USD)`
  - `Experience level categorization (Entry, Mid, Senior, Executive)`
  - `Company size impact analysis`
  - `Remote work trends and patterns`
  - `Skills demand analysis`
  - `Geographic salary variations`
  - `Time-series data showing market evolution`
    
---

## 🛠️ Tools & Techniques

- **Power BI Desktop**
- **Power Query:**
  - Text cleaning and null value handling
  - Standardization of job titles and locations
  - Salary normalization
- **DAX Measures:**
  - Average Salary by Role/Region
  - Salary Distribution by Experience
  - Job Posting Trends by Month
- **Data Modeling:**
  - Fact table: Job Listings
  - Dimension tables: Region, Role, Industry, Experience Level

---

## 🔍 Key Insights

- 🇺🇸 The USA leads in AI job demand, followed by India and Germany.
- 💰 Research Scientists and Machine Learning Engineers have the highest median salaries globally.
- 🌍 Remote roles comprise over 35% of total listings, especially in North America and Europe.
- 📈 There is a noticeable rise in demand for generative AI roles (e.g., Prompt Engineer, LLM Developer).

---

## 🧭 Future Improvements

- Include historic trends for comparison (e.g., 2020–2025)
- Add skills co-occurrence analysis using network graphs
- Integrate company-level hiring data
- Deploy dashboard to Power BI Service with filters by region and job type

---

## 📜 License

This project is released under the [CC0: Public Domain](LICENSE).

---

## 📬 Contact

Created by **[Your Name]** – [your.email@example.com]  
Feel free to reach out or fork this project for your own analysis!
```
