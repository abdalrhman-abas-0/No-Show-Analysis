# 📊 Medical Appointment No-Show Analysis

## 🩺 Overview
This project analyzes over **100,000 medical appointments** in Brazil to identify **factors associated with patient no-shows**. By exploring demographic and behavioral patterns, it offers data-driven insights to help healthcare providers reduce missed appointments and improve operational efficiency.

---

## 📁 Dataset Description
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **Total Records**: 110,000+
- **Columns Include**:
  - `PatientId`, `AppointmentID`
  - `Gender`, `ScheduledDay`, `AppointmentDay`, `Age`
  - `Neighborhood`, `Scholarship`, `Hypertension`, `Diabetes`
  - `Alcoholism`, `Handicap`, `SMS_received`, `No-show` (target)

---

## ❓ Analytical Questions
1. Do no-show rates vary by gender?
2. Are medical conditions linked to appointment attendance?
3. How does age affect no-show likelihood?
4. Do SMS reminders reduce no-show rates?

---

## 🔍 Key Insights
- **Gender**: Slightly higher no-show rate observed in females.
- **Health Conditions**: Alcoholism had the strongest link to no-shows.
- **Age**: Highest no-show rate found in the 20–30 age group.
- **SMS Reminders**: No statistically significant impact detected.

---

## 📝 Key Findings
| Factor              | Observation                                      |
|---------------------|--------------------------------------------------|
| Gender              | Females had a no-show rate of 20.3%, males 19.9% |
| Hypertension        | Associated with **hgher** no-show rates          |
| Diabetes            | Slightly reduced no-show likelihood              |
| Alcoholism          | **Increased** no-show risk (~30%)                |
| Age 20–30           | Highest no-show counts                           |
| SMS Reminders       | No significant change in behavior                |

---

## ⚠️ Limitations
- Dataset only spans **May–June 2016**.
- Missing socioeconomic indicators (e.g., income, education).
- No metadata on SMS delivery time or confirmation.
- Binary-encoded fields required careful interpretation.

---

## 🛠 Tools & Technologies
- **Python**: `pandas`, `matplotlib`, `seaborn`
- **Jupyter Notebook**: Exploratory Data Analysis
- **Environment**: Local setup with CSV file

---

## 🚀 Getting Started

### 📁 Repository Structure
```
├── Database_No_show_appointments.ipynb   # Main notebook
├── noshowappointments-kagglev2-may-2016.csv  # Dataset (downloaded)
├── README.md
└── images/
    └── age_distribution.png
    └── Cleaning_the_Data.png
    └── EDA_Q1.png
    └── EDA_Q2.png
```

### 🧪 Setup & Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Download the dataset `noshowappointments-kagglev2-may-2016.csv`
3. Open the notebook:
   ```bash
   jupyter notebook Database_No_show_appointments.ipynb
   ```

---

## 🔮 Next Steps
- 🎯 **Predictive Modeling**: Use logistic regression or decision trees to predict no-shows.
- 💰 **Cost Analysis**: Estimate revenue loss from missed appointments.
- 🗺️ **Geospatial Mapping**: Identify no-show hotspots by neighborhood.

---

## 📎 Access the Analysis
👉 [Jupyter Notebook](Database_No_show_appointments.ipynb)

