# Getting-and-Cleaning-Data-Course-Project



The R script, `run_analysis.R`, does the following:

- Download the dataset in the working directory
- Load the activity and feature info
- Loads the training and test datasets. keep columns that
   reflect a mean or standard deviation
- Loads the activity and subject data for each dataset and merges the
   columns with the dataset
- Merges the two datasets
- Converts the `activity` and `subject` columns into factors
- Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is shown in the file `tidy.txt`.
