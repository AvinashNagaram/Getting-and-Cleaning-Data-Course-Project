The codebook for creating the tidy dataset

General info
You can read in the tidy data set tidy_data.txt into R via read.table("tidy.txt"). 

How the data are transformed by the script:

The data are read in and modified for processing
features, concentrating on standard deviations and means are defined
Only the data relevant for the standard deviations and means are read in to safe memory.
Perform above steps to create train and test data
Transform activity names into factors.
Reshape the data so that subjects and activities become a variables of two independent columns.
Finally save the data.
