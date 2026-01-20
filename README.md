# Human Resources Analytics & Advanced BI Project

## 📌 Project Overview
This project presents an **advanced Business Intelligence solution for Human Resources analytics**, combining a well-structured **data model**, **DAX-based calculations**, and interactive **Power BI dashboards**.

The focus of the project is not only visualization, but also **analytical modeling**, enabling HR stakeholders to evaluate workforce composition, performance, and employment trends using reliable, reusable metrics.

---

## 🎯 Project Objectives
- Design an analytical data model optimized for HR reporting.
- Develop **advanced DAX measures** to calculate key workforce KPIs.
- Enable dynamic and interactive analysis through Power BI dashboards.
- Apply BI best practices in modeling, calculations, and visualization.
- Support data-driven HR decision-making.

---

## 🏗️ Architecture & Analytical Workflow
The solution follows a structured BI workflow:

1. **Data Preparation**
   - Data cleaning and transformation using Power Query.
   - Standardization of fields related to employees, roles, departments, and dates.

2. **Data Modeling**
   - Star-schema-inspired analytical model.
   - Proper use of relationships and cardinality.
   - Separation of fact-like tables (employment events) and dimensions (employee, department, role, date).

3. **Analytical Layer (DAX)**
   - Centralized KPI logic using DAX measures.
   - Reusable calculations to ensure metric consistency across reports.

4. **Visualization Layer**
   - Interactive Power BI dashboards built on top of the semantic model.
   - Slicers and filters enable multi-dimensional analysis.

---

## 🧱 Data Model
The analytical model is designed to support flexible HR analysis and includes:

### Core Entities
- **Employee**
- **Department**
- **Job Role**
- **Date**
- **Performance Metrics**

The model supports time-based analysis and cross-filtering across HR dimensions.

---

## 📐 Advanced DAX & Metrics
The project makes extensive use of **DAX measures** to calculate HR KPIs, such as:

- **Headcount**
- **Average Tenure**
- **Employee Attrition Rate**
- **Hiring and Termination Metrics**
- **Performance Distribution**

DAX techniques applied include:
- CALCULATE with context transition
- Time intelligence patterns
- Conditional logic and iterators
- Reusable base measures for scalability

All calculations are designed to be **dynamic and filter-aware**.

---

## 📊 Data Visualization with Power BI
Power BI dashboards provide insights such as:

- Workforce distribution by department, role, and gender
- Hiring and attrition trends over time
- Employee tenure analysis
- Performance comparisons across organizational units

The dashboards are designed following best practices in data visualization and UX.
