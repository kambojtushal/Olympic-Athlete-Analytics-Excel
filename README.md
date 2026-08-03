<div align="center">

# 🏅 Olympic Athlete Analytics Dashboard

### Interactive Athlete Performance Analysis Built Entirely in Microsoft Excel

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

*Turning 2,600+ rows of raw Olympic athlete data into a clean, interactive, decision-ready dashboard.*

[Overview](#-project-overview) •
[Dataset](#-dataset-information) •
[Dashboard](#-dashboard-highlights) •
[Features](#-excel-features-used) •
[Preview](#-dashboard-preview) •
[Structure](#-project-structure) •
[How to Use](#-how-to-use) •
[Author](#-author)

</div>

---

## 📌 Project Overview

This project is an interactive **Olympic Athlete Analytics Dashboard** built entirely in **Microsoft Excel**. It transforms raw athlete records into meaningful insights using **Pivot Tables**, **Pivot Charts**, calculated metrics, and dashboard-style visualizations — no external BI tool required.

The dashboard lets users explore athlete performance characteristics such as **age**, **BMI**, **height**, **weight**, **sport**, and **nationality** through fully interactive slicers and charts, making it easy to spot patterns across different sports and demographics.

---

## 📊 Dataset Information

| Detail | Value |
|---|---|
| **Records** | 2,606 athletes |
| **Fields** | 11 (+ Sr. No. index) |
| **Format** | Excel Table (`DATA` sheet) |
| **Tool Used** | Microsoft Excel |

### Dataset Fields

| Column | Description |
|---|---|
| Athlete Name | Full name of the athlete |
| Sport | Sport/discipline the athlete competes in |
| Nationality | Athlete's country |
| Age | Athlete's age |
| Weight (kg) | Body weight |
| Height (cm) | Body height |
| BMI | Calculated Body Mass Index |
| Weight Level | Categorized weight bucket (e.g., Average, Above Average) |
| Height Level | Categorized height bucket |
| Age Group | Categorized age bucket (e.g., Young Adults) |

---

## 📈 Dashboard Highlights

The dashboard provides interactive analysis across the following views:

- 🏆 **Athlete Distribution Across Sports**
- 🌍 **Sport-wise Nationality Breakdown**
- 👥 **Age Group Distribution**
- ⚖️ **Weight Category Analysis**
- 📏 **Height Level Analysis**
- 💪 **BMI Distribution**
- 📊 **Average BMI Across Sports**
- 📉 **BMI vs. Average Height & Weight**
- 📅 **Age-wise Weight Analysis**
- 📐 **Age-wise Height Analysis**

---

## 🛠 Excel Features Used

- Pivot Tables & Pivot Charts
- Slicers for interactive filtering
- Multi-tab Dashboard design
- Calculated fields (BMI, categorization logic)
- Formula-driven data categorization
- Clean, presentation-ready data visualization

---

## 📌 KPI Metrics

The dashboard helps users quickly identify:

- Total Athletes
- Sports Participation Count
- Nationality Distribution
- Average BMI (overall & by sport)
- Height Category Breakdown
- Weight Category Breakdown
- Age Group Breakdown
- BMI Comparison Across Sports

---

## 📂 Project Structure

The workbook is organized into the following sheets:

```
EXCEL_PROJECT.xlsx
│
├── DASHBOARD                        → Main interactive dashboard view
├── Count of Athletes Across Sport    → Pivot: athlete count by sport
├── Count of Athlete Across Age Group → Pivot: athlete count by age group
├── Sport Across Nationality          → Pivot: sport vs. nationality breakdown
│
├── WEIGHT                            → Weight analysis dashboard
├── Weight Across Age                 → Pivot: weight trend by age
├── Count of Athlete Across Weight     → Pivot: athlete count by weight level
│
├── HEIGHT                            → Height analysis dashboard
├── Height Across Height Level         → Pivot: athlete count by height level
├── Height Across Age                 → Pivot: height trend by age
│
├── BMI                                → BMI analysis dashboard
├── BMI Vs AVG Weight & Height         → Pivot: BMI vs. average metrics
├── Avg BMI Across Sport               → Pivot: average BMI by sport
├── Age Across BMI                     → Pivot: BMI trend by age
│
├── ABOUT                              → Project notes / summary
└── DATA                               → Raw dataset (2,606 records)
```

---

## 📷 Dashboard Preview

<img width="802" height="227" alt="Sports & Nationality Dashboard" src="https://github.com/user-attachments/assets/2354e652-479e-463e-a314-ee1f84b2602e" />
<img width="803" height="227" alt="Weight Analysis Dashboard" src="https://github.com/user-attachments/assets/7de2852c-6396-4443-8f1f-b00ea67f7d3f" />
<img width="805" height="228" alt="Height Analysis Dashboard" src="https://github.com/user-attachments/assets/98e67be3-5c67-4161-a822-8ff7e452e97e" />
<img width="803" height="224" alt="BMI Analysis Dashboard" src="https://github.com/user-attachments/assets/acb8a176-2b56-4202-bf94-fb87c61e9424" />
<img width="802" height="228" alt="Overall Athlete Dashboard" src="https://github.com/user-attachments/assets/dff1ec5c-73e6-4f01-b209-9899e8784b3b" />

---

## 🚀 How to Use

1. **Download** the `EXCEL_PROJECT.xlsx` file from this repository.
2. Open it in **Microsoft Excel** (2016 or later recommended for full Slicer/Pivot support).
3. Go to the **DASHBOARD**, **WEIGHT**, **HEIGHT**, or **BMI** sheets to explore each view.
4. Use the **Slicers** to filter by Sport, Nationality, Age Group, Weight Level, or Height Level — all connected pivot charts update instantly.
5. Explore the **DATA** sheet for the full raw dataset behind every chart.

> 💡 If charts/slicers don't render correctly, ensure macros/content are enabled and that you're using a desktop version of Excel rather than a browser preview.

---

## 🚀 Learning Outcomes

Through this project, hands-on experience was gained in:

- Data Cleaning & Preparation
- Dashboard Development
- Business Intelligence Fundamentals
- KPI Reporting
- Interactive Excel Dashboard Design
- Data Visualization Best Practices
- Analytical Thinking

---

## 🎯 Future Improvements

- [ ] Power BI version of the same dashboard
- [ ] Dynamic KPI Cards
- [ ] Power Query integration for automated data refresh
- [ ] Advanced Excel automation (VBA/macros)
- [ ] Predictive analytics (e.g., forecasting BMI/performance trends)

---

## 🧑‍💻 Author

**Tushal Kamboj**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/kambojtushal)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tushal-kamboj-533b05319)

---

<div align="center">

### ⭐ If you found this project helpful, consider giving it a Star!

</div>
