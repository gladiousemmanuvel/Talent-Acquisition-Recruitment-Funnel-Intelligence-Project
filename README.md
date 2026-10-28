# 🎯 Talent Acquisition & Recruitment Funnel Intelligence Dashboard

## 📝 Project Overview
This project analyzes end-to-end recruitment funnel data across candidates, applications, interview stages, and job offers. Using the **Multi-Company HR Analytics** raw dataset, Python for exploratory data cleaning, MySQL for relational database transformation, and Power BI for interactive visualization, it tracks key hiring metrics, sourcing channel performance, and recruitment funnel efficiency.

## 🛠️ Tools & Technologies Used
* **Dataset:** Multi-Company HR Analytics (Raw HR Tables: `applications`, `candidates`, `interviews`, `offers`, `jobs`, `employees`, `performance_reviews`, `attrition_events`, etc.)
* **Programming Language:** Python (Pandas, NumPy)
* **Database & Querying:** MySQL Workbench (`applications_master`, `interviews`, `offers`)
* **Data Visualization:** Power BI (`Talent Acquisition & Recruitment Funnel Intelligence.pbix`)
* **Development Environment:** Jupyter Notebook

## 📁 Repository & Folder Structure
```text
Talent Acquisition & Recruitment Funnel Intelligence/
├── data/
│   ├── raw_data/
│   │   └── Multi-Company HR Analytics/       # Original multi-table HR datasets
│   └── cleaned_data/
│       ├── applications_master.csv           # Master candidate application records
│       ├── interviews.csv                    # Cleaned interview stage records
│       └── offers.csv                        # Processed job offer datasets
├── sql/
│   └── recruitment_queries.sql               # MySQL queries for table joining & analytics
├── Talent Acquisition & Recruitment Funnel Intelligence.ipynb   # Python EDA notebook
├── Talent Acquisition & Recruitment Funnel Intelligence.pbix    # Power BI report file
├── Talent Acquisition & Recruitment dashboard.png               # Dashboard screenshot preview
└── README.md                                     # Project documentation