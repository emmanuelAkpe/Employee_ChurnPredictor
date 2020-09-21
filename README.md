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
 The highest number of employees who quit the firm receives low or medium salary while very few of them receives high salary.
2. Turnover frequency based on Department\
The highest number of employees who quit the firm comes from the sales, technical and support departments.
3. Turnover frequency based on Work accident\
Most of the employees that left the firm did not have any work accident experience 
4. Turnover based on Promotion\
 None of the employees that had promotion in the last 5years left the firm whiles most of the employees that did not get any promotion for the past 5 years left.

![ch1 4](https://user-images.githubusercontent.com/68768460/93789319-37e38780-fc21-11ea-9f96-14e8326e2629.gif)

In a similar way, a user can view the correlation matrix in order to determine the correlation between the target variable and the features.

![ch1 5](https://user-images.githubusercontent.com/68768460/93790092-2a7acd00-fc22-11ea-9065-20b421550e25.gif)

In order to visualize a cluster of the employees that leave the firm, the user has to click on *Visualize cluster of employees who quit* 

![ch1 6](https://user-images.githubusercontent.com/68768460/93791029-37e48700-fc23-11ea-8e75-303e6fb81b75.gif)

Insights Made from this session:\
Employees who left the company can be grouped into three clusters
1. Employees who have high satisfaction and also high evaluation(shaded by green)
2. Employees who have low satisfaction and High Evaluation(shaded by blue)
3. Employees who have moderate satisfaction and moderate evaluation(Shaded by grey)

When the user selects Prediction, he or she is allowed to enter the test_size(number of rows you want to test or validate your model with) and also the random state.The user now has the option to select either of the following machine learning models:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting classifier\
When the user selects any of the above classifiers, the model is automatically generated and then the model performance are displayed on the screen.

![ch1 7](https://user-images.githubusercontent.com/68768460/93793014-c6f29e80-fc25-11ea-99dc-5d6106072de8.gif)

WHen the results are generated and the user is not please with the results, he or she can tune the hyperparameters by just clicking or better still, selecting different model.\
The user can equally visualize the metrics associated with each model developed.

![ch1 8](https://user-images.githubusercontent.com/68768460/93793783-d1616800-fc26-11ea-9f8f-bcc23a9aa7a4.gif)

Finally, the user can predict whether an employee will leave the firm or not by entering the feature values.


![ch1 9](https://user-images.githubusercontent.com/68768460/93795203-96603400-fc28-11ea-97d1-689cbac465ba.gif)
