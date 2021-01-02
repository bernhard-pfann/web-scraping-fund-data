# Web Scraping Fund Data &amp; Portfolio Analysis

- Created a tool that stratifies a user-defined portfolio of funds
- Scraped publicly available fund data from webpage www.fondsprofessionell.at
- Scraped publicly available fx rates from ECB to convert financials into common reporting currency

## Web Scraping
By providing a user defined list of the funds' ISIN's together with the number of fund certificates, the web driver is scraping detailed information of the respective instruments. Following data points can thereby be automatically retrieved:

- NAV
- Historical performance
- Top holdings
- Asset allocation
- Sector allocation
- Countries
- Currencies

## Portfolio Analysis
The gathered information is converted into the user-defined reporting currency. Therefore the web driver is scraping current spot rates published by ECB. Via various visualizations and underlying tables the portfolio is being depicted, allowing for informed decisions for further portfolio construction.

**Python Version:** 3.7

**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, selenium, flask, json, pickle
