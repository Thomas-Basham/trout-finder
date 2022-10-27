# Trout Finder

[![Python application](https://github.com/Thomas-Basham/trout-finder/actions/workflows/python-app.yml/badge.svg)](https://github.com/Thomas-Basham/trout-finder/actions/workflows/python-app.yml)

**Author:** Thomas Basham

[wa-stocked-trout-finder.herokuapp.com](https://wa-stocked-trout-finder.herokuapp.com)

![Python application](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python application](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Python application]( 	https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)

A Full Stack Flask Web App used for displaying the most recent lakes that were stocked with trout in Washington State on an interactive map

## Tech Used 

* Flask

* Beautiful Soup (Data scraped from [WDFW Stock Report](https://wdfw.wa.gov/fishing/reports/stocking/trout-plants))

* Pandas

* Folium

* Postgresql

* Heroku Scheduler(To schedule webscraping daily)

* Google V3 Geolocator(To get lat/lon of lakes)


## Resources
[WDFW Stock Report](https://wdfw.wa.gov/fishing/reports/stocking/trout-plants)

[SqAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/quickstart/)

[Pandas to SQL](https://towardsdatascience.com/upload-your-pandas-dataframe-to-your-database-10x-faster-eb6dc6609ddf)

[measure-driving-distance-time-and-plot-routes-between-two-geographical-locations](https://medium.com/analytics-vidhya/measure-driving-distance-time-and-plot-routes-between-two-geographical-locations-using-python-39995dfea7e)

### TODO
* Add Email Alerts 
* Add user selected map boundary alerts 
