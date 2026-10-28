# 🎯 Talent Acquisition & Recruitment Funnel Intelligence Dashboard

## 📌 Project Overview
Engineered to evaluate candidate drop-off points, analyze recruitment channel efficiency, and predict pipeline bottlenecks across various hiring stages to optimize talent acquisition strategies. This multi-company HR analytics project consolidates candidate records using Python for ETL preprocessing, MySQL Workbench for relational data modeling, and Power BI for interactive recruitment funnel visualization.

## ⚙️ Analytical Workflow
* **Data Integration & ETL:** Cleaned and merged raw multi-company recruitment records (`applications_master`, `interviews`, `offers`), resolving schema inconsistencies using Python (Pandas).
* **Relational Database Modeling:** Stored structured candidate pipelines in MySQL Workbench to query channel sourcing volumes, stage conversion rates, and time-to-hire distributions.
* **DAX & Funnel Metrics:** Built dynamic DAX measures in Power BI to evaluate Application Volume, Offer Conversion Rate, Yield Ratio, and Average Resume Match Score.
* **Interactive Dashboard Construction:** Designed executive visuals displaying stage-wise drop-offs, sourcing channel distributions (LinkedIn vs. Naukri), and job role requirements.

## 🛠️ Tools & Technologies Used
* **Dataset:** Multi-Company HR Analytics & Recruitment Funnel Dataset
* **Programming Language:** Python (Pandas, NumPy, Matplotlib)
* **Database & Querying:** MySQL Workbench (`recruitment_queries.sql`)
* **Data Visualization:** Power BI (`Talent Acquisition Dashboard`)
* **Development Environment:** Jupyter Notebook

## 📁 Repository & Folder Structure
```text
Talent_Acquisition_Analytics/
├── data/
│   ├── raw/
│   │   └── Multi-Company HR Analytics/
│   └── cleaned/
│       ├── applications_master.csv
│       ├── interviews.csv
│       └── offers.csv
├── sql/
│   └── recruitment_queries.sql
├── Talent_Acquisition_Analytics.ipynb
├── Talent Acquisition Dashboard.pbix
├── Talent Acquisition Dashboard.png
└── README.md
```
## 📊 Dashboard Preview
## 🔗 Interactive Power BI Dashboard File
* **Download Full Power BI (.pbix) File:** [Click Here to Download via Google Drive](https://drive.google.com/file/d/1A-EyCizwYcjZO4oy8oeABUqrCMgcm5th/view?usp=sharing)

## 📈 Impact & Core Results
Applications Analyzed: Processed and evaluated 378.4K total candidate applications.

Offers Generated: Tracked pipeline conversion leading to 41K total job offers generated across business units.

Candidate Quality Metric: Maintained an average resume score of 50.03 across applicant pools.

Top Sourcing Channels: Identified LinkedIn and Naukri as the primary high-volume recruitment channels driving qualified candidates.

## 🏁 Final Conclusion
Reallocating recruitment ad budgets toward top-performing channels like LinkedIn and Naukri, while automating early-stage resume screening, will significantly reduce time-to-hire and improve candidate conversion yield across all hiring stages.
