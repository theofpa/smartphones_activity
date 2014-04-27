### Introduction

This repository is hosting the R code for the assignment of the DataScience track's "Getting and Cleaning Data" course which will be peer assessed.

The purpose of this project is to demonstrate the collection, work with, and cleaning of this data set. Tidy data have been prepared so can be used for later analysis.

### Data Set

The data set "Human Activity Recognition Using Smartphones" has been taken from [UCI](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

### Execution and files

The Data Set has been stored in `UCI HAR Dataset/` directory.

The `CodeBook.md` describes the variables, the data, and the work that has been performed to clean up the data.

The `run_analysis.R` is the script that has been used for this work. It can be loaded in R/Rstudio and executed without any parameters.

The result of the execution is that a `tidy.csv` file is being created, that stores the data (mean and standard deviation of each measurement per activity&subject) for later analysis.