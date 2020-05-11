# <img src="pics/facebook_logo.png" width="100"> Facebook_Predicting_Check_Ins

##  Predict which place a person would like to check in to.


### * Data info:
We are going to predict which business a user is checking into based on their location, accuracy, and timestamp. The train and test dataset are split based on time, and the public/private leaderboard in the test data are split randomly. There is no concept of a person in this dataset. All the row_id's are events, not people. 

#### File descriptions
train.csv, test.csv 
row_id: id of the check-in event
x y: coordinates
accuracy: location accuracy 
time: timestamp
place_id: id of the business, this is the target you are predicting
sample_submission.csv - a sample submission file in the correct format with random predictions
<img src="pics/data_glimsp.png" width="800"> 

### * Navigating through the repository:

#### [1. A Quick Knn baseline](https://github.com/paxton615/facebook_predicting_checkins/blob/master/facebook_predicting_check_ins.ipynb)

#### [2.improvement and better results]()


### * Aims:

#### 1. Practice the whole process from EDA to score
#### 2. dig deep in improving the scores



