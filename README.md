# HTML-Mars_data
Deliverable 1: Scrape titles and preview text from Mars news articles.  Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


Analyze your dataset by using Pandas functions to answer the following questions:

1.	How many months exist on Mars?
There are 12 Martian months, similar to Earth.



2.	How many Martian (and not Earth) days worth of data exist in the scraped dataset?
Number of unique Martian days (sols): 1867

3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * Find the average the minimum daily temperature for all of the months.
    * Plot the results as a bar chart.
The coldest month is Month 3, with an average minimum temperature of -83.31°C
The hottest month is Month 8 with an average minimum temperature of -68.38°C.

4.	Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * Find the average the daily atmospheric pressure of all the months.
    * Plot the results as a bar chart.

The lowest pressure of all Martian year is Month 6 with an average minimum pressure of 745.05
The highest pressure of all Martian year is Month 9 with an average maximum pressure of 913.31

5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    * Visually estimate the result by plotting the daily minimum temperature.

Visually by exploring the chart we can say that Martian year is a little bit shorter than 2 Earth years

1 Martian day is 24 hours, 37 minutes and 22 seconds long according to NASA. 
It is almost the same duration as an earth day(24h). 
But what about Martian year? in a Martian year there are 687 days according to the Wikipedia.

Also we can calculate it manually, as difference in days between two nearest peaks or two nearest trough on our graph, My manual calculations says that:
The difference between 2014-10-30 and 2016-09-26 is 697 days(two nearest peaks).
The difference between 2014-01-15 and 2015-12-02 is 686 days(two nearest trough)
This is not as precise as the theoretical calculation, but it is close
Also we can say that 
 Mars may not offer the warmth of a tropical island, like Hawaii, we can see that this planet is pretty cold with year bounce from -68 to -83oC . Also normal atmosphere pressure on Earth is 101,325 Pa. And on Mars it’s bounces from 745 to 913 and this is less than 1% of Earth’s atmospheric pressure.

