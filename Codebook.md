The run analysis file is created using the following logic:

1- Download the dataset from the following URL --  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2- Unzips the file
3- Creates results folder if it does not exist (all files are stored in this folder)
4- Load the text file features.txt used for columns
5- Loads X_train.txt, y_train.txt, subject_train.txt
6- X_train contains the data using the feature data set as columns
7- y_train contains the activity labels
8- subject_train contains the ids
9- loads and appends test dataset using X_test.txt, y_test.txt, subject_test.txt
10- X_test contains the data using the feature data set as columns
11- y_test contains the activity labels
12- Subject_test contains the ids
13- Appends train and test data
14- Rearrange the data using id
15- Loads activity_labels.txt
16- Changes the data activity row to use the activity labels
17- Saves the mean and std into mean_and_std.csv
18- Saves the tidy dataset into tidy_dataset.csv
