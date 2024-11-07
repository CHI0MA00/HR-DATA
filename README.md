# HR-DATA
This HR data presents an overview of employee demographics and attrition trends.

---

### Project Title: HR Dataset
---

[Project Overview For HR Data](#project-overview-for-hr-data)

[Column Descriptions For Sales Data](#column-descriptions-for-sales-data)

[Data Sources](#data-sources)

[Tools Used](tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)


### Project Overview For HR Data
---
This dataset showcases a detailed view of an HR data analysis dashboard for an organization. This data also provides insights into employee statistics, attrition rates, demographic breakdowns, and department-specific data and provides a snapshot of workforce composition and areas with potential retention challenges, which will assist in effectively highlighting areas for improvement in retention and employee satisfaction.

### Column Descriptions For Sales Data
---
- Attrition: Indicates whether an employee has left the company (represented as "Yes" or "No").
- Business Travel: Frequency of business travel for the employee (e.g., "Rarely," "Frequently," "No Travel").
- CF_age band: Age group category of the employee, used to group ages into ranges (e.g., "  Under 25", "25-34," "35-44").
- CF_attrition label: Custom attrition label for categorizing employees based on attrition (cE.g., "Current Employee", "Ex-Employee").
- Department: Department where the employee works (e.g., "Sales," "Engineering," "HR")
- Education Field: Field of study of the employee’s highest education (e.g., "Engineering," "Human Resources").
- Employee Number: Unique identifier for each employee.
- Gender: Gender of the employee (e.g., "Male," "Female").
- Job Role: The specific job title or role of the employee within the organization (e.g., "Manager," "Sales Representative").
- Marital Status: Marital status of the employee (e.g., "Single," "Married").
- Over Time: Indicates if the employee works overtime (e.g., "Yes" or "No").
- Over18: Indicates if the employee is over 18.
- Training Times Last Year: Number of training the employee received training in the previous year.
- Age: Employee’s age.
- CF_current Employee: Indicating whether the employee is currently employed (1 = "Yes" or 0 = "No").
- Daily Rate: Daily wage of the employee (could be in dollars or any other currency).
- Distance From Home: Distance between the employee’s home and workplace.
- Education: Education level of the employee, often represented as a number.
- Employee Count: Typically the count of employees per row.
- Environment Satisfaction: Employee’s satisfaction with the work environment.
- Hourly Rate: Employee’s hourly wage.
- Job Involvement: Employee’s involvement in their job
- Job Level: The level or rank of the job within the organization.
- Job Satisfaction: Satisfaction level of the employee with their job (e.g., 1 = very dissatisfied, 2 = dissatisfied, 3 = satisfied, 4 = very satisfied).
- Monthly Income: Employee’s monthly income. 
- Monthly Rate: The monthly rate of pay, potentially used in salary calculations.
- Num Companies Worked: Number of companies the employee has worked for, which may indicate experience or stability.
- Percent Salary Hike: The percentage increase in salary from the previous year.
- Performance Rating: Performance rating of the employee.
- Relationship Satisfaction: Satisfaction level with personal relationships at work.
- Standard Hours: The standard working hours for an employee, often 40 hours per week.
- Stock Option Level: Level of stock options granted to the employee.
- Total Working Years: Total years of work experience the employee has had.
- Work Life Balance: Work-life balance satisfaction, often on a scale.
- Years At Company: Number of years the employee has been with the company.
- Years In Current Role: Number of years the employee has held their current role.
- Years Since Last Promotion: Number of years since the employee’s last promotion.
- Years With Current Manager: Number of years the employee has worked with their current manager.

### Data Sources
---
The primary source of data used is the "HR.data.csv" from an organisation.

### Tools Used
---
Power BI: Utilised For Data Cleaning and Visualization

### Data Cleaning and Preparations
---
#### Data Cleaning:
The data cleaning process was performed in Power BI, following these steps:

- Column Renaming: Renamed columns for improved clarity and consistency.

- New Column Creation: Used conditional column to classify age brackets (Age_Band) and Attrition Count.

### Exploratory Data Analysis
---
The dataset was imported from Excel to Power BI to answer the following questions:
- What is the total number of employees?
- What is the total Attrition count?
- What is the total number of current employees?
- Calculate the attrition rate.
- Find the average age.
- Give the total attrition count by departmet and Education fields.
- Calculate the total attrition by gender.
- Built an interactive dashboard to effectively present key findings, trends and patterns to gain insights.

### Data Analysis
---
- The total number of employees is 1470

- Total number of attritions is 237

- Total number of current employees is 1233

- Average age is 37

- Attrition rate is 16%

### Data Visualization
---

![HR DATA VISUALIZATION](https://github.com/user-attachments/assets/86a0d921-0a89-4c7d-8545-08ee76f10a7a)


