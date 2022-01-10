# UFOs
## Overview of the Project
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, four more filters were added for the city, state, country, and shape.

Deliverable 1: Filter UFO sightings on multiple criteria
Deliverable 2: A written report on the UFO analysis

## Results
Upon loading the HTML webpage the user sees a navigation bar for 'UFO Sightings' and a page header with the title 'The Truth Is Out There'. Below this the page is slpit into two columns, the left side of the page shows the article title and the right side shows more information within a paragraph. Below this the page is splut again into two columns, the left column being smaller than the right column. The right column includes the data table with all avaialble data. The left side of the page includes a filter that can filter the data for the following:
- Date 
- City
- State
- Country
- Shape
When any one or a combination of filters are entered, the table is updated to display search results.

Examples of some searches are illustrated below:
#### 1. Date

#### 2. City

#### 3. State

#### 4. Date and City

## Summary
This webpage is very successful in filtering the data by a specific date, for  a specific city, state, country, and shape.
#### Drawback
A drawback of this is that before using the data file it wasn't cleaned to make sure dirty data doesn't get published on the website. For example the 'Duration' of UFO sighting on 1/1/2010 in spring valley ca is 10:00, which does not represent duration. Similarly, on 1/9/2010 in freedom ca, duration has no units.

#### Additional Recommendations
#### 1.
The code should be improved such that dates can be fileterd as a range. Right now, the dates can only be filtered one at a time. However, if the dataset was large enough to include several months or years and the user wanted to see results for an entire month, they wouldn't be able to do so.
#### 2.
The webpage can be improved by adding a dropdown for the filter boxes so that the user knows what options to choose from, in order to avoid people having to search for dates and locations that aren't even available in the dataset and comoing up with blank search results.