The run_analysis.R script prepares data by following the 5 steps described in the final stage of this course.

Step 1. Dataset is downloaded under the 'File.zip' file, from which a folder called UCI HAR Dataset is extracted.

Step 2. Each dataset is assigned to a different, custom variable

Step 3. 'training' and 'test' sets are merged to create a single dataset ('MergedData')

Step 4. 'CleanData' is created to specifically extract mean and S.Dev

Step 5. Descriptive activity names are used to name the activities in the data set

Step 6. Existing variable names are replaced with more appropriate lables

Step 7. A second, independent tidy data set is created and exported, which includes the average of each variable for each activity and each subject