# test-repo
For training only


# Getting and Cleaning Data Course Project


```
```

## See below code description:

1. Download the file, put it in the data folder. Unzip files to UCI HAR folder. 

2. The following files are used to load the data:
    test/subject_test.txt
    test/X_test.txt
    test/y_test.txt
    train/subject_train.txt
    train/X_train.txt
    train/y_train.txt

3. From 2 sets of the data (test and training) we create one   
   resulting data set.
   
4. The following variables were used as part of descriptive 
   variable names for data in data frame:
      Activity
      Subject
      Features
      
5. Read data from X, Y, subject test and train txt files to the 
   variables.
   
6. Concatunate migrating the training and test data tables by row 
   and getting 3 data tables:
   dataSubject 
   dataActivity
   dataFeatures
   
7. Merge columns of 3 data tables to get data frame Data.

8. Subset Name of Features by measurements on the mean and 
   standard deviation.
   
9. Subset the data frame Data by seleted names of Features. 
   
10.Names of Feteatures are labelled using descriptive variable 
   names as shown below:
   
    prefix t is replaced by time
    Acc is replaced by Accelerometer
    Gyro is replaced by Gyroscope
    prefix f is replaced by frequency
    Mag is replaced by Magnitude
    BodyBody is replaced by Body

11.Tidy data set is created with the average of each variable for
   each activity and each subject based on the data created in the
   previous step. 


