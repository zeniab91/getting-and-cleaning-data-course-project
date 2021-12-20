# getting-and-cleaning-data-course-project
Course project for Coursera's Getting and Cleaning Data class

This project is for the Coursera Getting and Cleaning Data class to perform an analysis on the "Human Activity Recognition Using Smartphones" dataset (http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones); the goal is to output a tidy dataset.


Before running the run_analysis.R script, please follow these steps:

1) Download the zip file from this URL: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
2) Unzip the file.
3) Move the below files and the run_analysis.R script to your working directory:

- features.txt
- subject_train.txt
- subject_test.txt
- X_train.txt
- X_test.txt
- y_train.txt
- y_test.txt

4) Install the reshape2 package using install.packages("reshape2").

Once those steps are complete, you can run the R script (run_analysis.R).

The run_analysis.R script will output a tidy data set, named tidy.csv.
