# Surfs-Up_Challenge
Analysis of precipation and temperature in Oahu, Hawaii with SQLALchemy and SQLite.

## Resources
Data Source: [hawaii.sqlite](https://github.com/monsecc01/Surfs-Up_Challenge/blob/a78995357a4d9b76175d77a9329e9d68d0d8250e/hawaii.sqlite)
& [SurfsUp_Challenge](https://github.com/monsecc01/Surfs-Up_Challenge/blob/a78995357a4d9b76175d77a9329e9d68d0d8250e/SurfsUp_Challenge.ipynb)

Software: Python 3.9, Visual Studio Code 1.55.1, Jupyter Notebook

## Overview of the statistical analysis:

The purpose of the weather analysis is to provide temperature data for June and December in Oahu, Hawaii. We will create a database engine using SQLite, query the database we built with SQLAlchemy and provide statical analysis of the data using Pandas. Statistical analysis of data will include: mean, minimum, maximum, standard deviation, and percentiles

## Results:

Our temperature analysis of Oahu provided data for the months of June and Decmber between the years 2010 and 2017. Some key differences between the two month's data are:
* There are 1700 data points for June while there are only 1517 for December. This could mean that either there are duplicates for June or there is data missing for December. 
* The minimum for June is 64 degress while December has a minimum temp 56. This tells us there is a possibility for colder days in December, which could affect surfing activity.
* June's standard deviation is approximately 3.26 while December has a standard deviation of approximately 3.75. This shows there is slightly more fluctuation in temperatures during the month of December. 

![June_Summary](https://user-images.githubusercontent.com/81447450/119284459-5f9e4b80-bc05-11eb-8322-246e460e9969.png)
![December_Summary](https://user-images.githubusercontent.com/81447450/119284464-61680f00-bc05-11eb-8d92-9cece6237cad.png)


## Summary:

Overall, temperatures in both June and December are pretty similar. Both months have average temps in the low to mid 70's and the max temps are very close. Although the standard deviations differ by less than a degree, they are both low. The consistent warm temperatures make sense given that Hawaii has a warm climate. 

Although temperature data for June and December provides us a good understanding of the weather during those months, we need more data to get a better picture. One additional query we could create is for precipition data during those months. This could help us understand if rain could affect the business. Another query could be active stations during those months. This data could help find the most active station that possibly provides the best data. We could use that station's data to find the most reliable weather data. 


