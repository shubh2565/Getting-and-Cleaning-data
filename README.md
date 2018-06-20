# Getting-and-Cleaning-data
The goal is to prepare tidy data that can be used for later analysis. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.
A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

This repository contains the following files:

* README.md, this file, which provides an overview of the data set and how it was created.
* tidy_data.txt, which contains the data set.
* CodeBook.md, the code book, which describes the contents of the data set (data, variables and transformations used to generate      the data).
* run_analysis.R, the R script that was used to create the data set

The R script called run_analysis.R does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
