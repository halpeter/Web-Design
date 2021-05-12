# Web-Design

## Background

Data is more powerful when we share it with others! I've taken what I've learned about HTML and CSS to create a dashboard showing off the analysis I've done. I've created a visualization dashboard website using visualizations created in my repo: python-api-challenge. Specifically, I've taken plots made from WeatherPy within this repo that used a cities CSV to create scatterplots of lattitude vs. specific weather attributes. The CSV and PNGs of the plots can be found within this repo inside of the Resources folder.


## Outline of Website

In building this dashboard, I created individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. I also have created a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Page Breakdown
This website consists of 7 pages total, including:

* A landing page which contains:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.
  * Code for this page can be found at [index.html](index.html)

* Four visualization pages, each containing:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
  * There is a sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.
  * Code for these pages can be found at [cloudiness.html](cloudiness.html), [humidity.html](humidity.html), [temperature.html](temperature.html), and [windspeed.html](windspeed.html).

* A comparison page that contains:
  * All of the visualizations on the same page so the user can easily visually compare them.
  * The screen updates based on the users screen size, they will see two images in a row on larger screens and one image per row on smaller screens.
  * Code for this page can be found at [comparison.html](comparison.html)

* A data page that contains:
  * A responsive table containing the data used in the visualizations.
  * The table was made from converting the csv file to an html file in python jupyter notebook (found [here](Resources/csv_conversion.ipynb))
  * Code for this page can be found at data.html

This website has a navigation menu at the top of every page that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Code for this can be found in the beginning of the body of each html file under nav

