# South Carolina COVID-19 Dashboard

This is a dashboard of daily-updated information about the COVID-19 pandemic in
the US state of South Carolina. It is powered by R's `flexdashboard` package,
with images by `plotly`, and daily updates run by Github's Actions feature.

Originally, most data came from daily press releases from the 
[South Carolina Department of Health and Environmental Control](https://scdhec.gov).
Because this agency no longer issues daily updates and does not release its
raw data to the public in an accessible format, there is no longer any data
included that comes directly from SCDHEC.

For daily/weekly case data as well as county-level case and death data, data 
from [the New York Times](https://github.com/nytimes/covid-19-data) is used.

For a few months of historical hospitalization data, the now-defunct
[COVID Tracking Project](https://covidtracking.com) is used. 
More recent hospitalization data comes from reports to HHS via 
[healthdata.gov](https://healthdata.gov/Hospital/COVID-US-Adult-Hospitalizations-by-state-/6ps2-ifta)

Testing data is compiled from labs that report to various local, state, and
federal agencies. It is available via
[healthdata.gov](https://healthdata.gov/dataset/COVID-19-Diagnostic-Laboratory-Testing-PCR-Testing/j8mb-icvb)

US Census Bureau population estimates and geographic shapefiles come from 
the [`tidycensus`](https://cran.r-project.org/package=tidycensus) package.

Click [here](https://jacob-long.github.io/SC-COVID-19-Dashboard/sc_dashboard.html) 
to see the dashboard.
