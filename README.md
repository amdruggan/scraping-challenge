## Assignment Overview

This assignment consists of two the following two technical deliverables:

### Deliverable 1: Extracting Titles and Preview Text from Mars News Articles

- **Part 1 (File: part_1_mars_news.ipynb)**: We used automated web browsing with Splinter to visit the Mars news site and extracted the HTML code using Beautiful Soup.
- **Part 2**: We scraped and extracted the titles and preview text from the news articles and structured this information in a list of dictionaries.

### Deliverable 2: Extracting and Analyzing Mars Weather Data, Presented in Tabular Form

- **Part 2 (File: part_2_mars_weather.ipynb)**: We extracted the Mars weather data from an HTML table and transformed it into a Pandas DataFrame.
- The DataFrame was organized with correct column headings and data types.

### Data Analysis

We performed data analysis to answer the following questions:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * Find the average the minimum daily temperature for all of the months.
    * Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * Find the average the daily atmospheric pressure of all the months.
    * Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    * Visually estimate the result by plotting the daily minimum temperature.

Additionally, we conducted analysis to determine:

- The month with the lowest average temperature and the one with the highest, with corresponding data visualizations.
- The month with the lowest average atmospheric pressure and the one with the highest, with corresponding data visualizations.
- An estimation of the number of terrestrial days in a Martian year.

### Data Export

To facilitate further use, we exported the DataFrame to a CSV file (File: mars_weather_data.csv).
