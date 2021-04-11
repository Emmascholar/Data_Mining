# Time_series Forecast
From my analysis it shows that the festive period recorded much sales and there was a peak sales during 19pm and 11am. 
## Handling Missing Value
### I used SimpleImputer and InterativeImputer to handle my missing data. no data was lost during the handling and when i try to fill it i noticed in order_date the sales personnel recorded Order Date string as a date thus making the data dirty, so i had to replace the string with a NaN value and then imputed the missing value.

### libraries used
* Pandas
* Matplotlib
* datetime
* Numpy
* sklearn
