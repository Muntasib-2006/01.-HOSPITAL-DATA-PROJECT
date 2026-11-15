# 🏥 Hospital Emergency Admissions & Patient Intelligence Studio
### *Dual-Paradigm Clinical Analytics: Pure Self-Contained HTML vs. Dynamic Star-Schema Streamlit App*

![Data Analytics](https://img.shields.io/badge/Domain-Healthcare_Analytics-0284c7)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B)
![HTML5/CSS3](https://img.shields.io/badge/Dashboard-Pure_HTML5-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🌟 Executive Overview
This repository showcases an end-to-end enterprise data analytics solution for **Hospital Emergency & Clinical Admissions**. It features a **Dual-Architecture Implementation** comparing two foundational philosophies of data delivery:

1. **The HTML Way**: A lightning-fast, zero-dependency, self-contained interactive web dashboard.
2. **The Streamlit Way**: A full-stack analytical web application backed by an enterprise **Kimball Dimensional Model (Star Schema)**, synthetic DAX/NumPy metrics, and live reactive filtering.

---

## 📂 Repository Architecture

```
01. HOSPITAL DATA PROJECT/
├── 📁 THE HTML WAY/
│   ├── index.html                           # Standalone Live Dashboard
│   ├── 2. Hospital_Dashboard.html           # Original Master HTML
│   ├── 1. Cleaned_Hospital_Data.csv         # Cleaned Dataset
│   ├── 3. generate_offline_dashboard.py     # HTML Dashboard Generator Script
│   ├── 5. requirements.txt                  # Python dependencies
│   └── 6. ARCHITECTURAL_BLUEPRINT_HTML_WAY.md
│
├── 📁 THE STREAMLIT WAY/
│   ├── 9. app.py                            # Streamlit Reactive Web App
│   ├── 1. Raw_Hospital_Data.csv             # Unprocessed Raw Records
│   ├── 2. clean_data.py                     # Data Preprocessing & Cleaning Pipeline
│   ├── 3. Cleaned_Hospital_Data.csv         # Standardized Data Feed
│   ├── 4. build_star_schema.py              # Kimball Dimensional ETL Engine
│   ├── 5. Fact_Admissions.csv               # Central Fact Table
│   ├── 5. Dim_Patient.csv                   # Patient Dimension
│   ├── 5. Dim_Department.csv                # Department Dimension
│   ├── 5. Dim_Date.csv                      # Date Dimension
│   ├── 5. Dim_Time.csv                      # Time Dimension
│   ├── 6. dax_numpy_metrics.py              # DAX & NumPy KPI Engine
│   ├── requirements.txt                     # Cloud Deployment Config
│   └── 10. ARCHITECTURAL_BLUEPRINT_STREAMLIT_WAY.md
│
├── HTML_WAY_VS_STREAMLIT_WAY_ARCHITECTURAL_SHOWDOWN.pdf  # Comparative Whitepaper
└── README.md
```

---

## 🚀 How to Run Locally

### Option A: The Streamlit Way (Interactive App)
```bash
# 1. Navigate to the Streamlit directory
cd "THE STREAMLIT WAY"

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the dashboard
streamlit run "9. app.py"
```
The application will launch automatically at `http://localhost:8501`.

### Option B: The HTML Way (Zero Dependencies)
Simply double-click `THE HTML WAY/index.html` or open it in any web browser (Chrome, Edge, Firefox, Safari). **No server, installation, or internet connection required.**

---

## 📊 Analytical Scope & KPIs
* **Emergency Admission Velocity & Volume**: Daily and hourly triage tracking.
* **Length of Stay (LOS)**: Stratified by medical department and acuity level.
* **Financial & Insurance Allocation**: Private vs. public payer distributions.
* **Bed Occupancy & Discharge Forecasting**: Operational resource bottlenecks.

---

## 👤 Author
**Muntasib Junaidi (Miran)**  
*NIT Warangal | Data Analytics & Software Engineering Portfolio*  
*GitHub: [@Miran2006](https://github.com/Miran2006)*
