## Employee_ChurnPredictor
The Employee_churnPredictor is a machine learning Application developed to help a firm to predict whether or not a particular employee will quit the job or not.It is a web application and can be accessed using the internet browser like  google chrome, explorer and the like. The application performs the following functions:
1. View data Report
2. Visualize the employee dataset
3. Develop and make predictions

That is, the application will enable a firm to predict whether an employee will stay or not without going through any complex process.

![Churn1](https://user-images.githubusercontent.com/68768460/93776747-6a868380-fc13-11ea-979a-3054578e5dd0.png)

### How It WORKS
The interface has three main sections name:
1. Data Report
2. Visualize_Datset
3. Predictions

Once the user selects Data Report, the system automatically generates all the statistical information on the dataset.


![ch1 1](https://user-images.githubusercontent.com/68768460/93778754-c6520c00-fc15-11ea-82e1-f62ce81d178f.gif)

The following insights were drawn from the dataset:
1. The dataset is made up of 14999 rows and 10 columns
2. All the columns are numeric except the department and the salary columns
3. The target column is QUit
4. there are no missing values

The following describes the various columns of the employee dataset:
* satisfaction_level: It is employee satisfaction point, which ranges from 0-1.
* last_evaluation: It is evaluated performance by the employer, which also ranges from 0-1.
* number_projects: How many numbers of projects assigned to an employee?
* average_monthly_hours: How many average numbers of hours worked by an employee in a month?
* time_spent_company: time_spent_company means employee experience. The number of years spent by an employee in the company.
* work_accident: Whether an employee has had a work accident or not.
* promotion_last_5years: Whether an employee has had a promotion in the last 5 years or not.
* Departments: Employee's working department/division.
* Salary: Salary level of the employee such as low, medium and high.
* quit: Whether the employee has left the company or not.

### Data Visualization
When the user selects 'Visualize_dataset', he/she is presented with the options below:
* Bar chart
* Turnover Frequency on other Variables
* pie chart
* Correlation matrix
* Visualize cluster of employees who quit

When the user selects *Bar Chart* he or she is provided automatically with a bar graph showing the distribution of all the categorical columns in the dataset.

![ch1 2](https://user-images.githubusercontent.com/68768460/93781694-2c8c5e00-fc19-11ea-8e30-87a1f9d001c6.gif)

Insights made from the Dataset:
1. Out of 14999 employees, 3571 left the company and 11428 stayed 
2. Most of the employees have done 3-5 projects with only few of the employees doing 6-7 projects
3. Most of the employees have spent 2-4 years in the firm whiles very few of them have spent about 7-10 years
4. Most of the employees have not had any accident on the job whiles a vey few of them have had accidents.
5. Most of the employees are in the sales, technical and support departments.
6. Most of the employees receive low salary and few of them receive high salary.
7. Very few number of employees have gotten promotion in the last five years.

Also, When the user selects *Turnover Frequency on other Variables* he or she is provided automatically with a bar graph which shows whether an employee left the company or not based on other columns.

![ch1 3](https://user-images.githubusercontent.com/68768460/93784844-f8b33780-fc1c-11ea-966b-a7659e3a761f.gif)

Insights Made from this session:
1. Turnover frequency based on salary levels\
 The highest number of employees who quit the firm receives low or medium salary while very few of them receiving high salary.
2. Turnover frequency based on Department\
The highest number of employees who quit the firm comes from the sales, technical and support departments.
3. Turnover frequency based on Work accident\
Most of the employees that left the firm did not have any work accident experience 
4. Turnover based on Promotion\
 None of the employees that had promotion in the last 5years left the firm whiles most of the employees that did not get any promotion for the past 5 years left.

![ch1 4](https://user-images.githubusercontent.com/68768460/93789319-37e38780-fc21-11ea-9f96-14e8326e2629.gif)




