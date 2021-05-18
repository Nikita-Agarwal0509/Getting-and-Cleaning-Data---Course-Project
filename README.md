# Getting-and-Cleaning-Data---Course-Project
Contains peer graded assignment of Coursera Getting and Cleaning Data Project (Week 4)

The purpose of this project is to demonstrate ability to collect, work with, and clean a data set. The goal is to prepare tidy data to be used for later analysis. Submissions required are: 1) a tidy data set , 2) a link to a Github repository to perform the analysis, and 3) a code book that describes the variables, data, and any transformations or work performed to clean up the data called CodeBook.md. README.md included in the repo with scripts. 

One of the most exciting areas in all of data science right now is wearable computing. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

R script run_analysis.R does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
#In the run_analysis.R script, were recreated each step.

This file 'run_analysis.R' contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

**# About R Script**

File with R code "run_analysis.R" perform 5 following steps:

*Merging the training and the test sets to create one data set.
1.1 Reading files
1.1.1 Reading trainings tables
1.1.2 Reading testing tables
1.1.3 Reading feature vector
1.1.4 Reading activity labels
1.2 Assigning column names
1.3 Merging all data in one set
Extracting only the measurements on the mean and standard deviation for each measurement
2.1 Reading column names
2.2 Create vector for defining ID, mean and standard deviation
2.3 Making nessesary subset from setAllInOne
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive variable names
Creating a second, independent tidy data set with the average of each variable for each activity and each subject
5.1 Making second tidy data set
5.2 Writing second tidy data set in txt file*


