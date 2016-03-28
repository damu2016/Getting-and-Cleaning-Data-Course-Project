# Getting and Cleaning Data project - Assignment 2

##This file describes the variables, the data, and any transformations or work that I have performed to clean up the data.

###Data Source

This dataset is derived from the "Human Activity Recognition Using Smartphones Data Set" which was originally made avaiable here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Link to download data:
      https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
      
###Run_analysis.R performs the following to clean up the data:

1. Merges the training and test data sets to one data set
2. Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement.
3. Reads activity_labels.txt and applies descriptive activity names to name the activities in the data set:
+ walking
+ walkingupstairs
+ walkingdownstairs
+ sitting
+ standing
+ laying



4. These signals were used to estimate variables of the feature vector for each pattern:


+ tBodyAcc-XYZ
+ tGravityAcc-XYZ
+ tBodyAccJerk-XYZ
+ tBodyGyro-XYZ
+ tBodyGyroJerk-XYZ
+ tBodyAccMag
+ tGravityAccMag
+ tBodyAccJerkMag
+ tBodyGyroMag
+ tBodyGyroJerkMag
+ fBodyAcc-XYZ
+ fBodyAccJerk-XYZ
+ fBodyGyro-XYZ
+ fBodyAccMag
+ fBodyAccJerkMag
+ fBodyGyroMag
+ fBodyGyroJerkMag

5. The set of variables that were estimated from these signals are:

+ mean(): Mean value
+ std(): Standard deviation

6. Ceates a second independent tidy data set with the average of each measurement for each activity and each subject. The result is saved as tidy_data_set_with_averages.txt