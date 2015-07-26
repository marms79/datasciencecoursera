Getting and cleaning data course project

About creating a tidy data set of wearable computing data which initially came from from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Files in this repo

README.md -- this file, which describes how my script works
CodeBook.md -- codebook describing all the variables, the data and transformations
run_analysis.R -- the R code used

run_analysis.R goals

You should create one R script called run_analysis.R that does the following. 

    1) Merges the training and the test sets to create one data set.
    2) Extracts only the measurements on the mean and standard deviation for each measurement. 
    3) Uses descriptive activity names to name the activities in the data set
    4) Appropriately labels the data set with descriptive variable names. 

    5) From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

It should run in a wd folder with Samsung data (the zip had this folder: UCI HAR Dataset) 

The output is created in working directory with the name of tidy-UCI-HAR-dataset-AVG.txt

It follows the goals for each step.

This is the process it follows:
    1) Checks to seeif the file exists, otherwise it will download it
    2) Checks to see if the file has already been extracted to the directory
    3) Loads both the test and train data sets
    4) Loads the features and activity labels to the data
    5) Extracts the mean and standard deviation column names and data
    6) Processes the data then merges and creates data set

The result is saved as "./tidy-UCI-HAR-dataset-AVG.txt", which will be a 180x68 data table (size w/out header row), where the first column contains subject IDs, the second column contains activity names, and the average for each of the 66 attributes  in columns 3...68. 
