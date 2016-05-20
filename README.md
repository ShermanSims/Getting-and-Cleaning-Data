# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Unzip the dataset if it hasn't already been done
3. Select mean and std. deviation features
4. Load the activity and feature info
5. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
6. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
7. Merges the two datasets and add labels
8. Converts the `activity` and `subject` columns into factors
9. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.
10. Output is placed in the file `tidy.txt`.
