# Human Resources (HR) Dashboard
## Introduction
In this project I will examine demographic data about employees of an organization and derive insights in Power BI. The dashboards include insights on employee satisfaction levels, performance rating, retrenchment and promotion status.
## Dashboard
View the full dashboard [here](https://github.com/mwang-cmn/HR-Dashboard-and-Notebook/blob/main/HR%20Dashboard.pbix)

## Data Understanding
In this project I will use 2 datasets that can be found [here](https://drive.google.com/file/d/1h4bvZlHJUFAYJ5CbleAmLr6muAX1Q7rm/view)
Here is a summary of the first dataset
| Column                      | Type         | Description                                             | Example Values                            |
|-----------------------------|--------------|---------------------------------------------------------|-------------------------------------------|
| Age                         | Integer      | Age of the employee                                     | 34, 29, 45                                |
| Attrition                   | Categorical  | Whether the employee has left the company or not        | Yes, No                                   |
| BusinessTravel              | Categorical  | Frequency of business travel for the employee           | Travel_Rarely, Travel_Frequently, Non-Travel |
| DailyRate                   | Integer      | Daily rate of pay for the employee                      | 1102, 279, 1373                           |
| Department                  | Categorical  | Department of the employee                              | Sales, Research & Development             |
| DistanceFromHome            | Integer      | Distance from home to work in miles                     | 1, 8, 2                                   |
| Education                   | Integer      | Education level of the employee                         | 1, 2, 4                                   |
| EducationField              | Categorical  | Field of education of the employee                      | Life Sciences, Medical, Other             |
| EmployeeCount               | Integer      | Employee count (always 1 in this dataset)               | 1                                         |
| EmployeeNumber              | Integer      | Unique identifier for the employee                      | 1, 2, 4                                   |
| EnvironmentSatisfaction     | Integer      | Satisfaction with the environment                       | 2, 3, 4                                   |
| Gender                      | Categorical  | Gender of the employee                                  | Male, Female                              |
| HourlyRate                  | Integer      | Hourly rate of pay for the employee                     | 94, 61, 92                                |
| JobInvolvement              | Integer      | Involvement in the job                                  | 3, 2, 4                                   |
| JobLevel                    | Integer      | Level of the job                                        | 2, 1, 4                                   |
| JobRole                     | Categorical  | Role of the employee                                    | Sales Executive, Research Scientist       |
| JobSatisfaction             | Integer      | Satisfaction with the job                               | 4, 2, 3                                   |
| MaritalStatus               | Categorical  | Marital status of the employee                          | Single, Married, Divorced                 |
| MonthlyIncome               | Integer      | Monthly income of the employee                          | 5993, 5130, 2090                          |
| MonthlyRate                 | Integer      | Monthly rate of pay for the employee                    | 19479, 24907, 2396                        |
| NumCompaniesWorked          | Integer      | Number of companies the employee has worked for         | 8, 1, 6                                   |
| Over18                      | Categorical  | Whether the employee is over 18 years old (always Y)    | Y                                         |
| OverTime                    | Categorical  | Whether the employee works overtime                     | Yes, No                                   |
| PercentSalaryHike           | Integer      | Percentage increase in salary                           | 11, 23, 15                                |
| PerformanceRating           | Integer      | Performance rating of the employee                      | 3, 4                                      |
| RelationshipSatisfaction    | Integer      | Satisfaction with relationships at work                 | 1, 4, 2                                   |
| StandardHours               | Integer      | Standard working hours (always 80 in this dataset)      | 80                                        |
| StockOptionLevel            | Integer      | Level of stock options                                  | 0, 1, 3                                   |
| TotalWorkingYears           | Integer      | Total years of working experience                       | 8, 10, 7                                  |
| TrainingTimesLastYear       | Integer      | Number of training sessions attended last year          | 0, 3, 6                                   |
| WorkLifeBalance             | Integer      | Work-life balance rating                                | 1, 3, 2                                   |
| YearsAtCompany              | Integer      | Number of years at the current company                  | 6, 10, 0                                  |
| YearsInCurrentRole          | Integer      | Number of years in the current role                     | 4, 7, 0                                   |
| YearsSinceLastPromotion     | Integer      | Number of years since the last promotion                | 0, 1, 3                                   |
| YearsWithCurrManager        | Integer      | Number of years with the current manager                | 5, 7, 0                                   |

The employee dataset is as follows:
| Column                      | Type         | Description                                             | Example Values                            |
|-----------------------------|--------------|---------------------------------------------------------|-------------------------------------------|
| EmployeeNumber              | Integer      | Unique identifier for the employee                      | 1, 2, 4                                   |
| Employee Name               | String       | Name of employee                                        | John, Mary                                |



