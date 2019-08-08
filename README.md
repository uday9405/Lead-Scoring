# Lead-Scoring

## Problem Statement

• X Education sells online courses to industry professionals. On any given day,
many professionals who are interested in the courses land on their website
and browse for courses.

• The typical lead conversion rate at X education is around 30%.

• The company wishes to identify the most potential leads, also known as ‘Hot
Leads’.

• If they successfully identify this set of leads, the lead conversion rate should
go up as the sales team will now be focusing more on communicating with the
potential leads rather than making calls to everyone.

• Our objective is to build a model wherein we need to assign a lead score to
each of the leads such that the customers with higher lead score have a higher
conversion chance and the customers with lower lead score have a lower
conversion chance.

## Solution

• Built a Logistic Regression model using StatsModels.Api library on the dataset.

• Used RFE of Scikit-Learn to select top 20 features for training the model.

• Achieved a precision of 80%
