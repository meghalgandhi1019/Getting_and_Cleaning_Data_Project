# Data Science: Getting Data and Cleaning Data

## Project

As per requirement, You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to accomplish this tasks
# Note

You need to install and load ```reshape2``` and ```data.table``` before executing following steps. 

1. https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip Download the data source from this link and put into a folder. You'll have a ```UCI HAR Dataset``` folder. Make sure it's in your project folder.

2. Required ```run_analysis.R``` of your project should be in your main project folder with  ```UCI HAR Dataset```. Necessary step after this is setting up your working direcory. It can be done by two ways:  Session toolbar from R-Studio OR you can do it by using  ```setwd()``` function.

3. Open and run ```source("run_analysis.R")```, ```required_tidydata.txt``` will be generated in your working directory as output of your project.

