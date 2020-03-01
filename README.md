# Web Design Homework - Web Visualization Dashboard (Latitude)

## Background

This repository seeks to create a website using `HTML` and `CSS` primarily from `Bootstrap` code snippets. A prior data analysis `WeatherPy` will be used as the data to create a website "Dashboard" to demonstrate the power of being able share and communicate your data science results publicly on a website. The website will be deployed on GitHub pages as the host of the `.html` files.

![Images/landingResize.png](WebVisualizations/Images/WebVis_home.png)


## Latitude - Latitude Analysis Dashboard with Attitude

For this exercise we'll be using [weather data](WebVisualizations/Resources/cities.csv) and using scatterplots from the [WeatherPy repository](https://github.com/kipmadden/python-api-challenge).

Individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Pages

For reference, see the ["Screenshots" section](#screenshots) below.

The website consists of 7 pages total:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    
The website has at the top of every page a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use bootstrap. This includes using the bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

### Bonuses

* Use a different dataset! The requirements above still hold, but make it your own.
* Use a bootstrap theme to customize your website. You may use a tool like [Bootswatch](https://bootswatch.com/). Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state. See the screenshots below.

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### Landing page

Large screen:
![Landing page large screen](Images/landing-lg.png)

Small screen:
![Landing page small screen](Images/landing-sm.png)
￼

#### Comparisons page

Large screen:
![comparison page large screen](Images/comparison-lg.png)

Small screen:
![comparison page small screen](Images/comparison-sm.png)

#### Data page

Large screen:
![data page large screen](Images/data-lg.png)

Small screen:
![data page small screen](Images/data-sm.png)

#### Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:
![visualize page large screen](Images/visualize-lg.png)

Small screen:
![visualize page small screen](Images/visualize-sm.png)

#### Navigation menu

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:
![nav menu small screen](Images/nav-sm.png)
