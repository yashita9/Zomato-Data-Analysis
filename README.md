# Zomato-Data-Analysis

This project analyzes restaurant data from Zomato to uncover insights into ratings, votes, restaurant types, cost for two people, and online ordering options. The analysis uses Python with libraries like Pandas, NumPy, Matplotlib, and Seaborn for data cleaning and visualization

****Data Cleaning****
Reading the Data:
Loads the dataset from a CSV file (Zomato data .csv) using Pandas.
Initial Exploration:
Uses dataframe.info() to check data types, missing values, and overall structure.
Rate Column Conversion:
A custom function handleRate() extracts the numerical rating from a string formatted as "3.5/5" and converts it to a float.

****Data Visualization:****

Count Plot for Restaurant Types:
Uses Seaborn’s countplot() to visualize the distribution of restaurant types based on the listed_in(type) column.
Line Plot for Votes by Restaurant Type:
Groups data by restaurant type, sums the votes, and plots the result to identify which types receive more votes.
Histogram for Ratings:
Displays the distribution of ratings using Matplotlib’s histogram, with customized bin sizes.
Count Plot for Approximate Cost:
Visualizes the frequency of different cost ranges for two people.
Box Plot (Online Order vs. Rate):
Examines how restaurant ratings vary between those that offer online ordering and those that don’t.
Heatmap Analysis:
Creates a pivot table summarizing the relationship between restaurant type and online ordering availability, and visualizes it with a heatmap.
