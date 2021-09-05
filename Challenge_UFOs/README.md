# UFO sightings

An html page of UFO sightings data is presented, created using Javascript and using Bootstrap and CSS to visually enhance the page.

## Overview of Project
Create a dynamic view that allows a deeper analysis of UFO sightings, allowing users to filter by multiple criteria at the same time; date, city, state, country and shape.

In order to offer a dynamic view it was necessary to have several filters, so that users can access the information where the sightings occurred.

By clicking on the following links you can access the Javascript and HTML files:

- <a href="https://github.com/CarmenU18/UFOs/blob/main/Challenge_UFOs/static/js/app.js"> UFO - Javascript file</a>
- <a href="https://github.com/CarmenU18/UFOs/blob/main/Challenge_UFOs/index.html"> UFO - HTML file</a>

## Results

The UFO data is displayed in table format with filters that allow a more agile access to the information:

<img src = "Resources/Image1.png"></img>

The user can select any search criteria: Date, City, State, Country or Shape as shown in the image above and by pressing "Enter", "tab" or clicking outside the search box, the filter retrieves the matching data and loads only the matching records into the table.
For example: Country = us, City = el cajon and Shape = triangle; you get:

<img src = "Resources/Image2.png"></img>

You can use only one filter, for example: Shape = light:

<img src = "Resources/Image3.png"></img>

## Summary

- The objective of having a dynamic view that allows filtering the information was achieved, the filter has a drawback: it is necessary to write the complete data to be searched for the filter to be applied correctly. To speed up the search, an improvement would be to be able to make a predictive search, i.e., as the user enters the data, the possible results are displayed.

- A second improvement would be for the search box to be case-insensitive.

- The "Filter Lookup" next to the table, could be replaced by filters that are applied directly in the headers and filtering as the user types. This would help to have a cleaner page and you would have the option to have more columns with data or expand the size of those columns.

- In order to better visualize the information without having to scroll down, a pagination with only a certain number of lines per page could be established.