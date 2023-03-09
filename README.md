# MARS
## Overview of Project 
This project requires the scraping of two websites relating to Mars.  The first portion requires the scraping of a website to extract the title and text from news articles regarding Mars.  The second portion requires scraping a page with atmospheric data from Mars sent by the Curiosity rover and then analyzing that data.

## Resources
Data Sources:  https://redplanetscience.com & https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html
Sotware: Splinter, Beautiful Soup, NumPy, Pandas, Jupyter Notebook

## Results
### Challenge 1
Used Splinter, the website was accessed and used BeatifulSoup to scrape the site.  Parsed the information to create a list of dictionaries for the titles and text of articles about Mars.  Finally, exported the data to a JSON file.

### Challenge 2
Used Splinter, the website was accessed and used BeatifulSoup to scrape the site.   Parsed the information to create a data frame of 1867 Earth days worth of atmospheric information.  Converted the data to the proper data types for analysis.  Determined the number of months and days worth of information from the Curiosity rover as well as the average temperature and pressure on Mars.  Then, created bar charts for average temperature and another for average pressure  per month.  Created a chart to help determine about how many days there are in a Martian year by estimating when the temperature pattern repeats.  Finally, exported the data to a CSV file.
![Average Temperature](https://github.com/BlazeMedina/Mars/blob/main/Avg_temp.png)
![Average Pressure](https://github.com/BlazeMedina/Mars/blob/main/Avg_pressure.png)

![Martian Temperature compared to Terrestrial Date](https://github.com/BlazeMedina/Mars/blob/main/Martian_temperature.png)
## Summary
* On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!
* Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
* The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
