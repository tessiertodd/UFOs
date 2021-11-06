# UFOs

## Project Overview
We are helping Dana to build a webpage that displays information about UFO sightings using JavaScript along with an HTML index file and CSS style file.  The webpage contains a list of UFO sightings with information around each sighting (date, city, state, country, shape, duration and comments).  This first iteration of the webpage had a filter to allow the user to select only sightings on a certain date - if no filter was used, all the data is displayed.

We have been tasked with building on the webpage we designed together which contained one filter to one that allows users to filter on up to all 5 pieces of information that we have for all sightings.

## Resources
- Sofware: Visual Studio Code
- Language: JavaSript
- Language: HTML
- Library: Bootstrap CSS style


# Results of Filter UFO sightings on multiple creteria
We needed to adjust both the HTML idex file to add the filters onto the website to allow users to be able to use any number of the filters to help view information of interest.

The user would use this new functionality by first going to the website.
![Table 1 top of website](https://github.com/tessiertodd/UFOs/blob/main/Top%20of%20site.png)

The user then needs to scroll down to the bottom of website.
![Table 2 bottom of site](https://github.com/tessiertodd/UFOs/blob/main/Bottom%20of%20site.png)

Near the bottom of the user will see go to the Filter Search area:
![Table with! filters highlighted](https://github.com/tessiertodd/UFOs/blob/main/Filter%20highlight.png)

User will now make selections on filters, they can choose to enter no filters or up to all five.

![Table_with filter seleted](https://github.com/tessiertodd/UFOs/blob/main/filter%20select.png)

Next we need to build a new function in our JavaScript file that would take the filters selected, loop through all the data and return the filtered dataset based on those filters to back to the webpage.  Here is a sample of some of the results from a filter on date of 1/1/2010.
![Table_with results](https://github.com/tessiertodd/UFOs/blob/main/selection%20results.png)


# Summary
Once these filters have been added to the website, this allows the users to much more easily analyze the data and get some insight around the topic of UFO sightings.

### Drawback
One drawback of this webpage is that the dataset we are using is static and a little dated as its from 2010.

### Recommendations
- It would be great to add a more recent data that can be searched, and ideally if data was being updated in real-time that would be even better.

- All of this data is great, but its limited to North America, and in very heavily weighted to the US.  If users from other countries around the world were accessing this webpage, they would like to see information from UFO sightings in their area of the world.

- If we had a feature to be able to seach and filter on key words, ideally in the comments as users may be looking for similar experiences they have heard of or had themselves.
