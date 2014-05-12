fire_and_drought
================

Final project for Information Visualization at the UC Berkeley School of Information
Xavier Malina, Cameron Reed and Peter Swigert

================

Project Goals
Our primary goal for this project was to design and build a directed narrative on historical drought and wildfire impacts in California. We wanted to provide users with an initial explanation of the core narrative, but then facilitate their exploration of drought and fire data over time through methods like filtering, highlighting and tooltips. To facilitate this exploration, we planned to build a website with interactive visualizations. We wanted to both present an interesting story about California, and enable users to uncover and visually explore the relationship between wildfires and drought across different variables.

Related Work
Drought and wildfire data is often visualized with maps, especially heatmaps and choropleth maps which show the extent and severity of the affected areas. This approach is valuable for answering the question of where things are happening. However, standard heatmaps are not good for showing the connection between drought and wildfire variables. Instead, we would like to visualize the data over time and focus on clarifying the relationship between drought and wildfire.

Visualization
We visualized the wildfire and drought data with six interactive Tableau dashboards arranged on a long scrolling webpage. The main content was broken into three sections: California Wildfire History, California Drought, and Wildfire and Drought. Each section included an introduction to the section topic and explanations of the dashboards. Throughout the document we tried to achieve a balance of explanation and exploration, pointing the user towards interesting patterns and data while allowing them to interact with and navigate the content. 

Data
We pulled data from two government sources. Our California wildfire dataset was derived from Dr. Karen Short’s national wildfire geodatabase from the U.S. Forest Service, accessible through USDA or the National Park Service. It contains data on all reported wildfires in the United States from 1992 to 2011. The fields we extracted included the geo-coordinates of the point of ignition as well as fire size, ignition date, and cause.
Drought data came from the NOAA National Climatic Data Center, which maintains historic climate data for all 344 climate divisions in the contiguous United States. We used the NCDC data search tool to obtain precipitation, temperature, and drought index data for the seven California climate divisions for the period of January 1895 to April 2014. 

Tools
We had initially planned on exploring the data in Tableau and building an interactive visualization in D3. However, after creating some exploratory charts in Tableau we realized that we could achieve the vast majority of the same output that we had hoped for with D3. A D3 component of the narrative was envisaged and implemented to about 60% completion before being put aside in favor of more work being achieved in Tableau. This decision left us much more time to focus on applying information visualization principles to our final product. We also discovered that Tableau dashboards could be embedded in our own webpage, which gave us more control over the context in which the dashboards would be presented. We used the Cool Kitten parallax framework as the foundation for our website and shared our code on GitHub. 

================


COOL KITTEN FRAMEWORK DETAILS:

///// This site was created with Cool Kitten - Parrallax Scrolling responsive frame work - 1.0 /////
Author: Jalxob
Release Date: February 2013.

///// Building /////

A small build script is included in order to minify and concatenate your javascript and css files. In order to use this script, you need to have *clean-css* and *uglify-js* installed globally using npm.

``` bash
sudo npm install clean-css uglify-js -g
```

Own the script

``` bash
chmod u+x compile.sh
```

Execute the script

``` bash
./compile.sh
```

///// Resources /////
- Normalize.css
- jQuery Easing Plugin
- Stellar.js

Build script and additional changes by [@james2doyle](https://github.com/james2doyle)


