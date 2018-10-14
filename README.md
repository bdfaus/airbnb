# Airbnb Data Wrangling

### Motivation

The goal of this repository is to uncover trends for either customers or renters on Airbnb
using data from Boston and Seattle homes, available from Kaggle.com.


### File Descriptions

The files in the Boston and Seattle folders are .csv files of data from Airbnb for their respective cities. There is also an ipython notebook of data analysis, exploration, and presentation.


### Libraries

Libraries necessary to run all cells in the Jupyter Notebook are as follows:
- random
- pandas
- numpy
- matplotlib
- bokeh
- seaborn


### Summary of Results

- The Boston Marathon correlates with the highest spike in Airbnb listing average prices.
- 'Number Accommodated' and 'Entire Apartment/House for Rent' had the highest correllation with average prices
- Obvious insights like high price at city center and high price at summer time held true
- One 'hidden'--as in, unobvious--zip code (outside of city center) ranked high (within top 5) of zip codes ordered by number of listings
- This 'hidden' zip code ranked 2nd in number of listings with prices under $100
- A correction in pricing occurred at the end of 2016 as number of available listings increased.
- There was one date in which it appears that Airbnb eliminated spam, duplicate, or otherwise not worthwhile listings as there was a sudden drop-off in number of listings from one day to the next.


### Licensing

The data files in this repository were provided by Kaggle.com at no cost.

They are provided under a CC0: Public Domain license: https://creativecommons.org/publicdomain/zero/1.0/
This is described on the "Overview" page here (for Boston data): https://www.kaggle.com/airbnb/boston/home
This is the link to the original data source (as provided on the kaggle page): http://insideairbnb.com/get-the-data.html


### Author

Ben Faus wrangled the data and created all the code/visualizations/observations you see in this notebook.
