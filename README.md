# human-resources-BI-report
This dashboard deals with performance indicators of workers and wages in a mid- sized business call planet induestries by the following categories:

- Departments
- Sex 
- Salary
- Performance
- Employee
The required data consist of 3 datasets that contains information about employees, performance and salary.

## Employee table
- ID: It has the employees' ids
- employee_name: It has the name of the employees
- state: It holds the state where the employees live in
- birth_date: This column stores the birth date of the employees
- gender: This column holds the employee gender
- department: This column has the corresponding department where every employee works.
- position: It has the employee position in the company
- boss_name: It refers to each corresponding boss of the employee

## Performance
This table just contains the employee id along with its performance evaluation

## Salary
This table contains the employee id and his corresponding salary.


# Employee analysis
![image](https://user-images.githubusercontent.com/99763884/210819574-49cd517b-8220-4b3b-bc08-22cc6b53083f.png)

# Salary analysis
![image](https://user-images.githubusercontent.com/99763884/210822755-0be3884e-ad43-419d-98d1-2a991cdb3aff.png)

# Evaluation analysis
![image](https://user-images.githubusercontent.com/99763884/210822835-fe77b497-b958-4390-a62e-3f486bf52b49.png)


## Key insights:
- The department with most employees is the production department followed by IT department
- IT employees earn more, on average, than production employees
- Most of the company employees are between 30 - 40 years old
- Age is positively correlated with salary in the company
- Evaluation of employee performance in the company is similar in men and women
- The company has more female worker than men, nonetheless, men earn more than 8000 dollars than women
- Most of the company employees are located in Texas, massachusetts and California





# Human Resources Report buildig
In the first place, new columns were added to create some new categories based on quantitative data to narrow down the scope of the analysis and ease the analysis 
process. The following DAX code was used to create the new columns:

### Age range in the employee tables:
![image](https://user-images.githubusercontent.com/99763884/210816770-64013814-5135-43a8-bd25-bcf45f09f709.png)
This image was created with the Carbon tool if you ever want to share your code in a format like this. Here is the link to format the code like that:
https://carbon.now.sh/

###  Evaluation group
![image](https://user-images.githubusercontent.com/99763884/210817970-0fe78e00-a6ab-4581-9a1c-79cd0eba92c2.png)


### Salary group
![image](https://user-images.githubusercontent.com/99763884/210818248-2a5eaee1-592e-4966-9dff-bf42f0bf0016.png)




