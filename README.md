# 📊 KPI Anomaly Detection Automation

This project focuses on monitoring daily business KPIs and identifying unusual spikes or drops using statistical anomaly detection.  
The goal is to detect abnormal behaviour early and provide a clean output that can be used for dashboards and alerting workflows.

---

## 📌 What This Project Covers

- Loaded and prepared KPI dataset in Jupyter Notebook (Python)
- Cleaned and formatted date and KPI fields
- Applied statistical logic (z-score based thresholding) to flag anomalies
- Generated anomaly indicators for days with unusual KPI behaviour
- Added a simple line chart to visually validate anomaly points
- Exported a business-ready CSV containing final anomaly results

**Tools used:** Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

---

## 📂 Folder Structure  
KPI-Anomaly-Detection-Automation/    
│── kpi_anomaly_detection.ipynb  
│── kpi_anomaly_output.csv  
│── daily.csv (optional – input dataset)  
│── README.md  

---

## 🧠 Business Insight

Anomalies indicate days where KPI trends deviate significantly from normal patterns.  
These may point to:
- sudden performance drops  
- unexpected revenue spikes  
- operational irregularities  
- potential system or data issues  

Such points help stakeholders **investigate and act early** rather than reacting late.

---

## 📈 Visual Validation

The notebook includes a minimal validation chart:

- Line chart showing KPI trend over time  
- Highlighted points representing anomaly days  

The chart is used only to **verify detection logic** —  
the final deliverable remains the **CSV output** for downstream consumption.

---

## 🗂 Output File

The project generates:

kpi_anomaly_output.csv
This file contains:
- Date  
- KPI values  
- Anomaly flag (0 = normal, 1 = anomaly)  

It is designed for use in dashboards, automation workflows, or monitoring pipelines.

---

## 🚀 How to Run This Project

1. Open `kpi_anomaly_detection.ipynb` in Jupyter Notebook  
2. Run all cells in sequence  
3. Review anomaly chart for validation  
4. The final output file (`kpi_anomaly_output.csv`) will be generated

---

🙋‍♂️ **Author**  
Ayush Saini  
Aspiring Data Analyst  
📧 ayushsaini8535@gmail.com
