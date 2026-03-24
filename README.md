# Healthcare Operations & Patient Insights Dashboard

## Project Overview
This project is a comprehensive healthcare analytics dashboard designed to provide insights into patient visits, billing, and treatment trends. It combines multiple healthcare datasets and leverages Python, SQL, and Power BI to generate actionable KPIs for hospital operations.

Key highlights:
- End-to-end ETL pipeline for cleaning and transforming raw clinical and financial data.
- Analysis of patient wait times, revenue cycle efficiency, and common procedures.
- Identifies inefficiencies, e.g., reducing patient processing time by ~20% (simulated impact).
- Power BI interactive dashboard to visualize trends across patients, encounters, procedures, and payers.

---

## **Technologies Used**
- **Python**: pandas, numpy, matplotlib, seaborn for ETL and data analysis
- **SQL**: For querying and transforming datasets (optional for database setup)
- **Power BI**: Interactive dashboards and KPI visualizations
- **Excel/CSV**: Dataset handling and exports

---

## **Dataset**
This project uses publicly available synthetic healthcare datasets (CMS-style) including:

| Dataset | Description |
|---------|-------------|
| `patients.csv` | Patient demographics (age, gender, race, address, etc.) |
| `encounters.csv` | Patient visits, admission/discharge, billing info |
| `procedures.csv` | Procedures performed during encounters |
| `payers.csv` | Insurance and payer details |
| `organizations.csv` | Hospital/organization information |

---
