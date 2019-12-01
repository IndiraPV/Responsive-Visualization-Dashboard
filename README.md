# Responsive Visualization-Dashboard using BootStrap 4.3, HTML5 and CSS

## [Latitude - Latitude Analysis Dashboard](https://github.com/IndiraPV/Responsive-Visualization-Dashboard)
Part of Case Western Reserve University's data bootcamp weekly challenges, created a dashboard [website](https://indirapv.github.io/Responsive-Visualization-Dashboard/) using visualizations that were created in a past assignments. Specifically,plotting weather data.
In building this dashboard, individual pages was created for each plot and a means to navigate between them. These pages contain the visualizations and their corresponding explanations. There is also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

The website has the following:
* A landing page containing an explanation of the project and links to each visualizations page.


![final_app](Images/final_app.PNG)

* Four visualization pages, each with:
	* A descriptive title and heading tag.
	* The plot/visualization itself for the selected comparison.
	* A paragraph describing the plot and its significance.

![max_temp](Images/maxtemp.PNG)

![humidity_page](Images/Humidity.PNG)

![cloudiness_page](Images/cloudiness.PNG)

![wind_page](Images/windspeed.PNG)


* A "Comparisons" page that:

Contains all of the visualizations on the same page so we can easily visually compare them.
Uses a bootstrap grid for the visualizations.

The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

Screens medium and larger:
![comparisons_page](Images/Comparisons.PNG)

Screens etra-small and small:
![comparisons_responsive](Images/comparisosns_small_screen.PNG)


* A "Data" page that:

Displays a responsive table containing the data used in the visualizations.
The table is a bootstrap table component.
The data comes from exporting a csv file to a dataframe and generating HTML table using Pandas nifty method appropriately called to_html that allows you to generate a HTML table from a pandas dataframe. 

![data_page](Images/Data.PNG)


The website has, at the top of every page, a navigation menu that:

Has the name of the site on the left which allows users to return to the landing page from any page.
Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
Navigation menu is responsive (using media queries). 

![navbar_large](Images/navbar_large_screen.PNG)

![navbar_small](Images/nav_small_screen.PNG)

Finally, the website was deployed to GitHub pages.

[website](https://indirapv.github.io/Responsive-Visualization-Dashboard/)
