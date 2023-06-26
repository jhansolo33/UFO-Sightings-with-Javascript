# UFO-Sightings-with-Javascript

##  Overview of the analysis:
###  The webpage allow users to view the data via an HTML and a dynamic table using information from JavaScript. To provide a more specfic analysis of UFO sightings, we include more filters for multiple criteria at the same time. We customized the site to allow for additional table filters to incude the date, city, state, country, and shape

##  Results:
###  Using JavaScript and HTML, modifications of the code in the index.html file allowed us to create more table filters. In addition to the date filter, to assist the user, filters were added for the city, state, country, and shape.

###  Using JavaScript, the handleClick() function was replaced in the app.js file with a new function that saves the element, value, and id of the filter that was changed. There are five list elements for filtering in the index.html file. The event listener was modified to detect changes to each filter in the app.js file. The updateFilters() function saves the element, value, and the id of the filter that was changed. The filterTable() function loops through all of the filters and keeps any data that matches the filter values. The webpage filters the table correctly based on the users query.  

##  Summary:
### Drawback - The big drawback from using this page is the visual layout of the page. The page still looks very much like a table to me.

###  Recommendations - Add even more search criteria options to each event and I would like to see more pictures added to the results table for each event as well.  
