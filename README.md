# Workforce-Performance-and-Employee-Attrition--IBM-Data

## 📌 Project Overview  
This is an end-to-end workforce analytics and project management initiative focused on understanding and addressing employee attrition.  
The project combines business problem definition, structured data preparation, SQL-based analysis, visualization planning, and project governance practices to deliver actionable insights for workforce planning and retention strategy.

Rather than focusing only on technical queries, the project is designed as a complete analytics and management lifecycle — similar to how real consulting and corporate transformation projects are executed.

---

## 🎯 Business Objective  
To identify key drivers of employee attrition and support data-driven workforce decision-making by analyzing:

- Department and role-level attrition risk  
- Early-tenure vs long-tenure employee exits  
- Impact of overtime and workload  
- Compensation and retention trends  
- Employee satisfaction and work-life balance  
- Workforce engagement and stability  

---

## 🗂️ Dataset  
- Source: IBM HR Attrition Dataset (Kaggle)  
- Records: ~1,470 employees  
- Features: Demographics, job roles, compensation, tenure, satisfaction, and engagement metrics  

**Note:**  
Due to platform limitations on OneCompiler, representative sample rows were used for SQL demonstrations.  
The full dataset was used locally for data preparation, feature engineering, and dashboard development.

---

## 🔄 Project Lifecycle (End-to-End)

### 1. Business Problem Definition  
Defined workforce attrition as a strategic business problem impacting operational continuity, cost, and employee morale.  
Key business questions were framed to align analysis with real management needs.

---

### 2. Data Preparation & Feature Engineering (Excel)  
- Column selection using Keep/Drop review  
- Removal of non-decision-relevant variables  
- Renaming for SQL compatibility  
- Derived fields created:  
  - Attrition Flag  
  - Overtime Flag  
  - Tenure Group  
  - Income Band  
- Data formatting and quality checks  

---

### 3. SQL Analysis (SQLite)  
Business-focused SQL queries were written to answer:

- Overall attrition rate  
- Attrition by department  
- Attrition by job role  
- Attrition by tenure group  
- Overtime vs attrition  
- Compensation vs attrition  
- Satisfaction vs attrition  
- High-risk employee profiles  

SQL was used not just for querying, but for decision-oriented insight generation.

---

### 4. Insight Generation  
Results were interpreted from a management perspective, focusing on:

- Workforce risk areas  
- Operational pressure points  
- Retention strategy implications  
- Engagement and satisfaction drivers  

---

### 5. Visualization & Reporting (Power BI – Planned)  
Interactive dashboards will be created for:

- Executive-level KPIs  
- Department-level attrition risk  
- Role-specific churn patterns  
- Tenure-based attrition trends  
- Overtime exposure analysis  
- Satisfaction & engagement insights  

---

### 6. Project Management Framework (Planned)  
This project is also being structured using Project Management principles, including:

- Project Charter  
- Scope & Objectives  
- Stakeholder Analysis  
- Timeline & Milestones  
- Risk Register  
- Communication Plan  
- Lessons Learned  

This ensures the project mirrors real-world consulting and corporate delivery models.

---

## 🛠️ Tools & Technologies  

| Tool | Purpose |
|------|---------|
| Excel | Data preparation, column selection, feature engineering |
| SQL (SQLite) | Business-driven workforce analysis |
| Power BI | Executive and operational dashboards |
| GitHub | Project documentation & version control |
| Project Management Templates | Charter, risks, scope, timeline |

---

## 📊 Key Business Questions Addressed  

- What is the overall employee attrition rate?  
- Which departments and roles face the highest risk?  
- Is early-tenure attrition more severe?  
- Does overtime increase employee exits?  
- Are compensation levels linked to attrition?  
- Do satisfaction and work-life balance influence retention?  

---

## 📁 Repository Structure  
