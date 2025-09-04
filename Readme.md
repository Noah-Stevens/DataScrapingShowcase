# Data Scraping — Mars News & Weather — M11

This project demonstrates web scraping, data cleaning, and exploratory analysis using Python.  
It extracts information from static HTML pages, organizes it into structured datasets, and analyzes Martian weather.

## Repository Contents
- part_1_mars_news.ipynb — Scrape Mars news titles and previews
- part_2_mars_weather.ipynb — Parse, clean, and analyze Mars weather data
- mars_table.csv — Cleaned dataset of Martian daily weather
- LICENSE — GPL-3.0 License

## Project Overview
### Part 1 — Mars News
- Parse an HTML file containing NASA Mars news
- Extract titles and teaser text
- Build a clean Pandas DataFrame

### Part 2 — Mars Weather
- Scrape an HTML table of historical weather data on Mars
- Clean and convert data types
- Analyze:
  - Coldest and warmest months
  - Atmospheric pressure variation
  - Length of a Martian year
- Save cleaned dataset as mars_table.csv

## Tools & Libraries
- BeautifulSoup — HTML parsing
- Pandas — data wrangling
- Matplotlib / Plotly — visualization
- LXML — parser backend

## Quick Start
1. Clone the repo
   ```bash
   git clone https://github.com/Noah-Stevens/DataScraping_Challenge.git
   cd DataScraping_Challenge
   ```

2. Install dependencies
   ```bash
   pip install pandas beautifulsoup4 lxml requests matplotlib plotly
   ```

3. Run notebooks
   - part_1_mars_news.ipynb
   - part_2_mars_weather.ipynb

## License
GPL-3.0 License. See LICENSE file.

## Author
Noah Stevens  
[LinkedIn](https://www.linkedin.com/in/noah-stevens-2a47a3331/)

