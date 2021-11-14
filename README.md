# UFOs

## Overview of UFO Analysis

### Purpose

The purpose of this project is to assist Dana, a data journalist, in producing a webpage via JavaScript detailing and analyzing UFO sightings from different cities around the world. 


## Results 

### Results UFO Analysis
In order to conduct a search, the user must enter the desired information, in the correct format, into the search bar located in the left hand side of the webpage (Figure 1). If one wants to filter their search to a specific city, one would only need to enter the name of the city into the city search bar and the webpage will comb through the Java Script file and output results from city specified. For example, in Figure 2, the city of willow was entered into the search bar, and two results for the city came up.  


#### Figure 1
![](static/images/Search_bar.png)    

#### Figure 2
![](static/images/city_search.png)  
 


## Summary
The webpage works well but it contains several drawbacks.

Firstly, the filter search bars require the user to enter the data in the specific format previewed within the empty search boxes. The date must be entered in DD/MM/YYYY format, and the remainder of the boxes must be entered in all lowercase letter: the filter function is case sensitive.  

Secondly, the box for state must be entered exactly as it appears in the preview. This filter only recognizes 2-letter lowercase abbreviations such as "va" or "ny." Entries such as "VA" or "Virginia" will not be recognized, and the same goes for the country filter. The webpage only recognizes "us," not "USA" or "Unites States."  

Two recommendations were identified as possible avenues for improvement for this webpage. First, the filter search provides a box for country, but the JavaScript file only contains information for cities within the United States. It is recommended to either add additional information to the file regarding UFO sightings abroad, or to remove the option to search for countries, since such a search would be irrelevant. The second recommendation is to add a sixth filter search for duration of the UFO sighting. There is significant data regarding different durations of UFO sightings, and it would be useful for the user to filter such data. 


