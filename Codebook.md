## CODEBOOK For JHS Week 4 Project Data Cleaning
## Author Rod Jones
## Describing the variables, the data, and transformations for clean data 

## First Downloading Files

Download data from the link below and unzip it into working directory of R Studio.
Execute the R script.
The data was provided by the Peer-graded Assignment: Getting and Cleaning Data Course Project
The source data came from the Human Activity Recognition Using Smartphones Data Set. 

About R script
File with R code "run_analysis.R" performs the 5 following steps (in accordance assigned task of course work):

## Second Reading Files

Reading in the files and merging the training and the test sets to create one data set.
Reading trainings tables
Reading testing tables
Reading feature vector
Reading activity labels
Assigning variable names

## Third Merging All Data Together

Extracting only the measurements on the mean and standard deviation for each measurement
Reading variable names
Create vector for defining ID, mean and standard deviation
Making nessesary subset from merged data set

## Fourth Creating a Second tidyData set

Creating a second, independent tidy data set for each activity and each subject
Making second tidyData set
Write second tidy data set in txt file

## Overall
The variables in the new tidyData contains 180 rows and 68 columns. 
Each row has averaged variables for each subject and each activity.                        
