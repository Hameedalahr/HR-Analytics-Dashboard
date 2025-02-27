# HR Analytics Dashboard

## Overview
The **HR Analytics Dashboard** is an interactive Power BI report that provides insights into employee attrition. It visualizes key HR metrics such as employee count, attrition rate, salary distribution, education background, and job roles to help organizations analyze workforce trends and make data-driven decisions.

## Features
- **Key Metrics Display**: Employee count, attrition count, attrition rate, average age, salary, and tenure.
- **Attrition Breakdown**:
  - By Gender
  - By Age Group
  - By Education Background
  - By Salary Range
  - By Job Role
- **Interactive Filters**: Users can switch between departments (Human Resources, Research & Development, Sales) for targeted analysis.
- **Visualizations**: Pie charts, bar charts, and line graphs to display attrition trends.

## Tech Stack
- **Power BI**: For data visualization and dashboard creation.
- **CSV Dataset**: Employee data file used for analysis.

## Screenshots

### CSV File
![Raw CSV File](https://github.com/Hameedalahr/HR-Analytics-Dashboard/blob/main/excel.png?raw=true)

### Human Resources
![Human Resources](https://github.com/Hameedalahr/HR-Analytics-Dashboard/blob/main/Human%20Resources.png?raw=true)

### Research & Development
![Research & Development](https://github.com/Hameedalahr/HR-Analytics-Dashboard/blob/main/Research%20&%20Development.png?raw=true)

### Sales
![Sales](https://github.com/Hameedalahr/HR-Analytics-Dashboard/blob/main/Sales.png?raw=true)

## Installation & Usage
1. **Download the Dataset**:
   - The dataset file (`HR_Analytics.csv`) is included in this repository.
2. **Open in Power BI**:
   - Open Power BI Desktop.
   - Import the dataset by clicking **Home > Get Data > Text/CSV**.
3. **Load and Transform Data**:
   - Use Power Query Editor to clean and transform the data if needed.
4. **Build and Explore**:
   - Open the provided `.pbix` file to view the dashboard.
   - Interact with the filters and explore insights.

## Dataset Description
The dataset contains the following attributes:
- **Employee ID**
- **Age**
- **Salary**
- **Job Role**
- **Education**
- **Attrition Status** (Yes/No)
- **Gender**
- **Department**
- **Experience in Years**

## Future Improvements
- Adding predictive modeling for attrition risk assessment.
- Enhancing interactivity with drill-through pages.
- Integrating real-time data sources.
