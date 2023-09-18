## Assignment Overview

This assignment consists of two the following two technical deliverables:

### Deliverable 1: Extracting Titles and Preview Text from Mars News Articles

- **Part 1 (File: part_1_mars_news.ipynb)**: We used automated web browsing with Splinter to visit the Mars news site and extracted the HTML code using Beautiful Soup. This part is worth 10 points.
- **Part 2**: We scraped and extracted the titles and preview text from the news articles and structured this information in a list of dictionaries.

### Deliverable 2: Extracting and Analyzing Mars Weather Data, Presented in Tabular Form

- **Part 2 (File: part_2_mars_weather.ipynb)**: We extracted the Mars weather data from an HTML table and transformed it into a Pandas DataFrame. We employed either Pandas, Splinter, or Beautiful Soup as needed.
- The DataFrame was meticulously organized with correct column headings and data types.

### Data Analysis

We performed data analysis to answer the following questions:

1. How many months exist on Mars?
2. How many Martian days' worth of data are available?

Additionally, we conducted analysis to determine:

- The month with the lowest average temperature and the one with the highest, with corresponding data visualizations.
- The month with the lowest average atmospheric pressure and the one with the highest, with corresponding data visualizations.
- An estimation of the number of terrestrial days in a Martian year.

### Data Export

To facilitate further use, we exported the DataFrame to a CSV file (File: mars_weather_data.csv).
