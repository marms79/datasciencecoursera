CODE BOOK:  wearable computing dataset

VARIABLES:

<br>Subject
  <br>subject number 1-10299 (avg dataset 1-180)
<br>Activity
  <br>activity labels
  <br>LAYING
  <br>SITTING
  <br>STANDING
  <br>WALKING
  <br>WALKING_DOWNSTAIRS
  <br>WALKING_UPSTAIRS
<br>tBodyAcc-mean-X
<br>tBodyAcc-mean-Y
<br>tBodyAcc-mean-Z
<br>tBodyAcc-std-X
<br>tBodyAcc-std-Y
<br>tBodyAcc-std-Z
<br>tGravityAcc-mean-X
<br>tGravityAcc-mean-Y
<br>tGravityAcc-mean-Z
<br>tGravityAcc-std-X
<br>tGravityAcc-std-Y
<br>tGravityAcc-std-Z
<br>tBodyAccJerk-mean-X
<br>tBodyAccJerk-mean-Y
<br>tBodyAccJerk-mean-Z
<br>tBodyAccJerk-std-X
<br>tBodyAccJerk-std-Y
<br>tBodyAccJerk-std-Z
<br>tBodyGyro-mean-X
<br>tBodyGyro-mean-Y
<br>tBodyGyro-mean-Z
<br>tBodyGyro-std-X
<br>tBodyGyro-std-Y
<br>tBodyGyro-std-Z
<br>tBodyGyroJerk-mean-X
<br>tBodyGyroJerk-mean-Y
<br>tBodyGyroJerk-mean-Z
<br>tBodyGyroJerk-std-X
<br>tBodyGyroJerk-std-Y
<br>tBodyGyroJerk-std-Z
<br>tBodyAccMag-mean
<br>tBodyAccMag-std
<br>tGravityAccMag-mean
<br>tGravityAccMag-std
<br>tBodyAccJerkMag-mean
<br>tBodyAccJerkMag-std
<br>tBodyGyroMag-mean
<br>tBodyGyroMag-std
<br>tBodyGyroJerkMag-mean
<br>tBodyGyroJerkMag-std
<br>fBodyAcc-mean-X
<br>fBodyAcc-mean-Y
<br>fBodyAcc-mean-Z
<br>fBodyAcc-std-X
<br>fBodyAcc-std-Y
<br>fBodyAcc-std-Z
<br>fBodyAccJerk-mean-X
<br>fBodyAccJerk-mean-Y
<br>fBodyAccJerk-mean-Z
<br>fBodyAccJerk-std-X
<br>fBodyAccJerk-std-Y
<br>fBodyAccJerk-std-Z
<br>fBodyGyro-mean-X
<br>fBodyGyro-mean-Y
<br>fBodyGyro-mean-Z
<br>fBodyGyro-std-X
<br>fBodyGyro-std-Y
<br>fBodyGyro-std-Z
<br>fBodyAccMag-mean
<br>fBodyAccMag-std
<br>fBodyBodyAccJerkMag-mean
<br>fBodyBodyAccJerkMag-std
<br>fBodyBodyGyroMag-mean
<br>fBodyBodyGyroMag-std
<br>fBodyBodyGyroJerkMag-mean
<br>fBodyBodyGyroJerkMag-std
<br>
DATA:

<br>  The signals were used to estimate variables of the feature vector for each pattern:
  '-XYZ' is used to denote 3-axial signals in the X, Y and Z directions:
            <br>tbodyacc-xyz
            <br>tgravityacc-xyz
            <br>tbodyaccjerk-xyz
            <br>tbodygyro-xyz
            <br>tbodygyrojerk-xyz
            <br>tbodyaccmag
            <br>tgravityaccmag
            <br>tbodyaccjerkmag
            <br>tbodygyromag
            <br>tbodygyrojerkmag
            <br>fbodyacc-xyz
            <br>fbodyaccjerk-xyz
            <br>fbodygyro-xyz
            <br>fbodyaccmag
            <br>fbodyaccjerkmag
            <br>fbodygyromag
            <br>fbodygyrojerkmag
<br>
The set of variables that were estimated from these signals are:
  <br>mean: Mean value
  <br>std: Standard deviation


TRANSFORMATIONS:

  <br>All the values are means, aggregated over 30 subjects and 6 activities, with the resulting dataset being 180 rows by 68 columns.



