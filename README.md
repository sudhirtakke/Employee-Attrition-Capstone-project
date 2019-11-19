# Employee-Attrition-Capstone-project
INSAID capstone project - ML 

## INTRODUCTION
### Predict whether or not an employee would stay given the data of employees at a company.<br/>
Your client for this project is the HR Department at a software company <br/>
####  They want to try a new initiative to retain employees.<br/>
  The idea is to use data to predict whether an employee is likely to leave.<br/>
  Once these employees are identified, HR can be more proactive in reaching out to them before it's too late.<br/>
  They only want to deal with the data that is related to permanent employees.<br/>
Current Practice Once an employee leaves, he or she is taken an interview with the name "exit interview" and shares reasons for leaving. The HR Department then tries and learns insights from the interview and makes changes accordingly.

This suffers from the following problems:<br/>
  This approach is that it's too haphazard. The quality of insight gained from an interview depends heavily on the skill of the interviewer.<br/>
  The second problem is these insights can't be aggregated and interlaced across all employees who have left.<br/>
  The third is that it is too late by the time the proposed policy changes take effect.<br/>
  
#### If the HR department hires you as data science consultants and want you to supplement their exit interviews with a more proactive approach, how would help them in this problem.

## Data Description 

Below are the details of different features of the input data
### department_data

This dataset contains information about each department. The schema of the dataset is as follows:<br/>
    dept_id – Unique Department Code<br/>
    dept_name – Name of the Department<br/>
    dept_head – Name of the Head of the Department<br/>

### employee_details_data

This dataset consists of Employee ID, their Age, Gender and Marital Status. The schema of this dataset is as follows:<br/>
    employee_id – Unique ID Number for each employee<br/>
    age – Age of the employee<br/>
    gender – Gender of the employee<br/>
    marital_status – Marital Status of the employee<br/>

### employee_data

This dataset consists of each employee’s Administrative Information, Workload Information, Mutual Evaluation Information and Status.<br/>

### Target variable
    status – Current employment status (Employed / Left)<br/>

### Administrative information
    department – Department to which the employees belong(ed) to
    salary – Salary level with respect to rest of their department
    tenure – Number of years at the company
    recently_promoted – Was the employee promoted in the last 3 years?
    employee_id – Unique ID Number for each employee

### Workload information
    n_projects – Number of projects employee has worked on
    avg_monthly_hrs – Average number of hours worked per month

### Mutual evaluation information
    satisfaction – Score for employee’s satisfaction with the company (higher is better)
    last_evaluation – Score for most recent evaluation of employee (higher is better)
    filed_complaint – Has the employee filed a formal complaint in the last 3 years?
    
## Evaluations of different models 
![image.png](images/evaluations.png)
    
    
