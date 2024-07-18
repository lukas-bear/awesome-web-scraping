# Awesome Web Scraping

A comprehensive collection of web scraping resources, tools, and libraries.

## Contents

- [Core Libraries](#core-libraries)
- [Specialized Tools](#specialized-tools)
  - [Network Utilities](#network-utilities)
  - [HTML/XML Processing](#htmlxml-processing)
  - [Text Processing](#text-processing)
  - [Data Formats](#data-formats)
- [Browser Automation](#browser-automation)
  - [Headless Browsers](#headless-browsers)
  - [Testing Frameworks](#testing-frameworks)
  - [Browser Extensions](#browser-extensions)
  - [Anti-detect Browsers](#anti-detect-browsers)
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
* [Go](go.md) - Collection of modern libraries like Colly, Chromedp, Arachnid, and Soup, with built-in concurrent processing support
* [Java](java.md) - Comprehensive set of tools including JSoup, Selenium WebDriver, Apache HttpComponents and Heritrix for enterprise crawling
* [JavaScript/Node.js](javascript.md) - Features Puppeteer, Cheerio, Playwright, and Axios, with strong HTTP clients and browser automation capabilities
* [Perl](perl.md) - Established libraries like WWW::Mechanize, HTML::Parser, LWP, and Mojo for text processing and web scraping
* [PHP](php.md) - Includes Goutte, Symfony DomCrawler, PHP Simple HTML DOM Parser, and Guzzle for web scraping and automation
* [Python](python.md) - Rich ecosystem featuring Scrapy, pyspider, BeautifulSoup, lxml, and Selenium, with extensive text processing and automation tools
* [R](r.md) - Data-focused tools including rvest, httr, xml2, and RSelenium, with strong integration to the tidyverse ecosystem
* [Ruby](ruby.md) - Features Nokogiri, Mechanize, Kimurai framework, and HTTParty, with elegant APIs for web scraping and parsing
* [Rust](rust.md) - Modern tooling with reqwest, scraper, tokio, and tungstenite for high-performance async scraping

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

### Anti-detect Browsers
* [Multilogin](https://multilogin.com)
* [AdsPower ](https://www.adspower.com)
* [GoLogin](https://gologin.com)
* [Incogniton](https://incogniton.com)
* [Dolphin Anty](https://dolphin-anty.com)
* [MoreLogin](https://www.morelogin.com)
* [Lalicat](https://www.lalicat.com)
* [HideMyAcc](https://hidemyacc.com)
* [BitBrowser](https://www.bitbrowser.net)
* [Ghost Browser](https://ghostbrowser.com)

## Anti-Bot Solutions

### Proxy Services
* [anyIP.io](https://anyip.io/) - Reliable proxy solutions, solid mobile proxies
* [Bright Data](https://brightdata.com/) - Enterprise proxy network
* [Oxylabs](https://oxylabs.io/) - Proxy and scraping solutions
* [ScraperAPI](https://www.scraperapi.com/) - Proxy API service
* [IPRotate](https://www.iprotatepro.com/) - IP rotation service
* [Smartproxy](https://smartproxy.com/) – Residential and datacenter proxies
* [SOAX](https://soax.com/) – Rotating residential and mobile proxies
* [ProxyEmpire](https://proxyempire.io/) – Ok residential and mobile proxies
* [NetNut](https://netnut.io/) – ISP proxies with high uptime

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
