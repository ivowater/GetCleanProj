# Getting and Cleaning Data

## Course project description

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to conduct analysis

1. Put ```run_analysis.R``` in your R working directory.
2. When you run the script it will crete a folder named "GetCleanCourseProject"
3. It will download the source data file and uzip it automatically.
4. Run ```source("run_analysis.R")```, then it will generate a new file ```tidy_data.txt``` in folder GetCleanCourseProject.

## Required libraries

```run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```. 