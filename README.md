# Weather-dataset-Task-1-https://github.com/nagapurisatwika/Weather-dataset-Task-1-/edit/main/README.md
Task 1 - Data Cleaning & Preprocessing
About this Task: Heyy! So this is one of my tasks where I tried to clean and preprocess a dataset before using it for any ML stuff.  
I used a *Weather dataset* for this task.
What I did in this task:
1. Imported the *weather.csv* dataset using Pandas.

2. Explored the data — checked how many rows and columns it had, saw some sample values, looked at data types and missing values.

3. Handled missing values — for numeric columns, I filled them with the mean, and for text (categorical) columns, I used the mode.

4. Converted all the categorical (text) columns into numbers using *LabelEncoder*.

5. Normalized all the numerical columns using *StandardScaler* so that all numbers are on the same range.

6. Plotted boxplots to find outliers in the numeric columns.

7. Removed outliers using the *IQR method* — kept only the values that were within a reasonable range.

8. Finally printed the cleaned data and checked its new shape.

9. Plotted a final boxplot to make sure the data looked clean and fine.
    
