# olympic-medal-prediction

Project Steps
1.	Form a hypothesis.
2.	Find and explore the data.
3.	(If necessary) Reshape the data to predict your target.
4.	Clean the data for ML.
5.	Pick an error metric.
6.	Split your data.
7.	Train a model.

Step 1:- Form a hypothesis.

Hypothesis in a ststement that we prove or disprove using data.
Statement:--We can predict how many medals a country will win at the Olympics by using historical data.

Step 2:- Find and explore the data.

We'll be using data from the Olympics, which was originally on Kaggle.
You can download the files we'll use in this project here:
•	teams.csv - the team-level data that we use in this project. we can use data from the summer olympics this data set contains more than 2000 rows . where each row is a single country in a single olympic game
•	athlete_events.csv - this is the original athlete-level data.

step 3:-reshape the data to predict your target:-

once we have the data we need to reshape it to make machine learning predictions  
possible in this case we don't need to do a lot of reshaping since what we're going to predict is the  
final column the metals column and we're going to use the athletes and previous metals columns to do  
that so our data is already in the form it needs to be.

step 4:-cleaning the data :-

involves making sure that our data is ready for machine learning in this case a lot of our data contains missing values so  
if you look at the previous metals column for some teams we can't actually find a value for  
previous metals and that's because that team did not compete in the previous olympics
machine learning algorithms cannot work with missing data  
so our fourth step is we're going to need to clean the data to handle those missing values.

step5:-- error matric:-

subtracting the the predictions from the actual values and then after  add up  
all of the error values and then we divide by the total number of predictions we made and that gives  us what's called the mean absolute error
 
Step 6:--split the data in training and test sets:-

splitting the data so we need to split the data  
because we want to train on one part of the data and make predictions on another part of the data  
and the reason  we want to do is give the algorithm a new set of data that it hasn't been trained  
on to make predictions on and that new set of data will tell us how well the algorithm  
is performing so we're going to train the algorithm on the training data and then test  
it on the test data and we'll measure the mean absolute error so how well the algorithm makes  
predictions on the test data and that will tell us if we've built the algorithm properly or not.

step 7:- actually train a model:-- linear regression model    y = ax +b

equation dictates the y-intercept and the slope of the line  
and we can use this line to predict data that we haven't trained it on
HERE we wil use bivariate analysis
us to use two predictors so  
the number of athletes a country is entered into the olympics and how many medals they got in the  
previous olympics so we're going to train a model that takes into account both of those factors
 
