# UdemyCourseProject3-imdb

This is a Udemy tutorial to learn Scrapy. Modern Web Scraping with Python using Scrapy Splash Selenium

Link to scrapy: https://www.imdb.com/search/title/?groups=top_250&sort=user_rating

# Scrapy command:
- run scrapy script -----> scrapy crawl best_movies

- run scrapy shell ------> scrapy shell

- Create New Scrpay Project -------> scrapy startproject imbd

- You can start your first spider with: 
  - cd imbd 
  - scrapy genspider example example.com

- Create Scrapy spider -------> scrapy genspider best_movies imdb.com

- Create Scrapy spider with template -------> scrapy genspider -t crawl best_movies imdb.com

- scrapy genspider -l
  - Available templates:
      basic
      crawl
      csvfeed
      xmlfeed

- Export Excel Command -----> scrapy crawl best_movies -o movies_dataset.csv
- Export JSON Command ------> scrapy crawl best_movies -o movies_dataset.json

# Anaconda command:
- install dependencies ----> conda install -c conda-forge scrapy==1.6 pylint autopep8 -y
- install iPython ---------> conda install iPython
