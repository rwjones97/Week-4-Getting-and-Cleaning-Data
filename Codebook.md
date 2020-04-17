## CODEBOOK For JHS Week 4 Project Data Cleaning
## Author Rod Jones

Downloaded and Input Files
The Data set and secondary tidyData come frm the UCI HAR Dataset provided. 
I used the following files:
[1] "activity_labels.txt"  
[2] "features.txt"                                
[3] "features_info.txt" 
[4] "README.txt"                                  
[14] "test/subject_test.txt"                       
[15] "test/X_test.txt"                             
[16] "test/y_test.txt"                             
[26] "train/subject_train.txt"                     
[27] "train/X_train.txt"                           
[28] "train/y_train.txt"   

The run_analysis script
Using R Studio Version 1.2.5033

This process was used to create the following:

-Converts the raw data into R data frame objects
-Merges training and testing data into a single files for analysis
-Appends the subject ID to the appropriate row of data
-Changes the data column names to descriptive names
-Produces a second tidy data set of activities by subject

Final Output:

Creating a second, independent tidy data set for each activity and each subject
Making second tidyData set into a txt.file 
The variables in the new tidyData contains 180 rows and 68 columns. 
Each row has averaged variables for each subject and each activity.                        

