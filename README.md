# South Carolina COVID-19 Dashboard

This is a dashboard of daily-updated information about the COVID-19 pandemic in
the US state of South Carolina. It is powered by R's `flexdashboard` package,
with images by `plotly`, and daily updates run by Github's Actions feature.

There are 3 data sources used:

* [South Carolina Department of Health and Environmental Control](https://scdhec.gov)
* [New York Times county-level COVID-19 case and death data](https://github.com/nytimes/covid-19-data)
* [The COVID Tracking Project](https://covidtracking.com)
* US Census Bureau population estimates and geographic shapefiles via 
the [`tidycensus`](https://cran.r-project.org/package=tidycensus) package.

Click [here](https://jacob-long.github.io/SC-COVID-19-Dashboard/sc_dashboard.html) to see the dashboard.
