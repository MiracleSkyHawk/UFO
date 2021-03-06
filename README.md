# UFO

## Overview of Project

The goal of this project is to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time, such as the city, state, country, and shape.

## Results

![Challenge_Demo.png](Challenge_Demo.png)

The webpage that the user will see is depicted as the image above. The section highlighted by the letter "B" shows the user the title of point that the author is trying to convey. Section A uses a question to attract the user, and section C provides a little article about UFO.

The table in section E shows UFO sights in a tabular format. It provides information such as the date, city, state, country, shape, duration, and comments of the UFO sighting event. The user can filter which events they want to see by using the filter tool in section D. The user can input any of the filters or a combination of filters in the same format as in the table and press "enter" key to search for resutls. If a field is left blank then that the table will not be filtered by that field. To see all the data, press UFO sightings in the navigation bar or clear all the fields. 

## Summary

One drawback of this design is that the user has to input the exactly the same string as in the table in order to correctly filter the data.

The recommendations of future improvement are listed below.

- A fuzzy search algorithm can be implemented to allow the user to search for information with input string that does not exatcly match the corresponding field in the table.
- Instead of using "text" input to filter, dropdown menus can be used as inputs for the search function.
