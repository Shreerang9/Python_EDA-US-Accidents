# Python_EDA-US-Accidents
The above Python project focuses on exploratory data analysis of US accidents. The project involves importing necessary libraries such as pandas, numpy, matplotlib, and seaborn. It then loads the dataset from a CSV file and performs data cleaning and analysis.

Data Cleaning:

The project starts by selecting only the numeric columns from the dataset and creating a new dataframe.
Missing values are calculated and displayed as a percentage of the total dataset.
Columns with zero missing values are removed from further analysis.
Null values in the "City" column are removed, resulting in a cleaned "City" column.
The unique cities and their occurrence counts are calculated.
Top 10 Accident-Prone Cities:

The project identifies and displays the top 10 cities with the highest number of accidents.
A bar plot is created to visualize the top 10 accident-prone cities.
A histogram is plotted to show the distribution of accident counts across all cities.
Observations:

The percentage of cities with less than 100 accidents is calculated, revealing that more than 74% of cities have fewer than 100 accidents.
The project notes that data for New York is missing from the dataset.
Working with Time Data:

The "Start_Time" column is analyzed to extract useful information.
An invalid value is dropped from the "Start_Time" column.
The "Start_Time" column is converted to a datetime format.
A histogram is plotted to show the distribution of accidents by hour of the day, indicating that most accidents happen between 6 am to 9 am and 3 pm to 5 pm.
Another histogram is plotted to show the distribution of accidents by day of the week, suggesting that accidents are lower on weekends.
The distribution of accidents by month is visualized through a histogram, revealing that the number of accidents is higher in July.
Overall, the project provides insights into US accidents, including the most accident-prone cities, patterns in accident occurrence by hour, day of the week, and month. It also highlights missing data for New York.
