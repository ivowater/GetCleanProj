# Getting and Cleaning Data

## Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to conduct the analysis


1. Put ```run_analysis.R``` in your R working directory.
2. Run ```source("run_analysis.R")```, it will create a folder in your R working directory named GetCleanCourseProject.
3. The script will then download and unzip the dataset. 
4. Then it will generate a new file ```tidy_data.txt``` in GetCleanCourseProject directory.

## Libraries

```run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```. 
