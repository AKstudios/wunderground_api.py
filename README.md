# wunderground_api
Python script to extract historical hourly weather data from any weather station and between any two dates.

## Prerequistes
Python 3.6+ (for pyppeteer & asyncio)

[pandas](https://pandas.pydata.org/)

[pyppeteer](https://pypi.org/project/pyppeteer/)

[BeautifulSoup 4](https://pypi.org/project/beautifulsoup4/)


## How to use
1. Use [Wundermap](https://www.wunderground.com/wundermap) to find your PWS station ID
2. Enter start date on line 10 in YYYY-MM-DD format
3. Enter end date on line 11 in YYYY-MM-DD format
4. Enter station ID on line 12 between single quotes
5. Weather data will be saved in individual csv files for each day (takes a few seconds per date)