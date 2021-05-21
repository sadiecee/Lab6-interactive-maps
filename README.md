# Summary of Lab
The goal of this lab was to explore how to create, edit and making important decisions regarding the visualization of geospatial data. We used the Folium library [Folium](https://python-visualization.github.io/folium/), which builds on a common web mapping javascript library called [Leaflet](https://leafletjs.com/). Folium lets you customize and edit your maps, adding in multiple layers, changing the color palette and more. It's a very powerful tool. 

In this code, we first mapped starbucks in LA county, aggregating by zip code into a choropleth map. We compared that choropleth map to that of one using point data to describe some of the flaws of using a unit disconnected to human behaviors, such as zip codes, have in creating misleading maps. We ended up creating a better choropleth map that looked at unemployment rates by state. The unemployment map took in a list of states and their unemployment rate as an input and created a choropleth map as an output. This code is the final code block shown in my .py code file. 

# Debugging and Write Up
This lab was very helpful in understanding how to integrate code with the GIS data – and what performing geospatial analysis might look like in a platform like Python. It was also illustrative in the decisions that we as GIS students might have to make, and what considerations are important to take into account. Maps can be very powerful but very misleading and it’s important to think deeply about why we are making the choices we are making when we choose how we display the data. 

I didn't necessarily run into any huge errors that required debugging for this lab, but I did rely on the Folium python library to understand which keys to use and how to alter, add to or subtract from my final, new Folium lab map. At times, it could be a struggle to understand what the Folium library at first, but the more I used it the more I understood how to read it, a skill that I think will be incredibly helpful moving forward. 

# Citation
This tutorial is based on [this Medium Tutorial by Ritvik Kharkar](https://towardsdatascience.com/making-3-easy-maps-with-python-fb7dfb1036) and the associated [Github repo for his tutorial](https://github.com/ritvikmath/StarbucksStoreScraping) that has been updated by Professor Shadrock Roberts.
