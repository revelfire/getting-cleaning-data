# Coursera Data Cleaning Module Peer Review Submission

## Quickstart
To quickly run the code navigate to the correct folder where you have pulled these
sources, e.g.
```
setwd("/Users/chris/coursera/data-cleaning/submission/")
```
and paste in the entire run_analysis.R file.

Alternatively you can navigate to it in the Files panel in R-Studio, click on
run_analysis.R, select all (cmd+A or ctrl+A for osx/windows) and click "Run"

## Dataset Analysis
I committed the dataset to my github for the exercise, not seeing much value
in writing the download and extract code as that seems ancillary to the goal
of the exercise.

The run_analysis.R is self-contained and documented inline. It can be copy-pasted
into the R console and ran end to end, no other files required. It will do the following...

## Merge
The training and the test sets to create one data set.

## Extract
The appropriate measurements on the mean and standard deviation for each measurement.

## Name
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.

## Average
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Write the File
It will output a file averages_per_subject_per_activity.txt which, if desired,
can be loaded back in using:
```
tidy_output <- read.table("averages_per_subject_per_activity.txt")
```
and inspected.

## Final Note
Unsure what they meant by "codebook" vs. well documented code, you will find Codebook.rmd
in the same folder with pretty much the same content just formatted for markdown.
