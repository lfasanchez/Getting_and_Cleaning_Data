
Getting and Cleaning Data - Course Project

* This is the course project for the Getting and Cleaning Data Coursera course.
* The included R script, `run_analysis.R`, conducts the following:


1. Download the dataset from: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
3. Load the data feature, activity info and extract columns named 'mean'(`-mean`) and 'standard'(`-std`).
   Also, rename column names to a more descriptive ones. (`-mean` to `Mean`, `-std` to `Std`, and remove symbols: `-`, `(`, `)`)
4. Then, Extract data by selected columns, and merge x, y(activity) and subject data.

5. After this, generate the 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity.
   The result of this exercise is shown in the file `tidy_dataset.txt`.