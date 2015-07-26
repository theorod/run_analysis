# run_analysis
Getting and Cleaning Data Course Project
The R script including in this repository does the following:
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

We first download the data from the zip file given in the description of the course project
Unzip the files and get the files
We use those data to read them and then to find the properties on those data in order to create the tidy data. We do this by using str function
We merge the data to get the data frame for all the data
Find and extract the mean and sd for each measurement .
Finally we use the plyr package.
independent tidy data set will be created with the average of each variable for each activity and each subject based on the data set before.

