# Basic-Web-Scraper-using-Python

## Introduction

A web scraper is a bot that is used to extract contents and data from a website. This information is then collected and stored in a format that can be processed and is useful to the user such as a CSV file. A web scraper automates the task of collecting data all over the internet and can be a part of a ML pipeline to make the workflow more efficient.

A web scraper can be a browser extension or tools like selenium can be used for web scarping. Here, the beautiful soup library is used to fetch the contents of a online book store.

## Implementation

![Books.toscrape](https://github.com/BoosterGold98/Basic-Web-Scraper-using-Python/blob/master/Book%20Store.JPG)

The site used can be accessed [here](http://books.toscrape.com/)

The information that is scraped are the Book Title, Book Price and Book Rating. The BeautifulSoup library is used to fetch the HTML code of the site and then to access information in the tags and fetch them. Frameworks like Scrapy can also be used for this purpose. 

## Testing

There are various sites that prohibit the act of scraping or put restrictions to it. Many sites prohibit the act of scraping unless the scraper has explicit permission. Most of these restrictions can be viewed on robots.txt available on the site.

Examples:

* [Amazon](https://www.amazon.in/robots.txt)
* [Facebook](https://www.facebook.com/robots.txt)

Thus, [toScrape](http://toscrape.com) is a good place to practice and implementing scraping bots.
