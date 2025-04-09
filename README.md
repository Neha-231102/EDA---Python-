Project Overview: Netflix Titles EDA (2021) :-
This project explores the Netflix Titles dataset from 2021 using Python to uncover insights into the content available on the platform. The analysis is done using Pandas, NumPy, Matplotlib, and Seaborn.
Libraries Used:-
pandas – for data manipulation, numpy – for numerical operations , matplotlib.pyplot & seaborn – for data visualization.
Data Loading & Preview : Loads the dataset (netflix_titles_2021.csv), Displays basic info: column names, data types, number of entries, and sample rows using .head() .
Missing Value Analysis :  Uses .isnull().sum() to count how many missing values are in each column .
Data Cleaning : Starts handling missing data by filling null values in the country column with "Not Specified" .






