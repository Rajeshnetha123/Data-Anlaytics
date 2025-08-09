# Data-Analytics
A curated collection of my data analytics projects, code snippets, and learning resources — from Python and SQL to Power BI and beyond


🏥 Hospital Data Analysis & Reporting

An end-to-end analysis of hospital records to uncover trends in patient demographics, medical departments, diagnoses, and billing.
This project uses Python, Pandas, and Excel to process and visualize healthcare data for actionable insights.

 📌 Overview

This project analyzes hospital patient records to:

* Identify patterns in diagnoses and departments.
* Explore billing trends and missing data.
* Examine demographics (age, gender distribution).
* Provide a data-driven report for better decision-making.

 🛠 Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter Notebook
* Excel / CSV

 📂 Project Structure

```
.
├── HospitalRecords.ipynb           # Main analysis notebook
├── Hospital_Records.csv            # Primary dataset
├── Hospital_Data_Report_Final.xlsx # Processed report (Excel)
└── README.md                        # Project documentation
```


 📈 Key Steps in Analysis

1. Data Loading — Imported CSV data into Pandas for manipulation.
2. Data Cleaning — Handled missing values in `Age`, `Gender`, `Department`, and `Bill_Amount`.
3. Exploratory Data Analysis (EDA) —

   * Patient distribution by department and gender.
   * Billing trends over time.
   * Diagnosis frequency.
4. Report Generation — Final cleaned and summarized dataset exported to Excel.


 📊 Sample Insights

* Neurology and Orthopedics departments have the highest patient visits.
* Missing demographic data could impact targeted healthcare decisions.
* Billing gaps identified — certain patients have `NaN` in `Bill_Amount`.
* Cancer and Skin Rash are among the most frequent diagnoses.


 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

3. Open `HospitalRecords.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells to reproduce the analysis and generate the Excel report.


 📌 Dataset

* Hospital\_Records.csv → Raw patient records.
* Hospital\_Data\_Report\_Final.xlsx → Final cleaned and processed data report.


 📬 Contact

💼 Name: Rajesh Nagula

📧 Email: rajeshnetha1234@gmail.com

🔗 LinkedIn: www.linkedin.com/in/nagula-rajesh

🔗 GitHub: https://github.com/Rajeshnetha123
