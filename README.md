# UFOs
JavaScript: array, filters. HTML and Bootstrap tu customize webpage
## Overview of Project
Share via web a conoslidated data base of UFO sightings from January 1st 2010 to January 13th 2010. The data is stored in a JavaScript array with: date, city, state, country, shape, duration and comments. The website has an option to filter the data based on one or multiple criteria and updates the table accordingly.
JavaScript was used to create the table in the website and HTLM, CSS and Bootstrap were used for design and structure. 
## Results
The website contains navigation bar, page header with an image, an attention grabber article title and subtitle, the article, filters and the table. 

![Top Page](https://github.com/Jimena-QM/UFOs/blob/main/resources/TopPage.png)

![Bottom Page](https://github.com/Jimena-QM/UFOs/blob/main/resources/BottomPage.png)

The user can filter by multiple criteria and the table is updated once the user inputs the data. Each filter option contains a place holder to guide the user on the format of the required filter. The source code listens for user input and applies filters, if the filter input does not match any of the data criteria the table shows only the table headers. 

The user must type in the filter desired with one or more criteria and press enter after typing the desired filter. To reset to the original table the user must delete the filtered input. 

The image below show the filtered table by city "el cajon"

![One Filter](https://github.com/Jimena-QM/UFOs/blob/main/resources/OneFilter.png)

The image below shows an additional filter of shape "triangle"

![Two Filter](https://github.com/Jimena-QM/UFOs/blob/main/resources/OneFilter.png)

If the input for filter does not match the data from the table, the following is displayed

![No Match Filter](https://github.com/Jimena-QM/UFOs/blob/main/resources/FilteredDataNotInTable.png)

## Summary
One important drawback for users is that in order to filter the data the user must add the filter exactly as it is in the table, the same nomenclature. For example, if the user inputs US instead of us the filter does not work. 

Recommendations: 
- Add the a brief summary of the date ranges, countries and shapes included in the table.
- Add drop down menus so the user can select the filter and avoid getting a blank table due to spelling or date ranges. 
- If the table comes out with no data, adding a message such as "No Data available for the filters specified". 

