# Predicting Employee Turnover
# Overview
The goal of this project was to create an Extreme Gradient Boosting (XGBoost) model to predict employee turnover at a large motor company. This project utilized employee data that the company did not know how to utilise, but desired to take inititives to improve employee satisfaction. The final XGBoost model performed with 99% accuracy and 98% precision determining what features were most important in separating employees who leave from those who stay. Based on the model, the satisfaction level, the average monthly hours, and the last evaluation were most influential in determining whether an employee stayed with the company (>83%) vs one who left (<17%). 
# Business Understanding
High employee retention is crucial for several reasons. From cost savings and organisational knowledge, to team cohesion and customer satisfaction, high employee retention has numerous benefits that can contribute to a more stable, productive, and successful work environment. 
# Data Understanding
The data was collected internally by Sailfort Motors. It contained data on nearly 15000 past and current employees, with 18 features. The features included information on satisfaction levels, last evaluation scores, the number of projects completed, the average monthly hours, and promotions in the last five years. The data was engineered such that all relevant features were made interpretable by the XGBoost model.
# Modeling and Evaluation 
An XGBoost model comprising gradient boosted trees was used to determine feature importance in who would leave the company or not. The below plot shows that staisfaction, average monthly hours, and the last evaluation were the top 3 most important factors in determining an employee who stayed from one who would leave.

![alt text](https://github.com/hermathena/Portfolio/blob/110acb3f9650b892883ae154ff50ff506d235dd0/Chart%20of%20Feature%20Importance.png)

It is interesting to note that salary level had little importance. The business consequences of this insight are profound.
# Conclusion
This model can benefit the company, by allowing them to know which employees are likely to leave, giving the company the opportunity to seek proactive remedy. It also allows the company to identify the features that most contribute to employee retention, and avoid wasting resources on those that do not. In the future, addressing the details behind the satisfaction level scores would enable the company to better target the employee's perception of what is importance to them.
