# 🧠 Employee Satisfactory Data Analysis Using Python

This project is a data-driven analysis of employee satisfaction across various departments. The main objective is to understand how many employees are satisfied or dissatisfied and how satisfaction levels vary across departments. The results are visualized using charts, including a **donut chart**, for better clarity and interpretation.

---

## 📌 Project Overview

The dataset used (`Employee.csv`) contains records of employees with their department and satisfaction status. The Jupyter Notebook (`employee.ipynb`) processes this dataset to generate insights and visual representations.

### 🔍 Key Insights:

- Total number of satisfied vs. unsatisfied employees  
- Percentage-based distribution using pie and donut charts  
- Department-wise average satisfaction levels  

This analysis helps HR departments and management visualize employee morale and satisfaction trends to make informed decisions.

---

## ⚙️ Tools & Libraries Used

| Tool         | Purpose                                |
|--------------|----------------------------------------|
| Python       | Core programming language              |
| Pandas       | Data loading, cleaning, and grouping   |
| Matplotlib   | Data visualization                     |
| Jupyter Notebook | Interactive analysis & presentation |

---

## 🧱 Project Architecture

The architecture for this analysis can be represented in simple logical stages:

```text
            ┌────────────────────┐
            │  Employee.csv      │
            │ (Employee Dataset) │
            └────────┬───────────┘
                     │
                     ▼
         ┌────────────────────────┐
         │ Data Preprocessing     │
         │ - Load CSV with pandas │
         │ - Check for nulls      │
         │ - Clean data           │
         └────────┬───────────────┘
                  │
                  ▼
        ┌────────────────────────────┐
        │ Data Analysis              │
        │ - Group by Dept            │
        │ - Calculate satisfaction % │
        └────────┬───────────────────┘
                 │
                 ▼
     ┌────────────────────────────────┐
     │ Visualization                  │
     │ - Pie chart & Donut chart      │
     │ - Satisfaction by department   │
     └────────────────────────────────┘






📁 Files in the Project
employee.ipynb – Jupyter notebook with full analysis

Employee.csv – Dataset used in the project

README.md – Project overview and documentation

.gitignore – Git ignore settings (optional)

requirements.txt – Python dependencies (optional)
