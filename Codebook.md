This code book summarises the data fields in 'TidyData.txt'  
  
# Identifiers  
'subject' - the ID of the test subject (Test, Train)  
'Activity_Label' - the activity that was performed  
  
# Activity Labels  
'WALKING' (value '1'): subject walked during test  
'WAKLING_UPSTAIRS' (value '2'): subject walked upstairs during test  
'WALKING_DOWNSTAIRS' (value '3'): subject walked downstairs during test  
'SITTING' (value '4'): subject was sitting during test  
'STANDING' (value '5'): subject was standing during test  
'LAYING' (value '6'): subject was laying during test  
  
# Description of abbreviations:  
t represents time measurements  
f represents frequency measurements  
Body = body movement  
Gravity = acceleration of gravity  
Acc = accelerometer measurement  
Gyro = gyroscopic measurements  
Jerk = sudden movement acceleration  
Mag = magnitude of movement  
'-XYZ' is used to denoted 3-axial signals in directions X, Y and Z.  
  
# Measurements  
tBodyAcc-XYZ  
tGravityAcc-XYZ  
tBodyAccJerk-XYZ  
tBodyGyro-XYZ  
tBodyGyroJerk-XYZ  
tBodyAccMag  
tGravityAccMag  
tBodyAccJerkMag  
tBodyGyroMag  
tBodyGyroJerkMag  
fBodyAcc-XYZ  
fBodyAccJerk-XYZ  
fBodyGyro-XYZ  
fBodyAccMag  
fBodyAccJerkMag  
fBodyGyroMag  
fBodyGyroJerkMag  
  
  
The set of variables were estimated from:  
mean(): mean value  
std(): standard deviation  
  
# Variable List for run_analysis.R  
actv_labels:  
- To store data of activity_labels.txt  
  
features:  
- To store data of features.txt  
  
xTrain:  
- To store data of X_train.txt  
  
yTrain:  
- To store data of Y_train.txt  
  
subTrain:  
- To store data of subject_train.txt  
  
xTest:  
- To store data of X_test.txt  
  
yTest:  
- To store data of Y_test.txt  
  
subTest:  
- To store data of subject_test.txt  
  
extract_features:  
- to store extracted features data containing mean or std  
  
testData:  
- Data combining subTest,xTest and yTest  
  
trainData:  
- Data combining subTrain,xTrain and yTrain  
  
mergeData:  
-Data merged for testData and trainData  
  
cleanData:  
- Tidy Data set  
  