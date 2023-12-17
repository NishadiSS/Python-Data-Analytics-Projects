# Weather-Analytics
### BIG-DATA ANALYSIS WITH PYTHON

## The Weather Dataset
The Weather Dataset is a time series data set with per-hour information about the weather conditions at a particular location.This data is available as a CSV file.

## The commands that we used in this project :
* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.

## Questions

* Find all the unique 'Wind Speed' values in the data.
* Find the number of times when the 'Weather is exactly Clear'.
* Find the number of times when the 'Wind Speed was exactly 4 km/h'.
* Find out all the Null Values in the data.
* Rename the column name 'Weather' of the dataframe to 'Weather Condition'.
* What is the mean 'Visibility' 
* What is the Standard Deviation of 'Pressure'  in this data?
* What is the Variance of 'Relative Humidity' in this data ?
* Find all instances when 'Snow' was recorded.
* Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.
* What is the Mean value of each column against each 'Weather Condition ?
* What is the Minimum & Maximum value of each column against each 'Weather Condition ?
* Show all the Records where Weather Condition is Fog.
* Find all instances when 'Weather is Clear' or 'Visibility is above 40'.
* Find all instances when :
    * A. 'Weather is Clear' and 'Relative Humidity is greater than 50'

       or

    * 'Visibility is above 40'