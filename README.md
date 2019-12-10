
![Alt Text](https://media.giphy.com/media/3ornkeA6BgebRyJjfW/giphy.gif)

Problem Statement: We don’t know when good employees leave our company and we don’t know the exact impact of these high performers leaving our company.

Abstract of project: A data set containing the information of 14,999 employees of a company was provided. This list of employees belonged to ten different internal departments within the company, as well as information about their satisfaction level with the company, their last performance evaluation, the number of projects they worked on, the amount of promotions in the last five years, average monthly hours spent working, the amount of time they’ve been with the company, amount of work accidents, and if the have left the company already. I used logistic regression, decision tree, random forest, and a dummy classifier method to predict who will potentially be churning in the near future. The definition of high performance I used was if an employee possessed the evaluation score of the employee was higher than 0.8 and I looked at the employees who haven’t left the company yet, but have an 80% or higher probability of churning. Decision tree yielded the best score and the most important factors that influence an employee churn are satisfaction level, time spent with the company, and the number of projects worked on. 


Outcomes Predictions: The model yielded 2,722 employees out of the 11,428 current employees may be potentially leaving the company. 211 of the 2,722 them are what I considered high performers.


Data Acquisition: csv file from google drive


Data Preparation: ‘Satisfaction level’ and ‘last evaluation’ metrics were provided as percentages, whereas ‘time spent at company’, ‘average monthly hours’, ‘number of projects’, ‘work accident’, ‘promotion in last 5 years’, and ‘churn’ were provided as integers. ‘Salary’ and ‘department’ metrics were categorical values. The first step was to scale the integer values into a percentage and to dummy the categorical values. Then, balancing the data set was the following step since the target feature(churn) was only 24% of the data set. 


Important features: Satisfaction level, number projects, and the amount of time spent at company influenced the most for employee churn. Salary and number of work accidents were not critical factors in influencing employee churn.


