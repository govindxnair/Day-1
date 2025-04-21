#Day 1
First we load the python library required ie pandas.
Then we load the csv file and make a copy so as to not make any changes in the original file.
Then we checks for any null values and since there are some null values , we drops all those null values.
We then fill the empty cells in the director column with the word "Unknown".
Finally we again confirm for any further null values.
We check for any duplicate rows, which is 0.
We then take the country count by converting comma-separated country names into lists and then removing the spaces from before and after the country names and finally taking the count of each country.
We Standarise the values in the column named country and converted to upper case.
We convert the "Date Added" column to datetime datatype and converting to date/month/year.
We finally check the datatypes of each column and rename the column headers to be clean.
We can also group values by movie and tv show(if needed and the code is provided).
Finally we can save the cleaned excel to a new csv file named "netflix_titles_cleaned.csv".
