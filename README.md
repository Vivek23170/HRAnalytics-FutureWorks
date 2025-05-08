# HRAnalytics-FutureWorks
<div align="center">
    <img src="https://github.com/user-attachments/assets/cf5325e0-87ee-4b4a-b04f-ab2b5bdb7132" width="100%" height="auto">
</div>

## Introduction
In the rapidly evolving labor market, decision-makers from various sectors—including HR professionals, career advisors, and business owners—face significant challenges in making informed decisions due to the lack of consolidated, actionable insights from disparate employment data. The EmployAnalytics Application is envisioned as a sophisticated tool designed to streamline the process of gathering, analyzing, and visualizing employment-related data to support strategic decision-making across multiple domains.

## Project Overview
EmployAnalytics-FutureWorks is a strategic initiative aimed at leveraging advanced data analytics to enhance the capabilities of FutureWorks Solutions, a consultancy firm specializing in recruitment and workforce management. This project utilizes the IBM HR Analytics Employee Attrition & Performance dataset to build a robust Power BI dashboard that facilitates deep insights into employee attrition and broader workforce dynamics.

## Goals 🎯
- **Improve Attrition Understanding:** Develop a deep understanding of factors driving employee attrition.
- **Enhance Decision Making:** Provide actionable insights to HR professionals and recruiters to optimize hiring and retention strategies.
- **Interactive Reporting:** Create a dynamic and interactive reporting environment that allows stakeholders to explore data and derive personalized insights.

---

## Steps Involved in Developing the Project
- [Identifying the Right Dataset](#identifying-the-right-dataset)
- [Making Strategies](#making-strategies)
- [Data Loading](#data-loading)
- [Data Transformation](#data-transformation)
- [Data Modeling](#data-modeling)
- [Designing Report Structure](#designing-report-structure)
- [Identifying Measures to Calculate](#identifying-measures-to-calculate)
- [Implementing the Dashboard](#implementing-the-dashboard)
- [Adding Required Visuals](#adding-required-visuals)
- [Adding Dynamic Nature](#adding-dynamic-nature)

---

## Identifying the Right Dataset
**Source:** The dataset was sourced from Kaggle, featuring detailed employee data ideal for analyzing workforce trends and patterns.  
[Dataset source](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## Making Strategies
**Approach:** Developed a comprehensive strategy to address the specific needs of workforce planning and management. The focus was placed on identifying and analyzing key metrics that significantly impact employee attrition and satisfaction.

- **Metric Identification:** Pinpointed the most influential factors contributing to employee turnover and job satisfaction.
- **Data-driven Insights:** Leveraged trends such as department-level attrition or satisfaction discrepancies to inform hiring strategy.
- **Predictive Planning:** Prepared for future analysis extensions to guide long-term HR and workforce management decisions.

---

## Data Loading
**Process:** 
- Downloaded the dataset from Kaggle and reviewed locally.
- Uploaded to Power BI using 'Get Data > Excel' for structured ETL workflow.

---

## Data Transformation
**Tools Used:** Power Query in Power BI  
**Key Steps Performed:**
- Cleaned and normalized fields.
- Handled missing values and incorrect types.
- Created new columns (e.g., `Career Readiness Index`, `Estimated Revenue`).
- Transformed ambiguous job titles into standardized categories.

**Challenge:** Some fields were inconsistently structured. We used text normalization and DAX for conditional logic to fix that.  
**Outcome:** A clean, structured dataset ready for visualization.

---

## Data Modeling
**Method:** Created relationships across relevant tables using common keys like `EmployeeID`, enabling cross-filtering across dashboards.  
**Result:** A normalized data model that supports consistent, interactive analytics.

---

## Designing Report Structure
**Implementation:** The dashboard was structured across **six distinct pages**, each with a focused theme and visual clarity to guide users—from consultants to job seekers.

### Pages Overview:

- **Welcome Page:** Introduction to project scope and navigation guidance.  
  ![image](https://github.com/user-attachments/assets/826cb67d-5d40-4624-835a-9b33c57e52bb)


- **Job Opportunities Page:** Highlights in-demand roles, relevant academic backgrounds, required skills, and average salaries.  
  ![image](https://github.com/user-attachments/assets/35913db2-cd0d-4282-a10d-4dce8640cca5)


- **Workplace Insights Page:** Explores satisfaction, work-life balance, and role stability scores across departments and age groups.  
  ![image](https://github.com/user-attachments/assets/22ef33b5-7fa8-4784-a14a-7425470fcc2c)


- **Salary Insights Page:** Evaluates salary and revenue trends by role and education background, along with a Career Readiness gauge.  
 ![image](https://github.com/user-attachments/assets/4c191cf6-731e-4a0d-8f9e-679c16039d8b)


- **Attrition Trends Page:** Presents detailed attrition analytics across gender, job role, and department, helping identify risk zones.  
 ![image](https://github.com/user-attachments/assets/137b6b58-a81d-4432-ac6c-75bafa064bdb)


- **Skill Insights Page:** Displays in-demand soft and technical skills mapped to job roles, with compensation comparisons across HR, R&D, and Sales.  
![image](https://github.com/user-attachments/assets/5a28d09e-c098-4675-8cf6-1dc922ff93aa)


---

### Navigation & Filters:
Each page includes a **custom sidebar navigation bar**, along with slicers (e.g., department, job level, age group, education field) that enhance personalization and interactivity.

**Outcome:** Users can seamlessly move between high-level overviews and granular breakdowns.

---

## Identifying Measures to Calculate
**Key Metrics Implemented:**
- Attrition Rate by Role, Department, Gender
- Work-Life Balance by Age
- Estimated Annual Revenue per Role
- Career Readiness Index (custom metric)
- Job Stability Score

---

## Implementing the Dashboard
**Platform:** Power BI Desktop  
**Features:**
- Page-level tooltips
- Conditional formatting
- KPI cards, matrix visuals, dynamic DAX measures

---

## Adding Required Visuals
**Charts Used:**
- Bar, line, pie, donut, stacked column, matrix, and gauge charts  
**Contextual Storytelling:** Every visual is paired with a strategic title and tooltip to guide interpretation.

---

## Adding Dynamic Nature
**Interactive Elements:**
- Slicers for Age, Department, Education, Job Role, etc.
- Cross-filtering via visual interactions
- Navigation buttons and bookmarks for smooth page transitions

---

## File Deliverables
🔗 [Power BI Dashboard File (.pbix)](https://github.com/Vivek23170/Team9-healthcare-workforce-visuals/blob/main/Team9_MRP_DAshboard.pbix)

