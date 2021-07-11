# UFO Sighting Data

## Overview
### Filtering Data

This analysis uses JavaScript, html, bootstrap, and CSS to create a visually appealing site that will display data of UFO sightings. The script was built to filter by date, city, state, country, and/or shape of the UFO.

## Results
### Filtering the Data

When the page is first loaded, it brings up the entire data table, unfiltered, with five filter criteria boxes available for user input (as pictured below). Each box contains a placeholder to show what kind of information should be entered and in what format.
![Alt Text](https://github.com/lyanneagger/UFOs/blob/main/static/images/all.png)</br>

To filter by only one criteria, the user would enter that into the appropriate box. In the example image below, "1/10/2010" was entered into the date box. This filter reduces the original dataset down to only 11 entries.
![Alt Text](https://github.com/lyanneagger/UFOs/blob/main/static/images/jan10.png)</br>

Additional filters can be combined by entering them in succession. Using the January 10, 2010 data group, another filter is applied for the state of California. Entering "ca" into the state filter box returns the following two results.
![Alt Text](https://github.com/lyanneagger/UFOs/blob/main/static/images/jan10ca.png)</br>

The filters can be reset either by deleting them in the input boxes or by clicking the "UFO Sightings" link in the nav bar on the top left of the page, and the entire dataset will be available for viewing again.


## Summary

One drawback of current design is that the user input must match the data exactly. For example, entering "1-1-2010" into the date filter returns no results, but "1/1/2010" returns more than 30 results. 

One recommendation for further development that would solve this issue would be presenting the filter options as a drop-down menu. Offering a drop-down menu would allow the user to choose from options already within the data rather than guessing at each state one by one. Seeing a list without Nebraska or Hawaii listed would make it instantly clear that there are no data points in those states and potentially save the user some time.

Additionally, the script could be developed further to broaden search results to look for partial matches. For example, the country search returns two results for "ca" for Canada, but any capitalization or full spelling will return nothing. The code would need to be changed to disregard case and search for full or partial spellings. In addition to that, states would need to be brought in so that searching "Pennsylvania" would return the two results for "pa."