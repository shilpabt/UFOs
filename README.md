# UFOs

# Overview of the Project
The objective of the project was to create a website that displays a dynamic table using which users can analyse the UFO sightings data. To provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape. 

The website was created using HTML for the basic structure. A style.css file that works in combination with Bootstrap to complete the decoration and feel of the website.

# Results 
Below is the webpage organized in a user-friendly way, that allows filtering the data of the UFO sightings based on: 
*  Date
*  City
*  State
*  Country
*  Shape 


![UFO sighting webpage](static/images/UFOwebsite.png?raw=true)


Selecting any of the filter criteria, user can either press "Enter" or "tab" key or can click anywhere else on the webpage out of the input box boundaries, the filter gets the matching data. The user can get more specific data by entering specific filters. 

Below is the filtered data by filtering city = willow,

![UFOs webpage by city](static/images/UFOsFilterbycity.png?raw=true)

Below is another example of UFO sighting filtered by shape, shape = trianle,

![UFOs webpage by shape](static/images/UFOsfilterbyshape.png?raw=true)


# Summary 
### Drawback of this webpage
Though the webpage serves the users to filter the data with multiple filters pretty well, it has some drawbacks in the filter text supplied for each filter as,
1. It is case sensitive eg, if we enter the state as "TX" instead of "tx", it gives no records and filters to browse the data is not enough.

### Additional development recommendations for further development

1. Filters can be implemented with the unique values of the columns preloaded as a dropdown list. This will add up to ease of use.

2. Webpage filters functionality can be enhanced by displaying the "Number of Records" found matching for the current filter on the column headers bar.



