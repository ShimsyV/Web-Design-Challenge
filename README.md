# Web-Design-Challenge : Web Visualization Dashboard (Latitude)

![](https://github.com/ShimsyV/Web-Design-Challenge.github.io/blob/main/WebVisualizations/assets/images/Readme_landing_page.PNG)

I created a visualization dashboard website using visualizations I had created in a past assignment. Specifically, I plotted weather data.

In building this dashboard, I created individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. I also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

# Website Requirements

The website consisted of 7 pages total, including:

### A landing page containing:

* An explanation of the project.
* Links to each visualizations page. There was a sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.

![](https://github.com/ShimsyV/Web-Design-Challenge.github.io/blob/main/WebVisualizations/assets/images/Readme_landing_page.PNG)

### Four visualization pages, each with:

* A descriptive title and heading tag.
* The plot/visualization itself for the selected comparison.
* A paragraph describing the plot and its significance.

![](https://github.com/ShimsyV/Web-Design-Challenge.github.io/blob/main/WebVisualizations/assets/images/Readme_temp_page.PNG)

### A "Comparisons" page that:

* Contains all of the visualizations on the same page so we can easily visually compare them.
* Used a Bootstrap grid for the visualizations.

The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

![](https://github.com/ShimsyV/Web-Design-Challenge.github.io/blob/main/WebVisualizations/assets/images/Readme_comparison_page.PNG)

### A "Data" page that:

* Displayed a responsive table containing the data used in the visualizations.
* The table is a bootstrap table component.
* The data is from exporting the .csv file as HTML, or converting it to HTML by using pandas. 

![](https://github.com/ShimsyV/Web-Design-Challenge.github.io/blob/main/WebVisualizations/assets/images/Readme_data_page.PNG)

### Navigation menu:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

![](https://github.com/ShimsyV/Web-Design-Challenge.github.io/blob/main/WebVisualizations/assets/images/Readme_nav.PNG)

