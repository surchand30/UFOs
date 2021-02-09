# UFOs

## Overview:

This project involved analyzing UFO sightings data stored in a JSON file format and making it the foundation of a user interactive web page. The idea was to parse the data from the JSON file format into a table using Javascript and access it using a webpage created using HTML. The webpage was created in such a way that the user should be able to filter through and view the data from the website.

## Results:

The UFO sightings webpage was created to provide an easy way for users to filter through the JSON data and analyze the data on a web browser. The UFO data comprises of Date of Sighting, City, State, Country where the UFO was sighted, Shape of the UFO, Duration for which the UFO was sighted and comments added by the individual who sighted the UFO. Filters were added to be able to slice and dice the data by the Data, City, State, Country and Shape parameters. Using these filters, it is very easy to analyze factors like :

  * On a particular date how many UFOs were sighted
  ![Date Capture](https://github.com/surchand30/UFOs/blob/main/Date%20Capture.PNG)
  
  * At a particular location how many UFOs were sighted
  ![Location Capture](https://github.com/surchand30/UFOs/blob/main/Location%20Capture.PNG)
  
  * How often was a circular UFO sighted
  ![Shape Capture](https://github.com/surchand30/UFOs/blob/main/Shape%20Capture.PNG)
  
  
  The webpage also enables us to apply multiple filters to narrow down our search to specific attributes.
  
  ## Summary:
  
  ### Drawbacks : 
  
  Though the webpage makes it very easy to filter through data to narrow down our search results, a user will need to browse through the entire data set to understand what are the possible values that each filter/attribute can take. This could make the data analysis ineffective and time consuming.
  
  ### Recommendations :
  
  * Having drop down lists with all possible values for each filter attribute could make the search very effective
  * The ability to sort date and duration columns will also be helpful in terms of identifying when was the UFO first or last seen or what is the maximum/minimum duration of the UFO sighting
