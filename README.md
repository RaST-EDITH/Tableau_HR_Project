# Tableau - HR Dashboard 📊

## Overview 🌟

The HR Dashboard is designed to equip HR managers with a comprehensive tool for analyzing human resources data. The dashboard features two main views: **Summary View** and **Employee Records View**. It offers both high-level insights and detailed employee records for in-depth analysis.

## Summary View 🔍

The **Summary View** is divided into three sections: **Overview**, **Demographics**, and **Income Analysis**.

### Overview 📈

The **Overview** section provides a snapshot of overall HR metrics, including:
- **Employee Counts**:
  - Total number of hired employees. 👥
  - Total number of active employees. 🟢
  - Total number of terminated employees. 🔴
- **Historical Trends**:
  - Visualization of the total number of hired and terminated employees over the years. 📆
- **Department and Job Titles**:
  - Breakdown of total employees by department and job titles. 🏢
- **Headquarters vs. Branches**:
  - Comparison of total employees between headquarters (HQ) and branches (New York is the HQ). 🌍
- **Geographic Distribution**:
  - Distribution of employees by city and state. 🌆

### Demographics 📊

The **Demographics** section provides insights into workforce composition, including:
- **Gender Ratio**:
  - Presentation of the gender ratio within the company. 🚻
- **Age and Education Distribution**:
  - Visualization of the distribution of employees across different age groups and education levels. 🎓
- **Age Group Details**:
  - Total number of employees within each age group. 🎂
- **Education Level Details**:
  - Total number of employees within each education level. 📚
- **Education and Performance**:
  - Correlation between employees’ educational backgrounds and their performance ratings. ⭐

### Income Analysis 💵

The **Income Analysis** section focuses on salary-related metrics:
- **Salary by Education Level**:
  - Comparison of salaries across different education levels for both genders to identify any discrepancies or patterns. 💰
- **Age and Salary Correlation**:
  - Presentation of how age correlates with salary within each department. 📈

## Employee Records View 🧑‍💼

The **Employee Records View** provides a detailed list of all employees with the following information:
- Name
- Department
- Position
- Gender
- Age
- Education
- Salary

### Filtering 🔍

Users can filter the list based on any of the available columns to view specific subsets of employee data.

## Data Generation 📊

To support the HR Dashboard, a realistic dataset of 8,950 records has been generated. The dataset includes various attributes to mimic real-world HR data:

- **Employee ID**: A unique identifier for each employee. 🆔
- **First Name**: Randomly generated. 🧑
- **Last Name**: Randomly generated. 👩
- **Gender**: Randomly chosen with a 46% probability for ‘Female’ and a 54% probability for ‘Male’. 🚺🚹
- **State and City**: Randomly assigned from a predefined list of states and their cities. 🌆
- **Hire Date**: Randomly generated with custom probabilities for each year from 2015 to 2024. 📅
- **Department**: Randomly chosen from a list of departments with specified probabilities. 🏢
- **Job Title**: Randomly selected based on the department, with specific probabilities for each job title within the department. 💼
- **Education Level**: Determined based on the job title, chosen from a predefined mapping of job titles to education levels. 🎓
- **Performance Rating**: Randomly selected from ‘Excellent’, ‘Good’, ‘Satisfactory’, ‘Needs Improvement’ with specified probabilities. 🌟
- **Overtime**: Randomly chosen with a 30% probability for ‘Yes’ and a 70% probability for ‘No’. ⏰
- **Salary**: Generated based on the department and job title, within specific ranges. 💵
- **Birth Date**: Generated based on age group distribution and job title requirements, ensuring consistency with the hire date. 🎂
- **Termination Date**: Assigned to a subset of employees (11.2% of the total) with specific probabilities for each year from 2015 to 2024, ensuring the termination date is at least 6 months after the hire date. ❌
- **Adjusted Salary**: Calculated based on gender, education level, and age, applying specific multipliers and increments. 💲

The dataset was created using a Python script, which structures the data generation process cleanly, using functions where appropriate, and includes comments to explain each step of the process. 🧑‍💻

## Features ⭐

- **Interactive Dashboards**: Visualize and interact with data through charts, graphs, and tables. 📊
- **Filtering Options**: Customize views and analyses by filtering data based on various criteria. 🔍
- **Historical Data**: Access historical data to track trends over time. 📅

## Getting Started 🚀

1. **Access the Dashboard**: Log in to the HR management system and navigate to the HR Dashboard section. 🔑
2. **Explore the Summary View**: Start by reviewing the Overview, Demographics, and Income Analysis sections for high-level insights. 📈
3. **Review Employee Records**: Use the Employee Records View to access detailed information and apply filters as needed. 📝
4. **Analyze Data**: Utilize the provided visualizations and filtering options to analyze data and generate insights. 📊

## Future Enhancements 🔮

- **Integration with External Data Sources**: To incorporate additional data for more comprehensive analysis. 🌐
- **Advanced Analytics Features**: Including predictive analytics and machine learning capabilities for deeper insights. 🤖

For any questions or issues, please contact the IT support team or refer to the help documentation available in the HR management system. 📞

## 📎 Contact

If you have any questions or need assistance with the project, please don't hesitate to contact me at 

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raghvendra-singh-053977226)

We are here to help you stay organized and monitor your daily task progress effectively.