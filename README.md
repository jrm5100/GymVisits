# GymVisits
Practice in web scraping

Interacting with aspx websites seems to be a bunch of correctly formatted POST requests with specific parameters (discovered by watching them on Chrome) and the occasional GET.  

This experiment was also very helpful in getting practice with datetime data in Pandas.  The categorical dtype was very useful in keeping string-like labels in the correct order (weekday, month).  Pivot table seemed to be the easiest way to group then plot the data, but picking some other column as a "value" and aggregating on the length seems very hacky.

Nothing too surprising.  Frequency of gym visits over the course of the year has varied from year to year, which was interesting.  Longest streak and most visits in a month were both higher than expected.  Not surprised to see early-morning visits happen more often early in the year.
