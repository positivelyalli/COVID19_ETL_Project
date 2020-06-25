# COVID-19 ETL Project
## How effective is shelter-in-place in fighting COVID-19?

Analysis of COVID-19 deaths and cases by state and what measures affected the growth rate. The data is from John Hopkins and scraping the New York Times to create a PostGres SQL database.

## Getting Started

1. Use [WHO github dataset](https://github.com/WorldHealthOrganization/app)-vicky (by state)
    - Current Cases, New Cases, Deaths, New Deaths by date
2. Scrape [NY Times](https://www.nytimes.com/interactive/2020/us/coronavirus-stay-at-home-order.html ) article - Alli
    - Measures put in place by date
3. Retrieve from [Census API](https://www.census.gov/data/developers.html) - Sowmya
    - Age
    - Population
4. Clean NY Times SIP data by State: Alli
    - New York
        - Stay at home, effective March 22 at 8 p.m.
    - New Jersey
        - Stay at home, effective March 21 at 9 p.m.
    - California
        - Stay at home, effective March 19
    - Washington
        - Stay at home, effective March 23
    - Michigan
        - Stay at home, effective March 24 at 12:01 a.m
    - Florida
        - No state measures but there are county
5. Clean each dataset - Alli, Weiqi, Sowmya
6. Combine datasets - Alli, Weiqi, Sowmya
7. Create plots
    - Gmap with size bubbles for deaths by state - Alli
    - Cases overtime with a way to show where they did shelter in place - Vicky
    - Mortality rate with total population percent  of seniors with pvalue- Sowmya

### Team
- [Alli Kruger](https://github.com/positivelyalli)
- [Weiqi Liang](https://github.com/liangweiqi2)
- [Sowmya Srinivasan](https://github.com/sowmyasrinivasan)


### Built With

Jupyter Notebook
Pandas
Python
Matplotlib
BeautifulSoup


## Acknowledgments

* [John Hopkins University](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_daily_reports/03-25-2020.csv)
* [NY Times](https://www.nytimes.com/interactive/2020/us/coronavirus-stay-at-home-order.html )
* [Census API](https://www.census.gov/data/developers.html)
