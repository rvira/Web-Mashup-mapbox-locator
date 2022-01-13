# Web-Mashup-mapbox-locator
Web application takes information from one or more sources and presents it in a unique layout.


## Problem statement
There is a lot of information available on internet  
Using **Web Mashup** gather this information from different sources  
Apply logic such that the most important information from this bulk amount of data will be displayed to user  

</br>

*Refer this link for ideas about developing web mashups*  
https://www.programmableweb.com/category/indian/mashup

## About Mashup

- Two APIs used:   
  1. Location API - https://coinmap.org/api/v1/venues/  
  2. Maps API - MapBox APIs (*https://www.mapbox.com/*)

- Coordinates and name of ATM from Location API is passed to MAPBOX API, which pinpoints the location according to the latitudes and longitudes provided.
- Location can be searched as well mashing up anither API from MapBox.

## How to execeute

1. Change the source of following snippet in *layout.html*
  > <script src="C:\Users\Rishabh\Desktop\cordinates.js">
  
2. Run the layout.html
  
  
## Extended scope
  API data can be stored in the database for increasing efficiency
