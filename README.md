# Demographic Data Analyzer :chart_with_upwards_trend:

This is the boilerplate for the Demographic Data Analyzer project. The goal of this project is to analyze demographic data using Python and Pandas.

## About the Project :bar_chart:

The dataset contains demographic information such as age, workclass, education, race, gender, etc. The dataset is analyzed to answer the following questions:

1. How many people of each race are represented in this dataset? This should be a Pandas series with race names as the index labels. (race column)
2. What is the average age of men?
3. What is the percentage of people who have a Bachelor's degree?
4. What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
5. What percentage of people without advanced education make more than 50K?
6. What is the minimum number of hours a person works per week?
7. What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
8. What country has the highest percentage of people that earn >50K and what is that percentage?
9. Identify the most popular occupation for those who earn >50K in India.

## Technologies :computer:

* Python
* Pandas

## Getting Started :rocket:

To get started with this project, you will need to have Python and Pandas installed on your computer. Youcan install them by following the instructions on their respective websites.

Once you have Python and Pandas installed, you can clone this repository and run the `demographic_data_analyzer.py` script to answer the questions above.

## Results :chart_with_downwards_trend:

The analysis of the demographic data yielded the following results:

1. The Pandas series with the number of people of each race represented in the dataset is as follows:
   ````
   Amer-Indian-Eskimo    311
   Asian-Pac-Islander    1039
   Black                 3124
   Other                 271
   White                27816
   Name: race, dtype: int64
   ```
2. The average age of men is approximately 39 years old.
3. The percentage of people who have a Bachelor's degree is approximately 16.45%.
4. Approximately 46.54% of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K.
5. Approximately 17.37% of people without advanced education make more than 50K.
6. The minimum number of hours a person works per week is 1 hour.
7. Approximately 25% of the people who work the minimum number of hours per week have a salary of more than 50K.
8. The country with the highest percentage of people who earn >50K is Iran, with a percentage of approximately 41.9%. 
9. The most popular occupation for those who earn >50K in India is Prof-specialty.

## Conclusion :bar_chart:

In conclusion, this project demonstrates how Python and Pandas can be used to analyze demographic data and answer various questions. The analysis of the dataset provides insights into the representation of different races in the dataset, the average age of men, the percentage of people with a Bachelor's degree, and other interesting statistics.
