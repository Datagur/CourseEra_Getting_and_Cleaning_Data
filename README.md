Getting and Cleaning Data: Course Project
=========================================

Introduction
------------

This repository contains the course project for the "Getting and Cleaning data" course. 

About the raw data
------------------

The features (561 of them) are unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file.

The same holds for the training set.

About the script and the tidy dataset
-------------------------------------

'run_analysis.R' which will merge the test and training sets together.

the UCI HAR Dataset must be extracted and..
the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only data for mean and standard deviation are maintained

The script will create a tidy data set with means of all the columns per test subject and per activity. 
This tidy dataset will be written to a tab-delimited file called tidyData.txt, which can also be found in this repository.

About the Code Book
-------------------

The CodeBook.md file explains the transformations used, resulting data and variables.
