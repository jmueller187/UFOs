# UFOs
Building tables and webpages using JavaScript, Bootstrap and CSS.

[Deployed UFO's Web Application](https://jmueller187.github.io/UFOs/)

## Overview of Project:
After creating a UFO Sightings webpage containing a dynamic table of data which could be searched by entering a sighting date, we were tasked with providing an opportunity to perform a more granular analysis by allowing users to filter for multiple criteria at the same time. Along with the original date field, we added table filters for the city, state, country, and shape associated with each sighting.

## Results:
When users visit the webpage, they now have five options in the Filter Search section to search for specific entries in the UFO sighting data. They can narrow their search by choosing a search field, entering the appropriate criteria and pressing Enter to initiate the search. The filtering options are as follows:

1) Filter by Date:
![Filter by Date](https://github.com/jmueller187/UFOs/blob/main/Resources/UfosFilterByDate.png)

2) Filter by City:
![Filter by City](https://github.com/jmueller187/UFOs/blob/main/Resources/UfosFilterByCity.png)

3) Filter by State:
![Filter by State](https://github.com/jmueller187/UFOs/blob/main/Resources/UfosFilterByState.png)

4) Filter by Country:
![Filter by Country](https://github.com/jmueller187/UFOs/blob/main/Resources/UfosFilterByCountry.png)

5) Filter by Shape:
![Filter by Shape](https://github.com/jmueller187/UFOs/blob/main/Resources/UfosFilterByShape.png)


## Summary:
While the webpage now contains multiple options for filtering the UFO sighting data, there is now a drawback in that the criteria you want to use must exist for the specific search field or no results will be returned. For example, entering a shape that has not been tracked will not provide any table entries.
This issue could be resolved in future development by adding drop-down menus for each search field so the users can select from the available entries to narrow their search. Another development option to resolve this issue would be to include a type-ahead feature in the search fields, thereby filling in the entry as the user types if that entry exists in the current data. 
