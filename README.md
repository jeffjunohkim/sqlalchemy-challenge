# sqlalchemy-challenge

## Overview
Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you decide to do a climate analysis about the area. The following sections outline the steps that you need to take to accomplish this task.

### Climate Data Analysis
#### Precipitation Analysis:
- Find the most recent date in the dataset.
- Query the previous 12 months of precipitation data.
- Load the data into a Pandas DataFrame, sort by date, and plot the results.
- Print summary statistics.

#### Station Analysis:
- Calculate the total number of stations.
- Find the most-active stations and their observation counts.
- Calculate temperature statistics (min, max, avg) for the most-active station.
- Query the previous 12 months of temperature observation data and plot as a histogram.
- Close your session.

### Climate App
Create a Flask API with the following routes:

- **/**: Welcome page with available routes.
- **/api/v1.0/precipitation**: Return last 12 months of precipitation data as JSON.
- **/api/v1.0/stations**: Return a JSON list of stations.
- **/api/v1.0/tobs**: Return temperature observations of the most-active station for the last year.
- **/api/v1.0/<start> and /api/v1.0/<start>/<end>**: Return min, avg, and max temperatures for a specified date range.

## Code Source
- Learning Assistant
- GitHub location: [https://github.com/jeffjunohkim/sqlalchemy-challenge.git](https://github.com/jeffjunohkim/sqlalchemy-challenge.git)
