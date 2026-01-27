# Data Dictionary

This document provides clear definitions for each column used in the HR Attrition Workforce dataset. All fields are described based on their analytical usage in reporting and decision-making.

| Column Name                         | Data Type | Description                                                                                      |
|-------------------------------------|-----------|--------------------------------------------------------------------------------------------------|
| Employee_ID                         | Integer   | A unique numeric identifier assigned to each employee. This serves as the primary key for analysis and joins. |
| Age                                 | Integer   | The age of the employee in completed years at the time of data capture.                        |
| Gender                              | Text      | Gender classification of the employee, used for demographic analysis.                           |
| Department                          | Text      | The organizational department where the employee is currently assigned.                         |
| Job_Role                            | Text      | The official job designation or role performed by the employee within the department.          |
| Job_Level                           | Integer   | The hierarchical level of the employee within the organization, representing their seniority.   |
| Monthly_Income                      | Numeric   | The gross monthly salary earned by the employee, used for compensation and attrition analysis.  |
| Total_Working_Years                 | Integer   | The total number of years of professional experience across all organizations.                 |
| Years_at_Company                   | Integer   | The number of years the employee has worked with the current organization.                       |
| Years_in_Current_Role              | Integer   | The duration, in years, the employee has spent in their current job role.                       |
| Years_Since_Last_Promotion         | Integer   | The number of years that have passed since the employee last received a promotion.              |
| Performance_Rating                  | Integer   | The performance evaluation score assigned to the employee during the most recent appraisal cycle. |
| Job_Satisfaction                    | Integer   | The level of job satisfaction reported by the employee, measured on a predefined scale.       |
| Work_Life_Balance                   | Integer   | The employee's reported rating of work-life balance, indicating the sustainability of their workload. |
| Attrition                           | Text      | The attrition status indicating whether the employee has left the organization ("Yes") or is currently employed ("No"). |
