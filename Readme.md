# Allris-Scraper

Scrapping data from [ratsinfo.leipzig.de](https://ratsinfo.leipzig.de/)

## Requirements

* Python 2.7
* pip 1.5.6 
* virtualenv (optional)
* virtualenvwrapper (optional)


## Installation and scrape

* Make a new virtualenv and switch to it. (optional)
* Install requirements with:
```
pip install -r requirements.txt
```

* Run with
```
scrapy crawl vo_all
```

## Thoughts

* implement caching or db
* update data from last scrape date

## Todo
* field originator needs to be validated
