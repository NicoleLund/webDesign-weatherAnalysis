# web-design-challenge

UofA Data Analytics Bootcamp Homework Assignment 11-Web

### Assignment Description

Build a webpage reporting the analysis conducted in the UofA Data Analytics Bootcamp Homework Assignment <a href="https://github.com/NicoleLund/python-api-challenge.git" target="_blank">06-Python-APIs WeatherPy</a>. That analysis retrieved and analyzed the current weather at 500+ locations around the world. The webpage requirements included:

* Content deployed to GitHub pages
* Pages utilizes a consistent navigation menu at the top of every page including:
    * A link in the top left corner that returns the user to the landing page
    * A dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page
    * Additional links next to the dropdown menu for the "Comparisons" and "Data" pages
* Pages used formatting that is responsive to screen size using media queries or bootstrap

### Completed Website
<a href="https://nicolelund.github.io/web-design-challenge/index.html" target="_blank">https://nicolelund.github.io/web-design-challenge/index.html</a>

### Project Content Descriptions
* index.html - Primary website landing page explaining the project and a preview (with links) of all four visualizations reported.
* comparison.html - A quad-chart on medium/large screens that collapses to a single column on smaller screens that compares all four visualizations reported with corresponding links to detailed analysis for each figure. 
* data.html - A bootstrap responsive table containing the source data for the project.
* visualizations - A folder containing the individual detailed figure analyses for each weather observation category.
    * cloudiness.html - Latitude vs Cloudiness Analysis
    * humidity.html - Latitude vs Humidity Analysis
    * max_temp.html - Latitude vs Max Temperature Analysis
    * wndspd.html - Latitude vs Windspeed Analysis
* resources - A folder containing the content presented in the project webpages.
    * assets - A folder containing all of the source images.
    * cities.csv - The source data for data.html.
    * convert_cities.ipynb - A Jupyter Notebook for converting cities.csv into cities.html.
    * cities.html - HTML table code that was copied into data.html.
* css - A folder containing the common styles.css stylesheet for all webpages in the project.
