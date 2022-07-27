# UFO's <br> Unidentified Flying Objects
🌌 Observing a world _**beyond**_ our own 🌌

## Overview 

The purpose of this website was to take a `JavaScript` dataset and use it to create a table that can be filtered through using multiple different criteria (city, country, UFO shape, etc...). Users can filter through the data and see if any UFO's have been sighted in thier area. Once created, this data is housed on an `HTML` that can easily be visited and viewed if hosted on a server.  

## Resources
- UFO Data: [UFO Sighting Data](js/data.js) <br>
- JavaScript file that makes and filters data: [App Script](js/app.js)<br>
- Web Page: [HTML Script](index.html)


## Using The Site

### Landing Page
When opening the site, users will be greeted with an image of our earth at night with a short paragraph and the beginning of a large table. At the top left, the UFO Sightings text can be clicked to reinitialize the page. The table holds all of the data that has been taken from the Data.JS, ran through functions and displayed here on our HTML site. Here is the main landing page: 

![Main](https://user-images.githubusercontent.com/60283799/181372217-85582789-e79e-47b4-b76c-1087c4a806d6.PNG)

### Filters 
When the user is familiar with the table and the different criteria that can be used to search, the can head over to the filters on the left side of the page. Here, they can input anywhere from one to five different filters. The format for inputting a filter is given to the user in the box as a place holder. This lets the user know how to input their criteria.   

Once the information is inputted by the user, the background code (`app.JS`) will run the table building function with the provided filters and return a table that displays the data the user is looking for. To For example, if someone was looking UFO sightings in San Diego, CA, that happened on 1/1/2010 and were triangle shaped, this would be the result: 

![filtered](https://user-images.githubusercontent.com/60283799/181375553-2467d278-6741-4c9d-8746-f784e45174fc.PNG)

They would be in luck because there was exactly one reported incident with that specific criteria. 
This process can be repeated to output different, specific results. 

## Summary 

The information is displayed in a neat, presentable and easy-to-use format. However, there is always room for improvment. One drawback of this webpage was that there isn't a whole lot of data to filter through so it may seem light on information.

When it comes to suggestions i would make for further development, there are a few. Beginning with a "clear filters" button that takes the applied filters away and resets the table to the default, unfiltered setting. Another change i would make is adding a drop-down menu in all of the search bars so that the user knows exactly what can and cant be searched for. Finally, i would format the paragraph to go all the way across the page and have the header and sub-header above that. 

