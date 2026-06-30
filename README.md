# 🏥 Hospital Management Dashboard | Power BI

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/SQL-Data%20Model-blue?style=for-the-badge&logo=mysql">
  <img src="https://img.shields.io/badge/Healthcare-Analytics-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 📌 Project Overview

This project is an interactive **Hospital Management Dashboard** built using **Microsoft Power BI**.

The dashboard analyzes hospital operations by integrating **5 relational tables** including patients, doctors, appointments, treatments, and billing. It provides meaningful insights into hospital performance, appointment status, treatment costs, and payment analysis.

---

# 📂 Dataset

The project consists of **5 related tables**.

| Table | Description |
|--------|-------------|
| 👨‍⚕️ Doctors | Doctor information and specialization |
| 🧑‍🤝‍🧑 Patients | Patient demographic details |
| 📅 Appointments | Appointment scheduling and status |
| 💊 Treatments | Treatment information and costs |
| 💰 Billing | Billing amount and payment status |

---

# 🔗 Data Model

Relationships used in Power BI

```text
Patients
   │
   ├────────► Appointments ◄──────── Doctors
   │                  │
   │                  ▼
   │             Treatments
   │                  │
   ▼                  ▼
              Billing
```

Primary Relationships

- PatientID → Appointments
- DoctorID → Appointments
- AppointmentID → Treatments
- TreatmentID → Billing
- PatientID → Billing

---

# 📊 Dashboard Features

✅ Executive Overview

✅ Patient Analytics

✅ Doctor Performance

✅ Appointment Analysis

✅ Treatment Analysis

✅ Billing & Revenue Analysis

✅ Interactive Filters & Slicers

✅ KPI Cards

✅ Dynamic Charts

---

# 📈 Key KPIs

- 👨 Total Patients
- 👨‍⚕️ Total Doctors
- 📅 Total Appointments
- 💊 Total Treatments
- 💰 Total Revenue
- ✅ Paid Bills
- ⏳ Pending Bills
- ❌ Cancelled Appointments

---

# 📉 Visualizations

- KPI Cards
- Clustered Bar Chart
- Line Chart
- Pie Chart
- Donut Chart
- Stacked Column Chart
- Matrix Table
- Tree Map
- Slicers
- Cards

---

# 🛠️ Tools Used

- 📊 Microsoft Power BI
- 🧹 Power Query
- 🧮 DAX
- 📄 CSV Dataset

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Relationship Creation
- Star Schema
- DAX Measures
- Power Query
- Dashboard Design
- Healthcare Analytics
- Business Intelligence

---

# 📷 Dashboard Preview

## Executive Dashboard

<img width="1920" height="1080" alt="Dashboard1" src="https://github.com/user-attachments/assets/a998470c-b139-41af-ae5e-8324c97fa005" />


```
images/dashboard1.png
```

---

## Billing Dashboard

<img width="1920" height="1080" alt="Fd" src="https://github.com/user-attachments/assets/73cdb0e4-8dbe-4ecb-a22d-3b892830b773" />


```
images/dashboard2.png
```

---

## Appointment Dashboard

<img width="1920" height="1080" alt="Do Dp" src="https://github.com/user-attachments/assets/76bd8ba2-ae8c-412e-a61f-a701af94c50c" />


```
images/dashboard3.png
```

---

# 📁 Repository Structure

```
Hospital-Management-Dashboard
│
├── Dataset
│   ├── appointments.csv
│   ├── billing.csv
│   ├── doctors.csv
│   ├── patients.csv
│   └── treatments.csv
│
├── Dashboard.pbix
│
├── Images
│
└── README.md
```

---

# ⭐ Highlights

- ✔️ End-to-End Power BI Project
- ✔️ Healthcare Analytics
- ✔️ 5 Related Tables
- ✔️ Interactive Dashboard
- ✔️ Professional Data Model
- ✔️ Business Intelligence Reporting

---

# 👨‍💻 Author

**Krishna**

If you like this project, don't forget to ⭐ the repository!
