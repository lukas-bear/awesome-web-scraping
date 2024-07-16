# Python Web Scraping

This list contains Python libraries related to web scraping and data processing.

## Contents

* [Network](#network)
* [Web Scraping](#web-scraping)
* [HTML/XML](#htmlxml)
* [Text Processing](#text-processing)
* [Structured Formats](#structured-formats)
* [Natural Language Processing](#natural-language-processing)
* [Browser Automation](#browser-automation)
* [Multiprocessing](#multiprocessing)
* [Queue Systems](#queue-systems)
* [Email](#email)
* [URL and Network Address](#url-and-network-address)
* [Web Content Extraction](#web-content-extraction)
* [WebSocket](#websocket)
* [DNS Resolving](#dns-resolving)
* [Proxy Server](#proxy-server)
* [Cloud Computing](#cloud-computing)
* [JavaScript Engine](#javascript-engine)
* [Captcha Solving](#captcha-solving)

## Network

### General
* [requests](https://github.com/kennethreitz/requests) - Python HTTP library for humans
* [urllib3](https://github.com/shazow/urllib3) - Thread-safe HTTP client with connection pooling
* [httpx](https://github.com/encode/httpx) - Next generation HTTP client
* [pycurl](https://github.com/pycurl/pycurl) - Python interface to libcurl
* [urllib](https://docs.python.org/3/library/urllib.html) - URL handling modules (stdlib)
* [RoboBrowser](https://github.com/jmcarp/robobrowser) - Simple web scraping browser
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - Website automation
* [PySocks](https://github.com/Anorov/PySocks) - SOCKS proxy client

### Asynchronous
* [aiohttp](https://github.com/aio-libs/aiohttp) - Async HTTP client/server framework
* [treq](https://github.com/dreid/treq) - Requests-like API on Twisted
* [grequests](https://github.com/kennethreitz/grequests) - Async HTTP for humans

### Low Level
* [socket](https://docs.python.org/3/library/socket.html) - Low-level networking interface
* [pyOpenSSL](https://github.com/pyca/pyopenssl) - OpenSSL wrapper
* [scapy](https://github.com/secdev/scapy) - Packet manipulation library
* [impacket](https://github.com/SecureAuthCorp/impacket) - Network protocol toolkit

## Web Scraping

### Frameworks
* [scrapy](https://github.com/scrapy/scrapy) - Comprehensive scraping framework
* [pyspider](https://github.com/binux/pyspider) - Distributed crawler system
* [cola](https://github.com/chineking/cola) - Distributed crawling framework
* [frontera](https://github.com/scrapinghub/frontera) - Crawl frontier framework
* [autoscraper](https://github.com/alirezamika/autoscraper) - Smart web scraper
* [ScrapegraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai) - AI-powered scraping

### Tools
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy
* [ScrapydWeb](https://github.com/my8100/scrapydweb) - Scrapy cluster manager
* [Starbelly](https://github.com/HyperionGray/starbelly) - User-friendly crawler
* [Gerapy](https://github.com/Gerapy/Gerapy) - Distributed crawler manager

### Protection Bypass
* [cloudscraper](https://github.com/venomous/cloudscraper) - Cloudflare bypass module

## HTML/XML

### HTML Processing
* [beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/) - HTML/XML parsing
* [lxml](https://github.com/lxml/lxml/) - Fast XML/HTML processor
* [html5lib](https://github.com/html5lib/html5lib-python) - Standards-compliant parser
* [pyquery](https://github.com/gawel/pyquery) - jQuery-like HTML manipulation

### XML Tools
* [xmltodict](https://github.com/martinblech/xmltodict) - XML to dict converter
* [untangle](https://github.com/stchris/untangle) - Simple XML parser
* [xmldict](https://github.com/martinblech/xmltodict) - XML feel like JSON

### Metadata
* [extruct](https://github.com/scrapinghub/extruct) - Metadata extraction
* [MarkupSafe](https://github.com/mitsuhiko/markupsafe) - Markup string handling

## Text Processing

### General
* [difflib](https://docs.python.org/3/library/difflib.html) - Text difference tools
* [Levenshtein](https://github.com/ztane/python-Levenshtein/) - String similarity
* [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy string matching
* [ftfy](https://github.com/LuminosoInsight/python-ftfy) - Text encoding fixes

### Character Encoding
* [chardet](https://github.com/chardet/chardet) - Character detection
* [cchardet](https://github.com/PyYoshi/cChardet) - Fast character detection
* [unidecode](https://pypi.python.org/pypi/Unidecode) - Unicode text conversion

### User-Agent
* [fake-useragent](https://github.com/hellysmile/fake-useragent) - Browser UA faker
* [user_agent](https://github.com/lorien/user_agent) - User-Agent generator
* [python-user-agents](https://github.com/selwin/python-user-agents) - UA parser

### Date and Time
* [dateutil](https://github.com/dateutil/dateutil) - Date utilities
* [dateparser](https://github.com/scrapinghub/dateparser) - Human date parsing
* [ciso8601](https://github.com/closeio/ciso8601) - Fast ISO 8601 parser

## Structured Formats

### Office Documents
* [python-docx](https://github.com/python-openxml/python-docx) - Word documents
* [openpyxl](https://github.com/pandas-dev/pandas) - Excel processing
* [PyPDF2](https://github.com/mstamy2/PyPDF2) - PDF manipulation
* [tablib](https://github.com/kennethreitz/tablib) - Tabular datasets

### Data Formats
* [pandas](https://github.com/pandas-dev/pandas) - Data analysis toolkit
* [pyyaml](https://github.com/yaml/pyyaml) - YAML parser
* [msgpack](https://github.com/msgpack/msgpack-python) - MessagePack serialization
* [orjson](https://github.com/ijl/orjson) - Fast JSON library

## Natural Language Processing

* [nltk](https://github.com/nltk/nltk) - Natural Language Toolkit
* [spacy](https://github.com/explosion/spaCy) - Industrial NLP
* [gensim](https://github.com/RaRe-Technologies/gensim) - Topic modeling
* [textblob](https://github.com/sloria/TextBlob) - Simple text processing
* [jieba](https://github.com/fxsjy/jieba) - Chinese text segmentation

## Browser Automation

### Drivers
* [selenium](https://github.com/SeleniumHQ/selenium) - Browser automation
* [playwright](https://github.com/microsoft/playwright-python) - Modern automation
* [puppeteer-python](https://github.com/pyppeteer/pyppeteer) - Chrome automation
* [helium](https://github.com/mherrmann/selenium-python-helium) - Selenium wrapper

### Frameworks
* [splinter](https://github.com/cobrateam/splinter) - Browser abstraction
* [botasaurus](https://github.com/omkarcloud/botasaurus) - Scraping framework
* [requestium](https://github.com/tryolabs/requestium) - Requests + Selenium

## Cloud Computing

* [minigun-requests](https://github.com/umihico/minigun-requests) - Cloud-based scraping
* [pythonista-chromeless](https://github.com/umihico/pythonista-chromeless) - AWS Lambda scraping
* [picloud](http://docs.picloud.com/) - Cloud code execution

## JavaScript Engine

* [Js2Py](https://github.com/PiotrDabkowski/Js2Py) - JavaScript to Python translator
* [v8eval](https://github.com/sony/v8eval/) - V8 JavaScript engine bindings

## Captcha Solving

* [captcha_solver](https://github.com/lorien/captcha_solver) - Universal captcha API
* [python-anticaptcha](https://github.com/ad-m/python-anticaptcha) - Anti-captcha.com client
* [python3-anticaptcha](https://github.com/AndreiDrang/python3-anticaptcha) - Captcha service API
* [unicaps](https://github.com/sergey-scat/unicaps) - Unified captcha API
