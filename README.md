# I310D Fall 2023 Coding Assignment 1
Data curation and visualization; web scraping and statistical analysis.

## Goal of this project
The objective of this assignment is to demonstrate data curation skills by following proper practices of reproducibile research and publish the dataset for others.

## APIs
- [BeautifulSoup](https://tedboy.github.io/bs4_doc/)
- [Pandas](https://pandas.pydata.org/docs/reference/index.html)
- [Numpy](https://numpy.org/doc/stable/reference/)
- [SciPy](https://docs.scipy.org/doc/scipy/reference/)
- [matplotlib](https://matplotlib.org/stable/api/index.html)
- [Requests](https://requests.readthedocs.io/en/latest/)

## License 
[MIT License](https://opensource.org/license/mit/)

## Data Source
- [Wikipedia: Demographics of South Korea](https://en.wikipedia.org/wiki/Demographics_of_South_Korea)
  - Original data: [United Nations](https://www.un.org/en/about-us/terms-of-use)
 
## About the project
The data collected from the Wikipedia represents demographics, especially the total population, numbers of birth and death, natural change, and fertility rate of South Korea from 1925 to 2022 (the data can be found [here](https://en.wikipedia.org/wiki/Demographics_of_South_Korea)).
### Data type and description
- **Year** (year)
- **Average population** (int): the arithmetic mean of the population on 1st January of two consecutive years
- **Live births** (int)
- **Deaths** (int)
- **Natural change** (int): # of births - # of deaths
- **Crude birth rate (per 1000)** (float): births per year per 1000 inhabitants
- **Crude death rate (per 1000)** (float): deaths per year per 1000 inhabitants
- **Natural change (per 1000)** (float): the ratio of natural change per year per 1000 inhabitants
- **Total fertility rate (TFR)** (float): the sum of the age-specific birth rates multiplied by five
### Analysis
The natural change in population by year was selected to demonstrate the population change in South Korea as it effectively shows the rate of change in total population. The population drastically increased until around 1973; however, since then, the population declined and eventually reached below zero in around 2020. As the country has been experiencing constant decline in population, it is anticipated to do so in the upcoming years as well. 
### Potential issues
The data only shows registered number of population, births, and deaths; the precise data is not available. 
