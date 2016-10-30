# Getting-and-Cleaning-Data-Course-Project
Week 4 Project Results

How the script works:

Set the working directory to include “UCI HAR Dataset” from here:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Merge the training sets (X_train.txt, Y_train.txt and subject_train.txt).
Merge the testing sets (X_test.txt, Y_test.txt and subject_test.txt).
Add activity labels (activity_labels.txt).
Read, replace and add feature names (features.txt).
Merge new training and testing sets.

Isolate mean and std. dev.

Eliminate irrelevant columns from new merged set. Save to a new Merged_Set.
Append activity and subject columns to Merged_Set.
Create and name the new tidy set (Tidy_Set).
