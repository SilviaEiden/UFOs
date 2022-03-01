# UFO Sightings

## Overview

### Purpose

The purpose of this analysis is to help Dana, a data journalist, with her webpage of UFO sightings. Using JavaScript, a dynamic table was created allowing users to filter for multiple criteria at the same time. This includes filtering by date, city, state, country, and shape. 

Now, Dana's dynamic webpage can provide a more in-depth analysis of UFO sightings. 

<p float="left">
  <img src="Readme_Images/UFO.png" width="300" height="100" />
  <img src="Readme_Images/nasa.jpg" width="300" height="100" />
  <img src="Readme_Images/disk.jpg" width="300" height="100" />
</p>

## Results

### Dataset and Files

* Data.js file: [data](../static/js/data.js)
* App.js file: [app](../static/js/app.js)
* Index.html file: [index](index.html)

### Software and Web-Based Application

* JavaScript, or JS
* HyperText Markup Language, or HTML
* Google Chrome
* Visual Studio Code - Version: 1.62.3

### Outcomes

The UFO Sightings dynamic webpage includes the following:

- Navigation Bar: "UFO Sightings"
- Page Header: "The Truth is Out There"
- Article Title: "UFO Sightings: Fact or Fancy? Ufologists Weigh In"
- Article Paragraph
- Filters for the Table: "Date, City, State, Country, and Shape"
- Table of UFO Sightings Data

<p float="left">
  <img src="Readme_Images/Storyboard.png" width="450" height="350" />
  <img src="Readme_Images/Storyboard_webpage.png" width="450" height="350" /> 
</p>

Furthermore, below is a quick walk-through on how to use the filters to search for specific data from the table of UFO sightings data. The filters for the table are located on the left side of the webpage. In this example, the user looks up for UFO sightings in the shape of a triangle and in the city of La Mesa, California. Once the user presses enter, the table gives an output of one row of data with complete details. 

https://user-images.githubusercontent.com/95309815/156206558-a978ceb5-cba0-4769-bd31-aaf126460bd9.mov

As shown here, there are placeholders in each filter to guide the user on how to enter a search value. For example, to enter a date the format to follow is month/day/year or 1/10/2020 as displayed.

<p float="left">
  <img src="Readme_Images/filter.png" width="200" height="450" />
</p>

Lastly, the registered UFO sightings data is displayed as a table organized by date, city, state, country, shape, duration, and comments.

![data_columns1](Readme_Images/data_columns1.png)

## Summary

The UFO Sightings dynamic webpage includes great features, however there is a drwback to it. In the filter's search bar, the data is case sensitive and does not allow for mispelling nor incomplete entries. This truly limits the filter search capability, therefore limiting the volume of data output. For example, one would enter La Mesa using upper case for both words as it is a city located in California, however the city data is saved using lower case and as such will not recognize the entry. 

<p float="left">
  <img src="Readme_Images/filter.png" width="300" height="450" />
  <img src="Readme_Images/filter.png" width="300" height="450" />
</p>

With that stated, here are two recommendations that could be used for further development:

- The HTML autocomplete attribute. This attribute provides automated assistance in filling out form field values, as well as guidance to the browser as to the type of information expected in the field.




* The summary addresses one drawback of this webpage (2 pt)
* The summary addresses two additional recommendations for further development (4 pt)

In conclusion, an exploratory analysis on weather data was completed to generate a summary statistics for temperatures in June and December. Using Python and SQLAlchemy, additional queries were run to retrieve precipitation data on both June and December months. The precipitation data was then represented in a line chart to further instill confidence in W. Avy to invest in Surf n’ Shake with an eye toward future expansion. Given all the data reflected above, weather should not be a major concern with respect to investing in Surf n’ Shake. Surf's up!
