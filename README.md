# Student Analytics Dashboard

This repository contains an end-to-end data analytics project focused on converting unstructured student data into a structured format and building an interactive Power BI dashboard to generate actionable insights.

The project demonstrates my approach to data cleaning, transformation, consolidation, and visualization using Excel (Power Query) and Power BI.

---

## Project Objective

The objective of this project was to:

- Convert unstructured and semi-structured raw data into a clean, structured dataset
- Design a scalable and repeatable data processing approach
- Build a one-page interactive Power BI dashboard for student analytics
- Document both the data transformation logic and visualization insights clearly

---

## Repository Contents

| File | Description |
|-----|-------------|
| **Raw_to_structureddata.xlsx** | Excel file containing raw data and Power Query transformations used to convert unstructured data into structured format |
| **Student_analytics.pbix** | Power BI dashboard file with interactive visuals |
| **structured_data_vanya.pdf** | Documentation explaining the structured data creation approach |
| **Visualization_insights_vanya.pdf** | Summary of insights derived from the Power BI dashboard |

---

## Data Processing Approach

The raw data was received in multiple Excel sheets with inconsistent headers, missing values, and duplicate fields.  
To handle this, I followed a structured approach:

1. **Data discovery & profiling** to understand structure and quality issues  
2. **Schema standardization** by normalizing column names and data types  
3. **Data consolidation** by appending multiple sheets and merging related datasets  
4. **Duplicate handling** using unique identifiers such as Email and Enrollment Number  
5. **Null handling & validation** based on logical and business rules  
6. **Derived fields creation** such as Age Groups for analysis  

This approach was designed to be reusable for any future unstructured datasets.

A detailed explanation of this methodology is available here:  
### Structured Data Approach Document
📄 [Structured Data Approach Document](structured_data_vanya.pdf)

---

## Dashboard Overview

The Power BI dashboard provides a one-page analytical view with:

- KPI cards for Total Students, Total Branches, and Average Age  
- Student distribution by Branch and Course  
- Age group analysis  
- Top institutions by student count  
- Interactive slicers for Branch and Course  

### Power BI Dashboard File
![Dashboard Preview](dashboard_preview.png)

---


---

## Visualization Insights

Key insights derived from the dashboard include:

- Dominant branches and courses among students  
- Age distribution trends across branches  
- Institutions contributing the highest number of students  

These insights are summarized in:  
### Visualization Insights
📈 [Visualization Insights Document](Visualization_insights_vanya.pdf)

---

## Tools & Technologies Used

- Microsoft Excel (Power Query)
- Power BI Desktop

---

## Outcome

This project showcases my ability to:

- Handle messy, unstructured data  
- Build scalable data transformation pipelines  
- Create meaningful, business-ready dashboards  
- Clearly document analytical approaches and insights  

It reflects an end-to-end data analytics workflow from raw data to decision-ready visuals.


