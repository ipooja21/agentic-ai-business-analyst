<div align="center">

# 🤖 Agentic AI Business Analyst

### An Autonomous Multi-Agent System for Business Intelligence

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com)

> *Upload your data — 6 AI Agents will clean, analyze, predict and generate reports automatically*

**🔒 Source code is private | Demo available on request**

</div>

---

## 📌 Overview

**Agentic AI Business Analyst** replicates the complete workflow of a real business analyst using **6 autonomous intelligent agents**. It takes raw, messy business data as input and automatically performs:

- ✅ Data cleaning & preprocessing
- ✅ Statistical analysis & visualization
- ✅ Machine learning prediction
- ✅ Anomaly detection
- ✅ Business insight generation
- ✅ Automated PDF & Excel report generation

> **Goal:** Eliminate manual effort and provide instant, data-driven business insights with zero human intervention.

---

## 🖥️ Demo Screenshots

### 📊 Upload & Raw Data Preview
> Upload any CSV/Excel file — the system instantly analyzes structure, missing values, and duplicates

![Upload Screen](./screenshots/upload.png)

---

### ⚡ 6-Agent Pipeline Execution
> All 6 agents run autonomously and report completion status in real-time

![Agent Pipeline](./screenshots/pipeline.png)

---

### 📈 KPI Dashboard
> Auto-generated KPIs: Revenue, Cost, Profit, Customers, Discount

![KPI Dashboard](./screenshots/kpi.png)

---

### 📉 Interactive Charts
> Region-wise revenue, scatter plots, product distribution — all interactive

![Charts](./screenshots/charts.png)

---

### 🔥 Correlation Heatmap
> Feature correlation matrix showing relationships between all business variables

![Heatmap](./screenshots/heatmap.png)

---

### 🤖 ML Prediction Model (Agent 6)
> Gradient Boosting vs Random Forest comparison with Feature Importance & Actual vs Predicted graph

![ML Model](./screenshots/ml_model.png)

---

### 🚨 Anomaly Detection (Agent 5)
> Isolation Forest detects anomalous records — flagged with visual scatter plot

![Anomaly Detection](./screenshots/anomaly.png)

---

### 📄 Auto-Generated PDF Report
> Professional business report generated automatically with all insights & statistics

![PDF Report](./screenshots/report.png)

---

## 🏗️ System Architecture — Agent Workflow

```
📂 Raw Data (CSV/Excel Upload)
         │
         ▼
┌─────────────────────┐
│  Agent 1: Data      │  ── Removes bad rows, handles missing values,
│  Cleaner 🧹         │      fixes duplicates → Clean Dataset
└─────────────────────┘
         │
         ▼
┌─────────────────────┐
│  Agent 2: Analyzer  │  ── Statistical analysis: Mean, Max, Min,
│  📊                 │      Std Dev, Correlation Matrix
└─────────────────────┘
         │
         ▼
┌─────────────────────┐
│  Agent 3: Insight   │  ── Generates data-driven business insights
│  Engine 💡          │      from ML model & statistics
└─────────────────────┘
         │
         ▼
┌─────────────────────┐
│  Agent 4: Report    │  ── Auto-generates PDF & Excel reports
│  Generator 📄       │      with all findings
└─────────────────────┘
         │
         ▼
┌─────────────────────┐
│  Agent 5: Anomaly   │  ── Isolation Forest detects outliers &
│  Detector 🚨        │      anomalous business records
└─────────────────────┘
         │
         ▼
┌─────────────────────┐
│  Agent 6: ML        │  ── Random Forest + Gradient Boosting
│  Predictor 🤖       │      predicts target column with accuracy score
└─────────────────────┘
         │
         ▼
📊 KPI Dashboard + Interactive Charts + Downloadable Reports
```

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🤖 **6-Agent Pipeline** | Fully autonomous multi-agent system |
| 🧹 **Smart Data Cleaning** | Removes bad rows, handles missing & duplicate values |
| 📊 **Interactive Dashboard** | Real-time KPI cards with Plotly visualizations |
| 🔥 **Correlation Heatmap** | Feature relationship matrix for all variables |
| 🤖 **ML Prediction** | Random Forest vs Gradient Boosting comparison |
| 🚨 **Anomaly Detection** | Isolation Forest flags suspicious records |
| 💡 **Auto Insights** | Data-driven business insights generated automatically |
| 📄 **PDF Reports** | Professional reports via ReportLab |
| 📊 **Excel Export** | Full data + anomaly labels via OpenPyXL |
| ❓ **Ask Your Data** | Natural language Q&A on your dataset |

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Language** | Python 3.x |
| **Frontend** | Streamlit |
| **ML Models** | Scikit-learn (Random Forest, Gradient Boosting, Isolation Forest) |
| **Visualization** | Plotly |
| **PDF Reports** | ReportLab |
| **Excel Export** | OpenPyXL |
| **Data Processing** | Pandas, NumPy |
| **Model Saving** | Joblib |

---

## 📊 ML Model Results (Sample Run)

| Model | Accuracy (R²%) | MAE |
|-------|---------------|-----|
| Random Forest | 66.49% | 2531.83 |
| **Gradient Boosting** | **68.93%** ✅ | **2433.47** |

**Top Features Impacting Revenue:**
1. 🥇 Cost (highest impact)
2. 🥈 Discount
3. 🥉 Marketing Spend

---

## 🚨 Anomaly Detection Results (Sample)

- **Total Records:** 64
- **Normal Records:** 60
- **Anomalies Found:** 4 (6.2% of data)
- **Method:** Isolation Forest

---

## ⚙️ How It Works

```
1. 📂 User uploads CSV/Excel dataset
2. 🧹 Agent 1 cleans data (removes bad rows, fixes missing values)
3. 📊 Agent 2 runs statistical analysis
4. 🤖 Agent 6 trains ML models & predicts target column
5. 💡 Agent 3 generates business insights from ML results
6. 🚨 Agent 5 detects anomalies using Isolation Forest
7. 📄 Agent 4 generates PDF + Excel reports
8. 📊 Dashboard renders KPIs, charts, heatmap & insights
```

---

## 🎯 Challenges Solved

- **Noisy/Dirty Data** → Smart preprocessing pipeline
- **Agent Coordination** → Sequential pipeline with status tracking
- **Automated Reporting** → Zero-manual PDF & Excel generation
- **Model Selection** → Automatic best model comparison

---

## 📬 Contact

> 🔒 Source code is private. Demo available on request.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pooja_Kumari-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/pooja-kumari-734b71284)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail)](mailto:poojakumari21official@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-00C7B7?style=for-the-badge)](https://pooja-kumari-portfolio.netlify.app/)

---

<div align="center">

*Built with ❤️ by Pooja Kumari | B.Tech CSE | UEM Jaipur*

</div>
