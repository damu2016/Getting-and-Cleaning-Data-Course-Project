# Getting and Cleaning Data Course Project - Assignment 2

The purpose of this project is to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

1. a tidy data set
2. a link to a Github repository with run_analysis.R script for performing the analysis, and 
3.  a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. 

##Objectives

run_analysis.R performs the following:

1. Merges Training and Test data sets
2. subset the measurements on the mean and Standard Deviation 
3. Uses descriptive activity names to name the activities in the data set
4. Creates a second (merged_data.txt) and tidy data set (tidy_data_set_with_averages.txt)


## run_analysis.R

### Steps involved in the script


1. It loads the Train and Test data sets and merge the two datasets into one data frame.
2. It extracts mean and standard deviation from the features data set.
3. The three data sets, X, Y and S, are merged. Then, it is exported as a txt file named merged_data.txt
4. The mean of activities and subjects are created into a separate tidy data set named tidy_data_set_with_averages.txt.
