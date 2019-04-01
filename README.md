# The answers to the following questions are in the notebook
## Umuzi assignment 2: Predicting salary differences
## Simple Linear Regression

### Instructions:
In the next series of challenges, we will predict employee salaries from different employee characteristics (or features).
We are going to use a simple supervised learning technique: linear regression. We want to build a simple model to determine how well Years Worked predicts an employee’s salary.
Import the data salary.csv to a Jupyter Notebook. A description of the variables is given in Salary Metadata. You will need the packages matplotlib, pandas and statsmodels.

### Answer the following questions:
Split your data into a training and test set. Train your model using the training set and answer the following questions:

1.	Using the `statsmodels` package, run a simple linear regression for Salary with one predictor variable: Years Worked.
	  * Does the model significantly predict the dependent variable? Report the amount of variance explained (R^2) and significance value (p) to support your answer.
	  * What percentage of the variance in employees’ salaries is accounted for by the number of years they have worked?
2. What does the unstandardized coefficient (B or 'coef' in statsmodels) tell you about the relationship between Years Worked and Salary?
3. What do the 95% confidence intervals [0.025, 0.975] mean?
4.	Calculate the expected salary for someone with 12 years’ work experience.
5.	Calculate the expected salary for someone with 80 years’ work experience. Are there any problems with this prediction? If so, what are they?
6.	We have only looked at the number of years an employee has worked. What other employee characteristics might influence their salary?

Now fit your model to your test set.

7. How does your model compare when running it on the test set - what is the difference in the Root Mean Square Error (RMSE) between the training and test sets?

