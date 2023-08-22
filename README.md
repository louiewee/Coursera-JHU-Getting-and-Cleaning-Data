# Coursera: Getting and Cleaning Data Assignment (Week 4)

This repository is for the peer-graded assignment of the "Getting and Cleaning Data" course from the Data Science Specialization offered by the John Hopkins University through Coursera. 

The course is taught by the following instructors: 
  - Jeff Leek, PhD
  - Roger D. Peng, PhD
  - Brian Caffo, PhD

[`CodeBook.rmd`](https://github.com/louiewee/getcleandata/blob/main/CodeBook.md) describes the variables, the data, and any transformations or work that was performed to clean up the data present in the codebook.

[`run_analysis.R`](https://github.com/stormrinz/getting-and-cleaning-data-UCI-HAR/blob/main/run_analysis.R) contains all the code to perform the analyses described in the 5 steps in the codebook. It can be run in RStudio along with the data present in the same folder, un-compressed and without names altered.

> 1. Merges the training and the test sets to create one data set.
> 2. Extracts only the measurements on the mean and standard deviation for each measurement. 
> 3. Uses descriptive activity names to name the activities in the data set
> 4. Appropriately labels the data set with descriptive variable names. 
> 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

#### [`tidy_data.txt`](https://github.com/stormrinz/getting-and-cleaning-data-UCI-HAR/blob/main/tidy.txt) is the output of the final step.
