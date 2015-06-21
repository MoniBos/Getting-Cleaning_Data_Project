The Code Book includes the variables, data, and transformations or work that you did to clean up the data.

You can find the original data here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

And the original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

What is the data about?
 
  It about experiments with a group of 30 volunteers with ages of 19-48 years. 
  Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. 
  The experiments have been video-recorded to label the data manually. 

The files included are:
    *'README.txt'
    
    *'features_info.txt'
    
    *'features.txt'
    
    *'activity_labels.txt'
    
    *'X_train.txt'
    
    *'y_train.txt'
    
    *'X_test.txt'
    
    *'y_test.txt'
    
    *'subject_train.txt'
    
    *'total_acc_x_train.txt'
    
    *'body_acc_x_train.txt'
    
    *'body_gyro_x_train.txt'


 The Transformation:
 
    1. Merges the training and the test sets to create one data set.
    
    2. Extracts only the measurements on the mean and standard deviation for each measurement.
    
    3. Uses descriptive activity names to name the activities in the data set
    
    4. Appropriately labels the data set with descriptive activity names.
    
    5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject
