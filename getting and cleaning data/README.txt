This file describes how run_analysis.R script works.

 Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".

Second, use source("run_analysis.R") command in R.

Third, there will be two output files which are generated in the current working directory:
merged_data.txt (7.9 Mb): it contains a data frame called cleanedData with 10299*68 dimension.
data_with_means.txt (220 Kb): it contains a data frame called result with 180*68 dimension.

Finally, use data <- read.table("data_with_means.txt") command in R to read the file. 