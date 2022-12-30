# UFO's

## Overview and Purpose
Dana, a data journalist tasked the analyst with creating a webpage that holds a table of UFO sighting data by using javascript, HTML, and CSS.  The analyst used HTML and CSS to design the webpage and user interface, and javascript to create the table.  The table has various filters so that users can search through the data by date, city, state, country, and shape.

## Results
The final result of the analyst's work is the webpage shown below:

![webpage.png](https://github.com/hillmanj1995/UFOs/blob/main/Resources/webpage.png)

To access the webpage, the user can click the following link: [UFO Finder](https://hillmanj1995.github.io/UFOs/)

To view the UFO sighting data, the user should scroll down the page until they find the filter inputs:

![filter_no_search.png](https://github.com/hillmanj1995/UFOs/blob/main/Resources/filter_no_search.png)

If the user wants to deploy a search filter on the data, all they have to do is type a date, city, state, country, or shape into its respective filter and hit enter:

![filter_state_search.png](https://github.com/hillmanj1995/UFOs/blob/main/Resources/filter_state_search.png)

To get back to the original dataset, the user can either refresh the page, or clear the filters and hit enter.

## Summary
The webpage is a success, but there is always room for improvement.  Some drawbacks to the webpage and its filters are that it cannot search a range of dates, which requires the user to know the exact date of the sighting they are looking for.  The filters are also case and space sensitive, so any use of upper case letters or additional spaces (example: "NY" vs. "ny"), will result in an empty table for a result.

To remedy the date issue, the analyst can create a filter that filters by month and year.  That way, the user can easily filter through different ranges of time so find what they are looking for more easily.

The analyst should also use a trim function to eliminate any extra spaces from the user inputs that could create an error while filtering.  They should also modify the input to be able to read both upper and lower case letters.