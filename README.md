# Failure-Employee-Productivity-Prediction-In-The-Garment-Industries
Pacmann Project Statistics Business
1.	Introduction and Background 
The garment industry is one of the most dominating industries in this era of industrial globalization. It is a highly labor-intensive industry that requires a large number of human resources to produce its goods and fill up the global demand for garment products. Because of the dependency on human labor, the production of a garment company comprehensively relies on the productivity of the employees who are working in different departments of the company. A common problem in this industry is that the actual productivity of the garment employees sometimes does not meet the targeted productivity that was set for them by the authorities to meet the production goals in due time. When the productivity gap occurs, the company faces a huge loss in production.

The Objective is to determine which factor has significant impact on unachieved employee productivity, analyze the relationship of attributes which have the significant correlation to the outcome and make the regression model.
2.	Dataset 
2.1 About dataset
The dataset derived from Kaggel, it’s contain daily productivity data of employees in the garment industry includes important attributes that related, which had been collected manually and also been validated by the industry experts. The attributes and the data types are listed below:
1)	day : Day of the Week (categorical).
2)	quarter : A portion of the month. A month was divided into four quarters (categorical).
3)	department : Associated department with the instance (categorical).
4)	team_no : Associated team number with the instance (categorical).
5)	no_of_workers : Number of workers in each team (numerical).
6)	no_of_style_change : Number of changes in the style of a particular product (numerical).
7)	targeted_productivity : Targeted productivity set by the Authority for each team for each day (numerical).
8)	smv : Standard Minute Value, it is the allocated time for a task (numerical).
9)	wip : Work in progress. Includes the number of unfinished items for products (numerical).
10)	over_time : Represents the amount of overtime by each team in minutes (numerical).
11)	incentive : Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action (numerical).
12)	idle_time : The amount of time when the production was interrupted due to several reasons (numerical).
13)	idle_men : The number of workers who were idle due to production interruption (numerical).
14)	actual_productivity : The actual % of productivity that was delivered by the workers. It ranges from 0-1 (numerical).
