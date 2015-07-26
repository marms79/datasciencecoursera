CODE BOOK:  wearable computing dataset

VARIABLES:

Subject
  subject number 1-10299 (avg dataset 1-180)
Activity
  activity labels
    LAYING
  SITTING
  STANDING
  WALKING
  WALKING_DOWNSTAIRS
  WALKING_UPSTAIRS
tBodyAcc-mean-X
tBodyAcc-mean-Y
tBodyAcc-mean-Z
tBodyAcc-std-X
tBodyAcc-std-Y
tBodyAcc-std-Z
tGravityAcc-mean-X
tGravityAcc-mean-Y
tGravityAcc-mean-Z
tGravityAcc-std-X
tGravityAcc-std-Y
tGravityAcc-std-Z
tBodyAccJerk-mean-X
tBodyAccJerk-mean-Y
tBodyAccJerk-mean-Z
tBodyAccJerk-std-X
tBodyAccJerk-std-Y
tBodyAccJerk-std-Z
tBodyGyro-mean-X
tBodyGyro-mean-Y
tBodyGyro-mean-Z
tBodyGyro-std-X
tBodyGyro-std-Y
tBodyGyro-std-Z
tBodyGyroJerk-mean-X
tBodyGyroJerk-mean-Y
tBodyGyroJerk-mean-Z
tBodyGyroJerk-std-X
tBodyGyroJerk-std-Y
tBodyGyroJerk-std-Z
tBodyAccMag-mean
tBodyAccMag-std
tGravityAccMag-mean
tGravityAccMag-std
tBodyAccJerkMag-mean
tBodyAccJerkMag-std
tBodyGyroMag-mean
tBodyGyroMag-std
tBodyGyroJerkMag-mean
tBodyGyroJerkMag-std
fBodyAcc-mean-X
fBodyAcc-mean-Y
fBodyAcc-mean-Z
fBodyAcc-std-X
fBodyAcc-std-Y
fBodyAcc-std-Z
fBodyAccJerk-mean-X
fBodyAccJerk-mean-Y
fBodyAccJerk-mean-Z
fBodyAccJerk-std-X
fBodyAccJerk-std-Y
fBodyAccJerk-std-Z
fBodyGyro-mean-X
fBodyGyro-mean-Y
fBodyGyro-mean-Z
fBodyGyro-std-X
fBodyGyro-std-Y
fBodyGyro-std-Z
fBodyAccMag-mean
fBodyAccMag-std
fBodyBodyAccJerkMag-mean
fBodyBodyAccJerkMag-std
fBodyBodyGyroMag-mean
fBodyBodyGyroMag-std
fBodyBodyGyroJerkMag-mean
fBodyBodyGyroJerkMag-std

DATA:

  The signals were used to estimate variables of the feature vector for each pattern:
  '-XYZ' is used to denote 3-axial signals in the X, Y and Z directions:
            tbodyacc-xyz
            tgravityacc-xyz
            tbodyaccjerk-xyz
            tbodygyro-xyz
            tbodygyrojerk-xyz
            tbodyaccmag
            tgravityaccmag
            tbodyaccjerkmag
            tbodygyromag
            tbodygyrojerkmag
            fbodyacc-xyz
            fbodyaccjerk-xyz
            fbodygyro-xyz
            fbodyaccmag
            fbodyaccjerkmag
            fbodygyromag
            fbodygyrojerkmag

The set of variables that were estimated from these signals are:
  mean: Mean value
  std: Standard deviation


TRANSFORMATIONS:

  All the values are means, aggregated over 30 subjects and 6 activities, with the resulting dataset being 180 rows by 68 columns.



