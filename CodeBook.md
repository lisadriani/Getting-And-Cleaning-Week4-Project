The code: run_analysis.R tidies the data in the way that is described by the course requirement 

The instructions state that the code should : 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


This was down by: 

1. Downloading the dataset. The zip file was opened and in a folder named UCI HAR Dataset

2. Then, I assigned each data to understandable variables

3. The next step merged the datasets together so that they would be one set, creating an X variable and a Y variable out of the data sets and r binding them together. 

4. Then, as per the directions, only the mean and standard deviation was taken from each of these. 

5. the named activities then got descriptive names instead of the previous names 

6. Then, take the set from step 4 and create a final independent data set with the average of each variable for each activity. 
