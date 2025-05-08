# HRAnalytics-FutureWorks
<div align="center">
    <img src="https://github.com/user-attachments/assets/cf5325e0-87ee-4b4a-b04f-ab2b5bdb7132" width="100%" height="auto">
</div>

## Introduction
In the rapidly evolving labor market, decision-makers from various sectors—including HR professionals, career advisors, and business owners—face significant challenges in making informed decisions due to the lack of consolidated, actionable insights from disparate employment data. The EmployAnalytics Application is envisioned as a sophisticated tool designed to streamline the process of gathering, analyzing, and visualizing employment-related data to support strategic decision-making across multiple domains.
## Project Overview
EmployAnalytics-FutureWorks is a strategic initiative aimed at leveraging advanced data analytics to enhance the capabilities of FutureWorks Solutions, a consultancy firm specializing in recruitment and workforce management. This project utilizes the IBM HR Analytics Employee Attrition & Performance dataset to build a robust Power BI dashboard that facilitates deep insights into employee attrition and broader workforce dynamics
## Goals 🎯
- **Improve Attrition Understanding:** Develop a deep understanding of factors driving employee attrition.
- **Enhance Decision Making:** Provide actionable insights to HR professionals and recruiters to optimize hiring and retention strategies.
- **Interactive Reporting:** Create a dynamic and interactive reporting environment that allows stakeholders to explore data and derive personalized insights.
  
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
  
## Identifying the Right Dataset

**Source:** The dataset was sourced from Kaggle, featuring detailed employee data ideal for analyzing workforce trends and patterns.
[Dataset source](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Making Strategies
**Approach:** Developed a comprehensive strategy to address the specific needs of workforce planning and management. The focus was placed on identifying and analyzing key metrics that significantly impact employee attrition and satisfaction. This strategic approach involved:

  - **Metric Identification:** Pinpointing the most influential factors contributing to employee turnover and job satisfaction based on historical data trends observed in the dataset. This includes variables such as job role, tenure, salary, work environment, and performance ratings.
  - **Data-driven Insights:** Leveraging data to derive insights that inform targeted interventions. For example, understanding which departments have higher attrition rates and what common characteristics are shared among employees who leave the company.
  - **Predictive Analysis:** Planning to use predictive analytics to forecast future trends in employee behavior.
    
This aims to proactively manage potential issues before they impact the workforce adversely.
This strategy ensures that the dashboard and associated analyses not only reflect historical data but also equip HR professionals and decision-makers with actionable intelligence to optimize their workforce strategies effectively.

## Data Loading
**Process:** Instead of directly connecting to an external data source, the dataset was initially downloaded and stored locally. This approach was chosen to allow for preliminary review and any necessary preprocessing steps that are easier to handle offline. After ensuring the data's integrity and format were suitable for analysis, it was uploaded into Power BI for further transformation and visualization.

- **Local Storage:** The data was downloaded from Kaggle and saved to a secure local directory. This step ensured that we had a stable version of the data for initial explorations without continuous reliance on an external source.

- **Upload to Power BI:** Once the local data validation and preliminary checks were completed, the dataset was uploaded into Power BI. This was done by importing the local file through the 'Get Data' feature in Power BI, selecting ‘Excel’ as the source format.

This method not only streamlined the initial data handling process but also provided an opportunity to cleanse and prepare the data comprehensively before it was used for creating the dashboard and conducting detailed analyses.

## Data Transformation
**Process:** Data transformation was meticulously handled using Power Query in Power BI to ensure the dataset was optimized for analysis. This involved several crucial steps:
- **Initial Data Review:** The dataset, sourced from Kaggle and loaded locally, was initially reviewed in Power Query. This review confirmed that the data was largely clean, with minimal inconsistencies or missing values, indicative of the high quality of data management practices at the source.
- **Handling Missing Values:** Minimal missing values in the dataset were determined to be non-impactful on analyses, so they were left unchanged to maintain data authenticity.
- **Data Type Adjustments:** Some fields in the dataset were found to have inappropriate data types for the intended analysis. For instance, numerical codes representing categories (like Education Level) were initially loaded as integers. These were converted to categorical data types to accurately reflect their descriptive nature and facilitate correct analysis handling.
- **Checking for Ambiguity:** The data was scrutinized for any ambiguity, especially in categorical variables where different terms might have been used interchangeably. Standardizing terms and consolidating similar values ensured consistency across the dataset. For example, job titles with minor variations in wording were standardized to a uniform format.
- **Final Data Check:** After all transformations, a final check was conducted to ensure data integrity, consistency, and readiness for the next stages of analysis and visualization in the Power BI environment.

**Outcome:** These thorough data transformation efforts resulted in a clean, consistent, and analytically robust dataset that was then utilized to develop insightful visualizations and predictive models in the subsequent stages of the project.

## Data Modeling
**Process:** Established a relationship between the Job and Employee tables using Employee ID as the primary key. This link ensures a robust data structure that allows for accurate and comprehensive analysis across employee attributes and job-related metrics.
**Outcome:** This relationship facilitates seamless integration of diverse data points, enhancing the dashboard's capability to deliver multidimensional insights and supporting complex queries that span across both datasets.

![image](https://github.com/user-attachments/assets/47ceda3f-b5be-47fe-8533-fed4417a9a30)


## Designing Report Structure
**Implementation:** The reports were meticulously structured across three distinct pages to ensure a logical flow of information, catering to both high-level overviews and detailed analyses:
- **Welcome Page:** Serves as the introduction, providing users with an overview of what to expect in the dashboard and how to navigate through various sections.

  ![image](https://github.com/user-attachments/assets/66d3494f-770a-4733-ae6a-b09980016fa8)


- **Attrition Page:** Focuses on detailed attrition analytics, offering insights into turnover rates, trends, and patterns across different demographics and job roles.

 ![image](https://github.com/user-attachments/assets/b24d56b8-fb57-4050-8ae4-407cff3d9596)

- **Satisfaction Insights Page:** Delivers comprehensive analysis on employee satisfaction, highlighting areas of strength and opportunities for improvement within the organization.

**Navigation:** Each page features navigation bars that allow for easy switching between reports, ensuring a user-friendly experience that facilitates quick access to needed information.

**Outcome:** This structured approach not only enhances the user experience but also ensures that stakeholders can access tailored insights efficiently, from strategic overviews to granular data explorations.

## Identifying Measures to Calculate
**Key Metrics:** Identified critical metrics such as attrition rate, employee satisfaction index, and others that influence strategic decisions.

## Implementing the Dashboard

## Adding Required Visuals
**Visuals Added:** Integrated various charts and graphs that dynamically represent the underlying data, such as bar charts, line graphs, and pie charts.

## Adding Dynamic Nature
**Interactivity:** Incorporated slicers, filters, and other interactive elements that allow users to customize views according to their specific needs.
## File Deliverables
This document includes all Power Query M-code scripts used to clean and transform the original HR dataset. It outlines the steps applied to standardize fields, convert data types, and enhance the dataset for use in the Power BI dashboard.https://github.com/Vivek23170/Team9-healthcare-workforce-visuals/blob/7977eec39802a8ab41d7c07eb229d5c64e737960/File%20Deliverables.docx




