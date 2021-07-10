# UFO's - Using HTML and JavaScript to Filter UFO Data

## Overview of Project
The purpose of this project is to use HTML, JavaScript, and CSS elements to create a search filter option to filter a dataset of UFO sighting information on specific elements, and present the filtered table on the webpage. 

## Results
Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

In order to search through the data in the table provided on the webpage we have developed a filter option that allows the user to filter by date, city, state, country, or shape:
<p align="center">
<img src=https://github.com/smanowar/UFOs/blob/main/images/search_filter.PNG width="200" height="400">    
</p>
Note that date ranges between '1/1/2010' to '1/13/2010', and that state and country are specified by their respective abbreviation.

For example, we can filter the table by the date the UFO observation occoured:
<p align="center">
<img src =https://github.com/smanowar/UFOs/blob/main/images/search_by_date.PNG width="225" height="125">    
</p>

By filtering on '1/7/2010', by clicking out of the filter we get the result:
<p align="center">
<img src =https://github.com/smanowar/UFOs/blob/main/images/search_by_date_result.PNG width="700" height="200">    
</p>

We can also use the filter feature to apply 2 or more filters at once. Let us try filtering by date and by city:
<p align="center">
<img src =https://github.com/smanowar/UFOs/blob/main/images/filter_search_date_city.PNG width="1200" height="200">    
</p>

Our outcome is one result for the searched filtered on both date = '1/7/2010' and city = 'westbrook'

## Summary

One drawback of this new design is not knowing what options you have to search. Provide a list of possible options to filter for each element. This will allow the user to see what options are even available for them to search by.
 
Recommendations:

1. The ability to filter dates is very specific. Given that the current data set is relativley small it dosen't really pose an issue, however - with larger data sets in the future, future versions could possibly have the option to filter by year or by month vs. the specific date or have the ability to filter between a range of dates.

2. Adding a 'clear' button to clear all filters at once. This would allow for a more user friendly experience as if they are filtering more than one element it would allow them to clear everything at once verses deleting the filter for each element manually
