Background:

We are a small startup focusing mainly on providing machine learning solutions in the European banking market. We work on a variety of problems including fraud detection, sentiment classification and customer intention prediction and classification.

We are interested in developing a robust machine learning system that leverages information coming from call center data.

Ultimately, we are looking for ways to improve the success rate for calls made to customers for any product that our clients offer. Towards this goal we are working on designing an ever evolving machine learning product that offers high success outcomes while offering interpretability for our clients to make informed decisions.

Data Description:

The data comes from direct marketing efforts of a European banking institution. The marketing campaign involves making a phone call to a customer, often multiple times to ensure a product subscription, in this case a term deposit. Term deposits are usually short-term deposits with maturities ranging from one month to a few years. The customer must understand when buying a term deposit that they can withdraw their funds only after the term ends. All customer information that might reveal personal information is removed due to privacy concerns.

Attributes:

age : age of customer (numeric)

job : type of job (categorical)

marital : marital status (categorical)

education (categorical)

default: has credit in default? (binary)

balance: average yearly balance, in euros (numeric)

housing: has a housing loan? (binary)

loan: has personal loan? (binary)

contact: contact communication type (categorical)

day: last contact day of the month (numeric)

month: last contact month of year (categorical)

duration: last contact duration, in seconds (numeric)

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

Output (desired target):

y - has the client subscribed to a term deposit? (binary)

Download Data:

https://drive.google.com/file/d/1EW-XMnGfxn-qzGtGPa3v_C63Yqj2aGf7

Goal(s):

Predict if the customer will subscribe (yes/no) to a term deposit (variable y)

Success Metric(s):

Hit %81 or above accuracy by evaluating with 5-fold cross validation and reporting the average performance score.

Bonus(es):

We are also interested in finding customers who are more likely to buy the investment product. Determine the segment(s) of customers our client should prioritize.

What makes the customers buy? Tell us which feature we should be focusing more on.
Submission Instructions:
Project should be implemented with Python
Please name your repository on GitHub with this name without exposing your project information: FSr3L4lxGxLqcn1e

****
Notes:
AutoML Output
Leaderboard
The AutoML object includes a “leaderboard” of models that were trained in the process, including the 5-fold cross-validated model performance (by default). The number of folds used in the model evaluation process can be adjusted using the nfolds parameter. If you would like to score the models on a specific dataset, you can specify the leaderboard_frame argument in the AutoML run, and then the leaderboard will show scores on that dataset instead.
With H2O we can get the Bonus

**********************************************************************************************************


 1)My problem is a clasification problem binary subscribe Yes or No? 
    Another survey could be -> Potencial client YES or NO?

 1_a) finding customers who are more likely to buy the investment product. Determine the segment(s) of customers our client should prioritize.
 1_b) What makes the customers buy? Tell us which feature we should be focusing more on.

********
 2)Steps in every DS Project
    	A)How do you know the most important fatures?
    		1)Ask your client about features don't try to guess as much as You undersatnd the problem the better approach you can use 
		to solve it. 
		2)You can of course do graphical Analysis EDA to see what features has more weight related with and output parameter
		

    	B)Check if We have Imbalance Classes How to sampling better. We can use SMOTE 
      
    	C) Types of Clasification to solve this problem?
           	1)Logistic Regression
		2)Decision Tree
		3)Random Forest
	   
	D)How to evade Overfitting? With Cross Validation

