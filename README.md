# Getting-Cleaning_Data_Project

We must create a file that:
  
    *Merges the training and the test sets to create one data set.
    *Extracts only the measurements on the mean and standard deviation for each measurement.
    *Uses descriptive activity names to name the activities in the data set
    *Appropriately labels the data set with descriptive activity names.
    *Creates a second, independent tidy data set with the average of each variable for each activity and each subject.


For this we will need to:

   1. Download the data source and put into a folder on your local drive.
   2. Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory
   3. After running the script Run_Analysis.R it should generate a new file tiny_data.txt in your working directory.

Note that Run_Analysis.R depends on the libraries reshape2 and data.table being installed in R.
