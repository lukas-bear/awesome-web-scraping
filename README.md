# Awesome Web Scraping [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A comprehensive collection of web scraping resources, tools, and libraries.

## Contents

- [Core Libraries](#core-libraries)
  - [Python](#python)
  - [JavaScript/Node.js](#javascriptnodejs)
  - [Java](#java)
  - [Go](#go)
  - [Ruby](#ruby)
  - [PHP](#php)
  - [Rust](#rust)
  - [Perl](#perl)
  - [R](#r)
- [Specialized Tools](#specialized-tools)
  - [Network Utilities](#network-utilities)
  - [HTML/XML Processing](#htmlxml-processing)
  - [Text Processing](#text-processing)
  - [Data Formats](#data-formats)
- [Browser Automation](#browser-automation)
  - [Headless Browsers](#headless-browsers)
  - [Testing Frameworks](#testing-frameworks)
  - [Browser Extensions](#browser-extensions)
- [Anti-Bot Solutions](#anti-bot-solutions)
  - [Proxy Services](#proxy-services)
  - [CAPTCHA Solvers](#captcha-solvers)
  - [Browser Fingerprinting](#browser-fingerprinting)
- [Data Processing](#data-processing)
  - [Natural Language Processing](#natural-language-processing)
  - [Data Cleaning](#data-cleaning)
  - [Data Storage](#data-storage)
- [Best Practices](#best-practices)
  - [Rate Limiting](#rate-limiting)
  - [Error Handling](#error-handling)
  - [Data Management](#data-management)
- [Resources](#resources)
  - [Documentation](#documentation)
  - [Tutorials](#tutorials)
  - [Community](#community)
- [How to Contribute](#Contributing)

## Core Libraries

### Python
* [Scrapy](https://github.com/scrapy/scrapy) - Comprehensive web scraping framework
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) - HTML/XML parsing library
* [lxml](https://github.com/lxml/lxml/) - Fast XML and HTML processing
* [requests](https://github.com/psf/requests) - HTTP library for humans
* [aiohttp](https://github.com/aio-libs/aiohttp) - Asynchronous HTTP client/server
* [pyspider](https://github.com/binux/pyspider) - Web crawler with GUI interface
* [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - Web automation library

### JavaScript/Node.js
* [Puppeteer](https://github.com/puppeteer/puppeteer) - Chrome automation API
* [Cheerio](https://github.com/cheeriojs/cheerio) - Fast jQuery-like parsing
* [Axios](https://github.com/axios/axios) - Promise based HTTP client
* [node-crawler](https://github.com/bda-research/node-crawler) - Web crawler with jQuery
* [Crawlee](https://github.com/apify/crawlee) - Web scraping and browser automation
* [Nightmare](https://github.com/segmentio/nightmare) - High-level browser automation

### Java
* [JSoup](https://jsoup.org/) - HTML parsing and manipulation
* [Selenium WebDriver](https://www.selenium.dev/) - Browser automation
* [Apache HttpClient](https://hc.apache.org/) - HTTP client library
* [crawler4j](https://github.com/CrawlerPack/crawler4j) - Multithreaded crawler
* [webmagic](https://github.com/code4craft/webmagic) - Distributed crawler framework

### Go
* [Colly](https://github.com/gocolly/colly) – Fast and elegant scraping framework, with features like cookie handling, automatic request delays, and parallel crawling.
* [Fetchbot](https://github.com/PuerkitoBio/fetchbot) - A simple and flexible web crawler that follows the robots.txt policies and crawl delays.
* [Goquery](https://github.com/PuerkitoBio/goquery) – A jQuery-like API for parsing and manipulating HTML documents.
* [Rod](https://github.com/go-rod/rod) – A high-level browser automation framework powered by Chromium DevTools.
* [Playwright-go](https://github.com/playwright-community/playwright-go) – Go bindings for Playwright, ideal for headless and non-headless browser automation.
* [Gocrawl](https://github.com/PuerkitoBio/gocrawl) - Polite, slim and concurrent web crawler.

### Ruby
* [Nokogiri](https://github.com/sparklemotion/nokogiri) - HTML/XML parsing
* [Mechanize](https://github.com/sparklemotion/mechanize) - Automated web interaction
* [Kimurai](https://github.com/vifreefly/kimuraframework) - Modern scraping framework
* [Watir](https://github.com/watir/watir) - Ruby browser automation
* [Anemone](https://github.com/chriskite/anemone) - Web spider framework

### PHP
* [DiDOM](https://github.com/Imangazaliev/DiDOM) - A blazing-fast and easy-to-use HTML parser.
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - A lightweight PHP web scraper for effortless data extraction.
* [Crawler](https://www.crwlr.software/packages/crawler) - A powerful library for rapid web scraping and crawling development.
* [PHPCrawl](http://phpcrawl.cuab.de/) - A robust PHP framework for web crawling and spidering.
* [simple_html_dom](https://github.com/samacs/simple_html_dom) - Just a Simple HTML DOM library fork.

### Rust
* [Reqwest](https://docs.rs/reqwest/latest/reqwest/index.html) - HTTP client for making web requests
* [Scraper](https://github.com/rust-scraper/scraper) - HTML parsing and web scraping (based on html5ever)
* [Fantoccini](https://docs.rs/fantoccini/latest/fantoccini/) - Web automation using WebDriver
* [Headless_chrome](https://docs.rs/headless_chrome/latest/headless_chrome/) - Control Chrome for headless browsing
* [Spider](https://github.com/spider-rs/spider) - A web crawler and scraper

### Perl
* [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize) - Automated web interaction
* [Mojo::UserAgent](https://docs.mojolicious.org/Mojo/UserAgent) - Modern, non-blocking HTTP client
* [Web::Scraper](https://metacpan.org/pod/Web::Scraper) - DSL for web scraping
* [LWP::Simple](https://metacpan.org/pod/LWP::Simple) - Basic web requests
* [Scrappy](https://metacpan.org/pod/Scrappy) - Lightweight web crawling framework
* [WWW::Mechanize::Chrome](https://metacpan.org/pod/WWW::Mechanize::Chrome) - Headless browser automation

### R
* [rvest](https://cran.r-project.org/package=rvest) - Web scraping and HTML parsing
* [httr](https://cran.r-project.org/package=httr) - HTTP client for making web requests
* [RCurl](https://cran.r-project.org/package=RCurl) - HTTP and FTP client interface
* [xml2](https://cran.r-project.org/package=xml2) - XML and HTML parsing
* [RSelenium](https://cran.r-project.org/package=RSelenium) - Web automation via Selenium WebDriver
* [scrapeR](https://cran.r-project.org/package=scrapeR) - Basic web scraping framework
* [polite](https://cran.r-project.org/package=polite) - Web scraping while respecting robots.txt
* [webdriver](https://cran.r-project.org/package=webdriver) - Headless browser automation

## Specialized Tools

### Network Utilities
* [mitmproxy](https://mitmproxy.org/) - Interactive HTTPS proxy
* [Charles Proxy](https://www.charlesproxy.com/) - Web debugging proxy
* [Fiddler](https://www.telerik.com/fiddler) - Web debugging proxy
* [Proxychains](https://github.com/haad/proxychains) - Proxy chaining tool

### HTML/XML Processing
* [XPath](https://www.w3.org/TR/xpath-31/) - XML path language
* [CSS Selectors](https://www.w3.org/TR/selectors-4/) - Pattern matching syntax
* [html5lib](https://github.com/html5lib/) - HTML parser and serializer
* [xmltodict](https://github.com/martinblech/xmltodict) - XML to Python dict converter

### Text Processing
* [Dateparser](https://github.com/scrapinghub/dateparser) - Date parsing library
* [Ftfy](https://github.com/LuminosoInsight/python-ftfy) - Text encoding fixer
* [Price-parser](https://github.com/scrapinghub/price-parser) - Price extraction
* [Phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Phone number parsing

## Browser Automation

### Headless Browsers
* [Chrome](https://www.google.com/chrome/browser/) - Most widely supported
* [Firefox](https://www.mozilla.org/firefox/) - Open-source alternative
* [PhantomJS](https://phantomjs.org/) - Scriptable headless WebKit

### Testing Frameworks
* [Selenium](https://www.selenium.dev/) - Browser automation standard
* [Playwright](https://playwright.dev/) - Modern web testing
* [Cypress](https://www.cypress.io/) - JavaScript testing framework

## Anti-Bot Solutions

### Proxy Services
* [Bright Data](https://brightdata.com/) - Enterprise proxy network
* [Oxylabs](https://oxylabs.io/) - Proxy and scraping solutions
* [ScraperAPI](https://www.scraperapi.com/) - Proxy API service
* [IPRotate](https://www.iprotatepro.com/) - IP rotation service

### CAPTCHA Solvers
* [2captcha](https://2captcha.com/) - Human captcha solving
* [Anti-Captcha](https://anti-captcha.com/) - Automated solving
* [DeathByCaptcha](https://deathbycaptcha.com/) - API-based solving

### Browser Fingerprinting
* [puppeteer-extra-plugin-stealth](https://github.com/berstend/puppeteer-extra/tree/master/packages/puppeteer-extra-plugin-stealth)
* [selenium-stealth](https://github.com/diprajpatra/selenium-stealth)
* [undetected-chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver)

## Data Processing

### Natural Language Processing
* [NLTK](https://www.nltk.org/) - Natural Language Toolkit
* [spaCy](https://spacy.io/) - Industrial-strength NLP
* [TextBlob](https://textblob.readthedocs.io/) - Simplified text processing
* [langdetect](https://github.com/Mimino666/langdetect) - Language detection

### Data Storage
* [MongoDB](https://www.mongodb.com/) - Document database
* [Elasticsearch](https://www.elastic.co/) - Search and analytics
* [PostgreSQL](https://www.postgresql.org/) - Relational database
* [Redis](https://redis.io/) - In-memory data store

## Best Practices

### Rate Limiting
* Implement exponential backoff
* Respect robots.txt directives
* Use delays between requests
* Monitor response codes

### Error Handling
* Implement retry logic
* Log errors comprehensively
* Handle timeouts gracefully
* Monitor scraping health

### Data Management
* Validate extracted data
* Remove duplicates
* Store raw and processed data
* Document data schema

## Resources

### Documentation
* [Scrapy Documentation](https://docs.scrapy.org/)
* [Selenium Documentation](https://selenium.dev/documentation/)
* [Puppeteer Documentation](https://pptr.dev/)
* [Playwright Documentation](https://playwright.dev/docs/intro)

### Tutorials
* [Web Scraping Best Practices](https://www.scrapehero.com/web-scraping-best-practices/)
* [Scraping with Python](https://realpython.com/web-scraping-101-with-python/)
* [JavaScript Web Scraping Guide](https://www.browserless.io/blog/web-scraping-in-nodejs/)
* [Anti-Bot Bypass Techniques](https://medium.com/@selvaganesh93/how-to-bypass-anti-bot-protection-while-web-scraping-14bb87d1c326)

### Community
* [Stack Overflow](https://stackoverflow.com/questions/tagged/web-scraping)
* [Reddit r/webscraping](https://reddit.com/r/webscraping)
* [Scrapy Community](https://scrapy.org/community/)

---

## Contributing

Check the [Contribution Guidelines](CONTRIBUTING.md) before sending any updates.

You can [open an issue](https://github.com/lukas-bear/awesome-web-scraping/issues) or [create a new PR](https://github.com/lukas-bear/awesome-web-scraping/pulls) with your additions.
I'll make sure to check them quickly!
