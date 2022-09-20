## Expected outcome:

A git repository with dataset and script located in GitHub.
A short (~2-3 minutes) video presentation of your git repository explaining what you have done and how it works. Please, use https://loom.com/ or similar software. We would like to assess your presentation skills so having your camera on would be a good advantage.

## Challenge

- Write a script to get a reproducible normalized CSV data file of Road Safety Facts and Figures in the EU.
- Include both script and your resulting data. 
- The documentation should be included in the README.md file and it must be clear to follow.

## More details:

- Use the following Wikipedia page and get the data from the “European Union Road Safety Facts and Figures” table: https://en.wikipedia.org/wiki/Road_safety_in_Europe
- Resulting CSV file should only include the following columns: Country, Year, Area, Population, GDP per capita, Population density, Vehicle ownership, Total road deaths, Road deaths per Million Inhabitants. Note that “Year” column value is always 2018.
- Data should be sorted by “Road deaths per Million Inhabitants” column.
- We want a script for this and we want this script to be in python, so that you can demonstrate your knowledge of this given programming languages.
- Your git repo should include all dependencies in standard way so that it can be run in the CI/CD.
- Please, use simple and built-in libraries where possible rather than use a framework.

## Bonus items:

- Make your repository into a Tabular Data Package - here’s a [guide](https://datahub.io/docs/data-packages/publish-tabular).
Build a chart from the data to display some interesting insight. Feel free to play around with the visualization.
Make sure your chart is deployed to GitHub pages or somewhere else so we can take a look.
