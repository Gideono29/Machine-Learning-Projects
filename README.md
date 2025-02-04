# Machine-Learning-Projects
Data Preprocessing and visualization in Machine Learning

Covid Test problem 
1.1 Task 1 
Read the data set provided on the Github Repository called covid_tests.csv.
Github Repo Link
1.2 Task 2 
• Visualize the first three rows of the data set to gain an initial understanding of the structure
and contents of the data set.
• Classify the data into two data types: numerical and categorical.
1.3 Task 3 
• Remove the columns BATCHDATE, HTN, CHD, SWABTYPE and TESTNAME. (Note: the col-
umn names may differ slightly in the dataset; be sure to use the exact names as
they appear.)
• Check for missing values by identifying null values in each column. For each column, state
the number of null values found in the dataset, as this will help determine the necessary
data cleaning steps.
Assignment 2 Data Loading and Organization Page 1
• After identifying the null values, proceed with the following:
– For the columns HIGHRISKEXPOSUREOCCUPATION and COUGH, remove any rows
that contain null values. Verify that no more null values exist for the 2 columns,
provide proof, and make use of a screenshot.
– For CATEGORICAL data, remove all rows with null values. Verify that no more null
values exist with a screenshot.
– For NUMERICAL data, calculate the mean and use it to replace any null values.
1.4 Task 4 
Apply label encoding to the Result column in the dataset by converting POSITIVE to 1
and NEGATIVE to 0.
Save the updated dataset with name df_updated. Answer all following questions using
the updated dataset.
1.5 Task 5 
Now, visualize the distribution of the AGE, PULSE, HIGHRISKINTERACTIONS, SMOKER
and TEMPERATURE columns using both a histogram and a box plot. If categorical
data, plot a histogram only.
For each plot:
– Use a histogram to display the frequency distribution of values within each column.
This will allow you to observe how the values are spread across different ranges and
identify any patterns.
– Use a box plot to summarize the distribution of each column. The box plot will show
the median, quartiles, and any potential outliers.
For graduate students, histograms for numerical features should also include a smooth
curve, usually called a density plot. Plot histogram and density plot on the same axis.
Add appropriate labels for the x-axis and y-axis and provide a descriptive title for
each plot. This will make the plots easier to interpret and understand
