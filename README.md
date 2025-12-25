# 📊 KPI Anomaly Detection Automation

This project focuses on monitoring daily business KPIs and identifying unusual spikes or drops using statistical anomaly detection. 
The goal is to generate a clean, business-ready output that can be used in dashboards or alerting workflows.

---

## 📌 What This Project Covers

- Loaded and prepared the KPI dataset in Jupyter Notebook (Python)
- Cleaned and formatted date and KPI fields
- Applied statistical logic to flag anomalies
- Generated anomaly indicators for days with unusual KPI behaviour
- Created a simple KPI trend chart for validation
- Exported a final CSV file containing the anomaly results

**Tools used:** Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

---

## 📊 Key Insights

- The dataset includes multiple daily KPI records, out of which **7 days were flagged as anomalies**
- Anomalies align with unusual fluctuations in KPI values and may indicate operational or business-level deviations
- These anomaly points help stakeholders investigate potential issues earlier instead of reacting late

---

## 📈 Visual Highlights

- **Revenue trend chart with highlighted anomaly points**  
  Used to visually validate whether the detection logic matches real KPI behaviour

The chart is only for validation — the final deliverable remains the CSV output.

---

## 📂 Folder Structure

KPI-Anomaly-Detection-Automation/  
│── data/  
│   ├── daily.csv  
│   └── kpi_anomaly_output.csv  
│── notebooks/  
│   └── kpi_anomaly_detection.ipynb  
└── README.md  

---

## 🗃 Output File

The project generates:
kpi_anomaly_output.csv


This file contains:
- Date  
- KPI values  
- Anomaly flag (0 = normal, 1 = anomaly)

Designed for monitoring dashboards and automation workflows.

---

## 🚀 How to Run This Project

1. Open `kpi_anomaly_detection.ipynb` in Jupyter Notebook  
2. Run all cells in sequence  
3. Review the anomaly validation chart  
4. The final output file (`kpi_anomaly_output.csv`) will be generated in the project directory

---

🙋‍♂️ **Author**  
Ayush Saini  
Aspiring Data Analyst  
📧 ayushsaini8535@gmail.com
