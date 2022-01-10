# UFOs
## Overview of the Project
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, four more filters were added for the city, state, country, and shape.

Deliverable 1: Filter UFO sightings on multiple criteria<br/>
Deliverable 2: A written report on the UFO analysis

## Data Source and Code Files
Data source: [data.js](https://github.com/rmat112/UFOs/blob/main/static/js/data.js)<br/>
Javascript code: [app.js](https://github.com/rmat112/UFOs/blob/main/static/js/app.js)<br/>
HTML file: [index.html](https://github.com/rmat112/UFOs/blob/main/index.html)

## Results
Below is an overview of the webpage created for this challenge.
![img1.png](https://github.com/rmat112/UFOs/blob/main/static/images/img1.png)

Upon loading the HTML webpage the user sees a navigation bar at the top for 'UFO Sightings' and a page header with the title 'The Truth Is Out There'. 
![img2.png](https://github.com/rmat112/UFOs/blob/main/static/images/img2.png)
![img3.png](https://github.com/rmat112/UFOs/blob/main/static/images/img3.png)
Below this the page is split into two columns: the left side of the page shows the article title and the right side shows more information within a paragraph. 
![img4.png](https://github.com/rmat112/UFOs/blob/main/static/images/img4.png)
Below this the page is split again into two columns. The right column includes a table with all available data. The left side of the page includes several input boxes to filter the data for the following:
  - Date 
  - City
  - State
  - Country
  - Shape
  
![img5.png](https://github.com/rmat112/UFOs/blob/main/static/images/img5.png)

When any one, or a combination of filters are entered in the input boxes, the table on the right is updated to display search results.

Examples of some searches are illustrated below:
#### 1. Date
Filter applied: Date 1/2/2010
![datefilter.png](https://github.com/rmat112/UFOs/blob/main/static/images/datefilter.png)

#### 2. City
Filter applied: City Madison
![cityfilter.png](https://github.com/rmat112/UFOs/blob/main/static/images/cityfilter.png)

#### 3. State
Filter applied: State ak
![statefilter.png](https://github.com/rmat112/UFOs/blob/main/static/images/statefilter.png)

#### 4. Date and City
Filter applied: Date 1/1/2010, city la mesa
![datecityfilter.png](https://github.com/rmat112/UFOs/blob/main/static/images/datecityfilter.png)

## Summary
As illustrated above, this webpage is very successful in filtering the data by a specific date, for  a specific city, state, country, and shape.
### Drawback
A drawback of this page is that before using the data file it wasn't cleaned to make sure dirty data doesn't get published on the website. For example the 'Duration' of UFO sighting on 1/1/2010 in spring valley ca is 10:00, which does not represent duration. Similarly, on 1/9/2010 in freedom ca, duration has no units.

### Additional Recommendations
1. The code should be improved such that dates can be fileterd as a range. Right now, the dates can only be filtered one at a time. However, if the dataset was large enough to include several months or years and the user wanted to see results for an entire month, they wouldn't be able to do so.

2. The webpage can be improved by adding a dropdown for the filter boxes so that the user knows what options to choose from, in order to avoid people having to search for dates and locations that aren't even available in the dataset and comoing up with blank search results.
