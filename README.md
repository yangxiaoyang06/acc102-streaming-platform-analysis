# Financial Performance Analysis of Netflix, Bilibili, and iQIYI

**Track:** Track 2 – GitHub Data Analysis Project  
**Module:** ACC102 Mini Assignment  
**Notebook file:** `final_notebook_track2_revised.ipynb`

## Product Link / Demo
- **GitHub repository link:** *add your repo link here before submission*
- **1–3 minute demo video link:** *add your demo video link here before submission*

The course briefing specifically notes that Track 2 should include a README and a **1–3 minute demo video**, and that the product link should be easy for the marker to find. fileciteturn7file2L17-L20 fileciteturn7file2L37-L40

## 1. Problem & User
This project compares the financial performance of **Netflix**, **Bilibili**, and **iQIYI**. The analytical problem is to examine how differences in business model affect **revenue scale, profitability, and the relationship between user growth and revenue**.

The intended user is a **non-technical business audience**, especially students, beginner investors, and readers who want a clear comparison of streaming-platform performance without reading full annual reports.

This focus matches the assignment requirement to define a **clear analytical problem** and a **clear target user or audience**. fileciteturn7file1L18-L20

## 2. Data
The dataset is based mainly on **official investor-relations disclosures**, with one supporting market-data source used to cross-check part of the Netflix revenue series.

### Sources and access dates
- **Netflix Investor Relations** – annual reports and investor materials. Accessed **22 April 2026**
- **Bilibili Investor Relations** – financial information and annual disclosures. Accessed **22 April 2026**
- **iQIYI Investor Relations** – annual reports and financial disclosures. Accessed **22 April 2026**
- **Macrotrends** – supplementary Netflix revenue series. Accessed **22 April 2026**

### Files used
- `data/netflix_financials.csv`
- `data/bilibili_financials.csv`
- `data/iqiyi_financials.csv`

### Key fields
- `Year`
- `Revenue`
- `NetIncome`
- `Subscribers` or `MAU`

The assignment brief says the notebook or reflection should clearly state the **data source** and the **date accessed or collected**. fileciteturn7file1L21-L26

## 3. Methods
The notebook uses Python for a coherent analytical workflow from **data input to final output**. The main steps are:

1. Load annual financial datasets for the three firms
2. Standardise monetary values into **million USD**
3. Standardise user metrics into **million users**
4. Calculate additional indicators such as revenue growth and profit margin
5. Build summary tables and comparison charts
6. Interpret findings in relation to each company’s business model

### Comparability decisions
- Revenue and net income are compared in a common unit
- Netflix and iQIYI are interpreted mainly through subscriber-based logic
- Bilibili is interpreted using broader platform logic because its model is not purely subscription-based and MAU is more consistently available than paid subscribers

This follows the notebook requirement that the work should show **problem definition, data loading, cleaning or preparation, analysis, and outputs**, and that the workflow should be readable with markdown and clear structure. fileciteturn7file1L33-L36

## 4. Key Findings
- **Netflix leads in both scale and profitability.** It has the largest revenue base and the most consistent positive earnings.
- **Bilibili shows strong growth but weak profitability.** Growth in users and revenue does not automatically produce earnings.
- **iQIYI is a middle case.** It remains weaker than Netflix overall, but its profitability improves in later years.
- **User growth matters, but monetisation design matters more.** A stronger user base only translates into better financial outcomes when the platform converts users into revenue efficiently.

## 5. How to Run
Keep the following files in the same project folder:

- `final_notebook_track2_revised.ipynb`
- `README.md`
- `requirements.txt`
- `data/netflix_financials.csv`
- `data/bilibili_financials.csv`
- `data/iqiyi_financials.csv`

Then:
1. Open the folder in **Jupyter Notebook, JupyterLab, or VS Code**
2. Open `final_notebook_track2_revised.ipynb`
3. Run all cells from top to bottom

If a project depends on additional files, packages, or setup steps, the brief says these must be clearly explained in the notebook or README. fileciteturn7file1L27-L31

## 6. Repository Structure
```text
streaming-platform-analysis/
│
├── final_notebook_track2_revised.ipynb
├── README.md
├── requirements.txt
├── data/
│   ├── netflix_financials.csv
│   ├── bilibili_financials.csv
│   └── iqiyi_financials.csv
└── outputs/
    ├── revenue_comparison.png
    ├── revenue_growth_comparison.png
    ├── net_income_comparison.png
    ├── profit_margin_comparison.png
    ├── user_scale_trend.png
    └── revenue_vs_user_scale_scatter.png
```

This structure also follows the GitHub beginner guidance shown in the course slides, which suggests a repo with a notebook, README, charts/outputs, small data files where suitable, and optional `requirements.txt`. fileciteturn7file2L43-L49

## 7. Limitations & Next Steps
### Limitations
- The three firms are not perfectly identical in business structure
- Bilibili is represented using **MAU**, while Netflix and iQIYI are discussed more through subscriber-based logic
- The analysis is descriptive and comparative rather than predictive
- Some conclusions are affected by differences in company disclosure formats

### Next steps
- Add ARPU or segment revenue analysis
- Include content cost, marketing expenditure, or cash flow measures
- Extend the time period
- Upgrade the project into a Streamlit dashboard for Track 4

## 8. Python Packages
Suggested contents for `requirements.txt`:
```text
pandas
matplotlib
jupyter
ipython
```

## 9. Submission Reminder
For Track 2, your final submission package should include:
- one **repository link**
- one **Python notebook or code files**
- one **README**
- one **1–3 minute demo video**
- one **500–800 word reflection report**

This comes directly from the assignment brief and the student briefing slides. fileciteturn7file1L10-L15 fileciteturn7file2L25-L29
