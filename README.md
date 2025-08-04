# Task-1-Data-Cleaning-and-Preprocessing
This repository contains a data cleaning script for the Netflix Shows Dataset from Kaggle using Python and Pandas. The goal of this project is to transform raw, inconsistent data into a clean, standardized format ready for analysis or visualization.

 #Overview
The Netflix dataset includes information on TV shows and movies available on Netflix, such as title, type, cast, director, country, release year, rating, and more. This project focuses on cleaning and preprocessing this data to ensure consistency and accuracy.

#Tasks Performed

✅ Missing Values: Identified and handled null values using .isnull() and .fillna().

✅ Duplicates: Removed duplicate rows using .drop_duplicates().

✅ Standardized Text: Normalized text values (e.g., country names, ratings, type, director names).

✅ Date Format Conversion: Converted date_added column to a consistent dd-mm-yyyy format using pd.to_datetime().

✅ Column Renaming: Cleaned column names by converting them to lowercase and replacing spaces with underscores.

✅ Data Type Fixes: Ensured numeric and date columns have the correct data types (e.g., release_year as integer, duration_num as float).

