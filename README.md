#Report

Predicting Load Eligibility 


In this project of Loan Prediction we are trying to analyse our customers and trying to predict which cutomer has the imence need of loan.So basically we are trying to reach out to the right people at the right time.

examples:-
- If a person who is studying in college, is hardly earning through part time jobs will be in emence need of money will have high probability that he will take loan from us.
- A newly wed couples in search of housing and car will have high probability of taking loan from us.
- etc


In this model building we have two data sets one is the train data other is the test data,Train data is the data which will be used feed the model and test data is the data on which the predictive model will be tested.


Steps used in the above model 
- Data Cleaning and Preprocessing(filling the missing values using mean and median)
- splitting the data into the x (23 independent attributes) and y(1 dependent attributes)
- The dependant attribute is a binary class with value y and n (where 'y' indicates that person is highly elligible to get the laon whereas 'n' indicates that the person has a very low probability of wanting to get a loan).
- Model Building (using Logistic Regression)
