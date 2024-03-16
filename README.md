# Google Play Store Data Cleaning and Analysis

This project focuses on cleaning and analyzing data from the Google Play Store dataset using Python and pandas. The dataset contains information about various mobile applications available on the Google Play Store, such as app names, categories, ratings, reviews, sizes, installs, prices, and more.

## Dataset Description

The dataset (`googleplaystore.csv`) includes the following columns:

1. App: Name of the application
2. Category: Category to which the app belongs
3. Rating: Rating of the app
4. Reviews: Number of reviews for the app
5. Size: Size of the app
6. Installs: Number of installs for the app
7. Type: Free or Paid
8. Price: Price of the app
9. Content Rating: Content rating of the app
10. Genres: Genres to which the app belongs
11. Last Updated: Date when the app was last updated
12. Current Ver: Current version of the app
13. Android Ver: Required Android version

## Project Overview

The project involves the following steps:

1. Data Cleaning:
   - Handling missing values
   - Cleaning column datatypes
   - Converting categorical data to the appropriate format
   - Removing duplicates
   - Cleaning and converting numerical columns
   - Analyzing and fixing invalid or inconsistent data

2. Data Analysis:
   - Analyzing the most reviewed app
   - Identifying the category with the highest number of apps
   - Finding the most expensive app and game
   - Determining the most installed finance app
   - Analyzing teen games with the most reviews
   - Finding the free game with the most reviews
   - Calculating the total transfer in tebibytes (TB) for the most installed lifestyle app

## Libraries

- pandas
- numpy
- seaborn
