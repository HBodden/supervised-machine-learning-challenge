# supervised-machine-learning-challenge

Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

The task at hand is to use bank lending data to create machine learning models to classify (Logistics Regression and Random Forest Classifie) the risk level of given loans. Specifically, compare the Logistic Regression model and Random Forest Classifier.

Part one predict which model will perform better?
I think the Random Forrest will perform better as it will breakdown the data into smaller elements and as each smaller element is assessed a much stronger/accurate classifier will be generated. Logisitics Regression simply creates a line spearating the data and uses probability to determine which side of the line the data will fall.   

Part 2 conclusion:
Both models appear to have performed the same on the data set. The Random Forrest classifier fit a little better than the Logisitcs Regression model, looking at 3 decimal places over. I believe the perfromance of each model was similar because there were only two types of loan status (1/0).  Since this model provides infomration on loan health I beleive the recall of the Log Regression model is sufficient for it to be used with a fairly high level of confidence.  

Files: 
lending_data.csv
Credit Risk Evaluator.ipynb