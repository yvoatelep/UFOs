# UFOs
The purpose of this project was to create an interactive web page that would allow users to find UFO sightings based on criteria of Date, City, State, Country, and Shape of object sighted. In this way, citizen researchers may be able to get canofirmation of their own data or find information such as where the most UFOs have been seen, their typical shape and appearances, time of year that they are sighted, etc. The image below shows the overall appearance of the webpage and table. 

![This is an image](https://github.com/yvoatelep/UFOs/blob/main/static/images/UFO_intro_image.png)


## Results
The website allows users to filter sighting data based on any of the five the search criteria. As seen in the photo below, the data is searched based on any or multiple search criteria. If no events match the search criteria, the table will be blank. If all the search boxes are cleared and returned to placeholders, the page will default to showing all data. 

![This is an image](https://github.com/yvoatelep/UFOs/blob/main/static/images/UFO_Site_image_1.png)

In the image below, the table has been filtered to show events in the state of California. No other criteria is entered, so all those events show. (There are 29 events, although the photo only shows the first few.) 

![This is an image](https://github.com/yvoatelep/UFOs/blob/main/static/images/UFO_CAFilter.png)

If a filter is added that doesn't match an event in California, then no events will display. For example, no events occurred in California on January 7, 2010. When both CA and 1/7/2010 are input as filters, then no data appears. Similarly, if CA is typed in with upper case letters, as is normal when using the state abbreviation, no data appears. 

![This is an image](https://github.com/yvoatelep/UFOs/blob/main/static/images/UFO_%20UpperCase.png)

## Summary
Although the filters work in this version of the table, the code should be refined to accomodate varied types of  input. Right now, the code is set to accept only the exact word used in the data filters, which are not capitalized and use state abbreviations. This could be confusing to users and should be improved and ammended in future versions of the webpage. It would also be more useful if partial matches were shown. For example, when no events occur on the date selected and in the state, perhaps users could be prompted with a message, such as "29 events recorded in CA, but none on date selected. PLease remove dates to see data." Right now, users will miss out on important data that could help their research due to these shortcomings. 

Another major drawback of this search page is the limitation of the data provided. Users will only discover events if they are part of the database that this particluar site is built upon, and that is limited. An exciting element would be to make the page even more dynamic, by allowing users to log events for the developers. If events are logged multiple times or confirmed by multiple users, developers could use that information to update the database, so it could become a repository for sightings that would grown over time, much a wiki page.

