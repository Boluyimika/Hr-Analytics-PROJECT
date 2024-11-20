# HR Analytics Project

## Table of Content
1. [Introduction](#Introduction)
2. [Objectives](#Objectives)
3.  [Data_Overview](#Data_Overview)
4.  [Tools_Used](#Tools_Used)
5.  [Data_loading_and_preprocesing](#Data_loading_and_preprocesing)
6.  [Data_cleaning&Exploration_data_analysis](#Data_cleaning&Exploration_data_analysis)
7.  [visualizations](#visualizations)
8.  [Analysis](#Analysis)
9.  [Recommendations](#Recommendations)

 
 


## Introduction

This project focuses on analyzing HR data to gain insights into various aspects of employee demographics, behaviors, and trends within an organization. 
The goal is to utilize the data to understand key factors affecting employee turnover, job satisfaction, and overall workforce dynamics.
---
## Objectives
To develop HR strategies that address workload imbalances, support diversity and inclusion, and enhance well-being programs to meet the needs of employees with varied personal and professional backgrounds.

## Data_Overview

The dataset used in this project is a CSV file named HR Analytics Data.csv, which contains the following columns:

- Age:Employees Age
- Attrition:Employee Attrition.
- BusinessTravel:how frequently an employee travels for business purpose
- Dailyrate:Daily wage of an employee.
- Distance from home:Distance form home to office in KM's
- Overtime: Indicates whether the employee has worked overtime
- MaritalStatus: Employee's marital status
- JobRole: The specific job role or position held by the employee
- Gender: Gender of the employee.
- Education:Qualification of employee.
- EducationField: The field of education the employee pursued
- Department: Employees department
- EducationLevel: employees education level
- EmployeeCount
- EmployeeNumber

## Tools_Used 
The analysis is conducted using Python leveraging libraries such as 
- pandas
- matplotlib
- seaborn for data manipulation and visualization.


## Data_loading_and_preprocesing
![Data loading](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/Data_Loading.png?raw=true)
---
## Data_cleaning&Exploration_data_analysis
![Data Exploration](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/Data%20Cleaning&%20Exploration.png?raw=true)

## visualizations
![Chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/plot_distribution%201.png?raw=true)
---
## Analysis


### Distribution of Age
**Analysis**: The age distribution appears to be somewhat skewed towards younger ages, with a peak around the early 30s and a gradual decline after age 40.

**Insights**: This could indicate that the organization has a relatively young workforce, with fewer employees above the age of 50. This may suggest a focus on early to mid-career employees or a high turnover rate as employees age. HR could explore retention strategies for older employees or development programs targeted at younger staff for career growth.
![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/age_distribution.png?raw=true)

### Business Travel Distribution by Department
**Analysis** :Most employees either "Travel Rarely" or "Do Not Travel" across departments. However, "Travel Frequently" is more common in the Sales department than in Research & Development or Human Resources.

**Insights**: Frequent travel in the Sales department is expected and might be related to business demands. However, frequent travel can contribute to employee burnout, especially in sales roles, which often have high turnover. HR might consider providing additional support to traveling employees in sales, such as flexible work arrangements or wellness programs.

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/Business_travel_by_department.png?raw=true)
---

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/plot_distribution2.png?raw=true)
---
### Gender Distribution by Department

**Analysis** : The Research & Development department shows a higher male-to-female ratio, while Sales has a relatively more balanced distribution. Human Resources has a low overall count, with a slight female majority.

**Insights**: The gender imbalance in Research & Development suggests potential diversity challenges, which could impact the company culture and innovation. HR could implement diversity initiatives to attract more female employees to technical roles. Additionally, for departments with significant gender imbalances, targeted recruitment efforts could help balance the workforce and promote an inclusive environment.

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/Gender_distribution_department_barplot_with_labels.png?raw=true)
### Job Role for each department
The bar chart shows the distribution of job roles in each department.

**Analysis**:  
- The Sales department has the most employees (326), followed by the Research & Development department (292). The Human Resources department has the least employees (11).
- The Sales department has a single job role (Sales Executive), while the Research & Development department has multiple job roles (Research Scientist, Laboratory Technician, Manufacturing Director, Healthcare Representative, Manager, Sales Representative, Research Director). The Human Resources department has only one job role (Human Resources).

**Insight**:this chart provides insight into the organizational structure of a company, showing which departments are the largest and which have the most diverse range of job roles.

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/business_travel_jobrole_barplot_with_labels.png?raw=true)
---

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/plot_distribution3.png?raw=true)
---
### Distribution of Education
The histogram shows the distribution of education fields 

**Analysis**: The most common field is Life Sciences, followed by Medical. Other fields are significantly less common, with the fewest people in the "Resources" field.The smooth blue curve is a kernel density estimate, which helps to visualize the distribution of the data and highlight areas of high concentration.

**Insight**: This could be useful for understanding the demographics of the data, or for making decisions about how to target certain groups

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/EducationField_distribution.png?raw=true)

### Marital Status Distribution
**Analysis**: The distribution shows that the majority of the people are single, followed by married, and then divorced. The curve of the graph suggests that there are more people who are either single or married, with a smaller number of divorced individuals. 

**Insight**: The distribution of marital status is not normally distributed, with a peak at the single status and a smaller peak at the married status.

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/MaritalStatus_distribution.png?raw=true)

### Overtime Distribution
**Analysis**:The chart shows the distribution of overtime work in a dataset. 

**Insight**: The vast majority of employees (around 80%) do not work overtime. Only a small minority (around 20%) work overtime.

![chart](https://github.com/Boluyimika/Hr-Analytics-PROJECT/blob/main/OverTime_distribution.png?raw=true)
---
## Recommendations

 ### Enhance Workload Balance and Overtime Management
Redistribute Workloads: Identify the roles or departments where overtime is most common and consider redistributing tasks to ensure a more balanced workload. This may involve cross-department collaboration or hiring additional staff in high-demand areas.

Overtime Monitoring and Management: Implement a system to regularly monitor overtime hours. Set clear guidelines and encourage managers to recognize signs of burnout to help avoid overburdening employees.

Flexible Work Arrangements: Offer flexible work options, such as compressed workweeks or remote work days, especially for employees frequently working overtime. This could help reduce stress and improve work-life balance.

### Career Development Opportunities for Single-Role Departments
Create Development Paths in Sales and HR: For departments with limited role diversity (like Sales and Human Resources), establish structured career paths. For example, add roles with distinct levels (e.g., Junior, Mid-Level, Senior) or specializations (e.g., Account Manager, Sales Strategist) to provide employees with a clearer sense of progression.

Cross-Training and Rotation Programs: Allow Sales Executives or HR personnel to participate in cross-departmental projects or rotation programs. This not only broadens skill sets but also helps prevent job stagnation and promotes internal career mobility.

### Support Diversity and Inclusion Initiatives

Gender Diversity Initiatives in R&D: Actively recruit and retain more women in the R&D department. This could involve outreach to female candidates in relevant fields or offering mentorship and sponsorship programs to help women progress within technical roles.

Educational Field Expansion: Since Life Sciences and Medical are dominant, consider expanding recruitment efforts to include more varied educational backgrounds. Engaging with academic institutions and programs in underrepresented fields (e.g., Business, Engineering) can help build a more diverse talent pipeline.

### Implement Targeted Employee Well-being Programs

Tailored Benefits for Different Demographics: Provide benefits that cater to the different needs of single, married, and divorced employees. For instance, consider offering flexible working hours, family leave policies, and mental health support. Married employees may value benefits like family health coverage, while single employees may appreciate opportunities for professional growth and networking.

Stress Management and Wellness Initiatives: High-travel roles, like those in Sales, may benefit from wellness programs focusing on travel stress management, mental health support, and resilience training. Offer resources such as travel-related wellness stipends, gym memberships, and access to wellness apps.

###  Optimize Business Travel Policies

Travel Alternatives and Flexibility: Assess whether some travel could be replaced by virtual meetings. Where travel is essential, provide flexibility in travel arrangements, allowing employees to choose travel schedules that reduce stress.

Post-Travel Recovery Time: Allow employees some buffer time post-travel for rest and to catch up on tasks. This can help in reducing burnout and improving productivity.

### Regular Employee Engagement and Feedback

Employee Satisfaction Surveys: Conduct periodic surveys to assess employee satisfaction with workload, career development opportunities, and well-being support. This will provide insights into areas that need improvement and help management stay connected to evolving employee needs.

Focus Groups for Continuous Improvement: Establish focus groups for employees in single-role departments (like Sales and HR) to share their experiences and feedback. Their insights can guide further role diversification or development opportunities.

### Retain Older and Experienced Staff
Mentorship Programs: Create mentorship programs where older, experienced employees mentor younger team members. This helps retain valuable knowledge within the organization and provides younger employees with growth opportunities.

Career Longevity Initiatives: Offer programs that support career longevity, such as part-time work options for experienced employees approaching retirement. This helps retain experienced talent and ensures knowledge transfer.



## Installation
To run the code and reproduce the analysis on your local machine, follow these steps:

## Clone this repository:

bash
Copy code
git clone https://github.com/Boluyimika/hr-analytics-project.git
Navigate to the project directory:

bash
Copy code
cd hr-analytics-project
## Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Ensure that you have the HR Analytics Data.csv file in the project directory.

## Usage
The analysis is contained within a Jupyter notebook (HR_Analytics_Analysis.ipynb). You can run the notebook to execute the analysis and generate visualizations. 

To start the Jupyter notebook, use the following command:

bash
Copy code
jupyter notebook HR_Analytics_Analysis.ipynb

## Contributing
Contributions are welcome! If you'd like to improve the analysis or add new features, feel free to fork this repository, make your changes, and submit a pull request.

Fork the repository.
Create a new branch for your feature or bugfix.
Commit your changes.
Push to your branch.
Submit a pull request.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any inquiries or suggestions, please reach out:

Name: Peace.E.Bamigboye

Email: peaceboluwatife98@gmail.com
