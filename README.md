# Medical Reports Analysis & Interactive Dashboard

Analyze hospital medical test data using **PySpark** and visualize insights with **Streamlit**. Compute KPIs like total reports, monthly/quarterly trends, doctor workload, and test type distribution. Build an interactive dashboard for better decision-making.

---

## Features

- **Data Processing:** RDD, SQL, and DataFrame operations  
- **KPIs:** Total reports, unique patients, most active doctor, monthly & quarterly trends  
- **Visualization:** Interactive bar, line, and pie charts with Plotly  
- **Dashboard:** Interactive filters by year and doctor for dynamic analysis  

---

## Dataset

- **File:** `medical_reports.csv`  
- **Columns:** `ReportID`, `PatientID`, `TestType`, `ResultValue`, `Doctor`, `ReportDate`  
- **Derived Columns:** `Month`, `Quarter`, `Year`  

---

## Installation

Install the required libraries using pip:

```bash
pip install pyspark streamlit pandas plotly

HOW TO RUN

1  --  cd path_to_project_folder
2  --  streamlit run 35thproject.py



