# R Web Scraping

This list contains R libraries related to web scraping and data processing.

* [Network](#network)
* [Web-scraping Frameworks](#web-scraping-frameworks)
* [HTML/XML Parsing](#htmlxml-parsing)
* [Text Processing](#text-processing)
* [Specific Formats Processing](#specific-formats-processing)
* [Natural Language Processing](#natural-language-processing)
* [Browser Automation and Emulation](#browser-automation-and-emulation)
* [Multiprocessing](#multiprocessing)
* [Queue](#queue)
* [Email](#email)
* [URL and Network Address Manipulation](#url-and-network-address-manipulation)
* [Web Content Extracting](#web-content-extracting)
* [Asynchronous](#asynchronous)
* [WebSocket](#websocket)
* [DNS Resolving](#dns-resolving)
* [Computer Vision](#computer-vision)
* [Proxy Server](#proxy-server)
* [Other R Lists](#other-r-lists)

## Network

* General
  * [httr](https://github.com/r-lib/httr) - Tools for working with URLs and HTTP
  * [curl](https://github.com/jeroen/curl) - Modern and flexible web client
  * [RCurl](https://cran.r-project.org/package=RCurl) - General network client interface
  * [request](https://github.com/sckott/request) - HTTP client with retry functionality
  * [crul](https://github.com/ropensci/crul) - HTTP client with async support
  * [jsonlite](https://github.com/jeroen/jsonlite) - JSON parser and generator

* Asynchronous
  * [promises](https://github.com/rstudio/promises) - Async programming support
  * [future](https://github.com/HenrikBengtsson/future) - Unified parallel and distributed processing
  * [async](https://github.com/djnavarro/async) - Asynchronous HTTP requests

## Web-scraping Frameworks

* Full Featured Crawlers
  * [rvest](https://github.com/tidyverse/rvest) - Simple web scraping for R
  * [Rcrawler](https://github.com/salimk/Rcrawler) - R web crawler and scraper
  * [RSelenium](https://github.com/ropensci/RSelenium) - R bindings for Selenium
  * [splashr](https://github.com/hrbrmstr/splashr) - Splash Web Scraping Client

* Other
  * [polite](https://github.com/dmi3kno/polite) - Be nice on the web
  * [webdriver](https://github.com/ropensci/webdriver) - 'WebDriver' Client

## HTML/XML Parsing

* [xml2](https://github.com/r-lib/xml2) - Parse XML and HTML
* [XML](https://cran.r-project.org/package=XML) - Tools for parsing XML
* [selectr](https://github.com/sjp/selectr) - CSS selector engine
* [htmltools](https://github.com/rstudio/htmltools) - Tools for HTML generation
* [htmlwidgets](https://github.com/ramnathv/htmlwidgets) - HTML widgets framework
* [htmltab](https://github.com/crubba/htmltab) - HTML table extraction

## Text Processing

* General
  * [stringr](https://github.com/tidyverse/stringr) - String manipulation made easy
  * [stringi](https://github.com/gagolews/stringi) - Fast string processing
  * [rebus](https://github.com/richierocks/rebus) - Build regular expressions
  * [textclean](https://github.com/trinker/textclean) - Text cleaning tools

* Character Encoding
  * [enc](https://github.com/yihui/enc) - Portable charset encodings
  * [readr](https://github.com/tidyverse/readr) - Read rectangular text data

* Text Analysis
  * [tidytext](https://github.com/juliasilge/tidytext) - Text mining using tidy tools
  * [quanteda](https://github.com/quanteda/quanteda) - Quantitative text analysis
  * [tm](https://cran.r-project.org/package=tm) - Text mining framework

## Specific Formats Processing

* General
  * [jsonlite](https://github.com/jeroen/jsonlite) - JSON parser
  * [yaml](https://github.com/viking/r-yaml) - YAML parser and emitter
  * [readxl](https://github.com/tidyverse/readxl) - Excel files reader
  * [openxlsx](https://github.com/awalker89/openxlsx) - Excel file manipulation

* Document Processing
  * [pdftools](https://github.com/ropensci/pdftools) - Text extraction from PDF
  * [tesseract](https://github.com/ropensci/tesseract) - OCR engine
  * [docxtractr](https://github.com/hrbrmstr/docxtractr) - Extract data from docx files
  * [tabulizer](https://github.com/ropensci/tabulizer) - PDF table extraction

## Natural Language Processing

* [tidytext](https://github.com/juliasilge/tidytext) - Text mining using tidy data
* [spacyr](https://github.com/quanteda/spacyr) - R wrapper to spaCy NLP
* [tokenizers](https://github.com/ropensci/tokenizers) - Fast tokenization tools
* [text2vec](https://github.com/dselivanov/text2vec) - Text vectorization
* [udpipe](https://github.com/bnosac/udpipe) - Tokenization, tagging, lemmatization
* [word2vec](https://github.com/bmschmidt/wordVectors) - Word embeddings

## Browser Automation and Emulation

* [RSelenium](https://github.com/ropensci/RSelenium) - R Selenium WebDriver client
* [chromote](https://github.com/rstudio/chromote) - Chrome Remote Interface
* [webdriver](https://github.com/ropensci/webdriver) - WebDriver protocol client
* [phantomjs](https://github.com/wch/webshot) - PhantomJS automation

## Multiprocessing

* [parallel](https://stat.ethz.ch/R-manual/R-devel/library/parallel/doc/parallel.pdf) - Parallel processing support
* [future](https://github.com/HenrikBengtsson/future) - Unified parallel processing
* [foreach](https://github.com/RevolutionAnalytics/foreach) - Parallel loops
* [doParallel](https://github.com/RevolutionAnalytics/doparallel) - Parallel backend

## Queue

* [taskscheduleR](https://github.com/bnosac/taskscheduleR) - Task scheduling
* [rzmq](https://github.com/ropensci/rzmq) - R bindings for ZeroMQ
* [future.queue](https://github.com/HenrikBengtsson/future.queue) - Job queue processing
* [jobqueue](https://github.com/wush978/JobQueue) - Parallel job queue

## Email

* [emayili](https://github.com/datawookie/emayili) - Email sending
* [gmailr](https://github.com/r-lib/gmailr) - Access Gmail API
* [blastula](https://github.com/rstudio/blastula) - Email automation
* [mailR](https://github.com/rpremraj/mailR) - Interface to Apache Commons Email

## URL and Network Address Manipulation

* URL
  * [urltools](https://github.com/Ironholds/urltools) - URL manipulation tools
  * [httr](https://github.com/r-lib/httr) - URL handling functions

* Network Address
  * [iptools](https://github.com/hrbrmstr/iptools) - IP address tools
  * [ipaddress](https://github.com/davidchall/ipaddress) - IP address manipulation

## Web Content Extracting

* Text and Meta Data
  * [boilerpipeR](https://github.com/kohlschutter/boilerpipe-r) - Content extraction
  * [readtext](https://github.com/quanteda/readtext) - Text file reading
  * [webshot](https://github.com/wch/webshot) - Website screenshots

## Asynchronous

* [promises](https://github.com/rstudio/promises) - Async programming
* [future](https://github.com/HenrikBengtsson/future) - Async computation
* [later](https://github.com/r-lib/later) - Delay execution

## WebSocket

* [websocket](https://github.com/rstudio/websocket) - WebSocket client
* [httpuv](https://github.com/rstudio/httpuv) - HTTP and WebSocket server
* [sockjs](https://github.com/rstudio/sockjs) - SockJS client

## DNS Resolving

* [getip](https://github.com/hrbrmstr/getip) - IP address tools
* [resolve](https://github.com/hrbrmstr/resolve) - DNS resolution
* [dnsquery](https://github.com/hrbrmstr/dnsquery) - DNS lookup tools

## Computer Vision

* [magick](https://github.com/ropensci/magick) - Advanced image processing
* [imager](https://github.com/dahtah/imager) - Image processing library
* [opencv](https://github.com/swarm-lab/Rvision) - OpenCV bindings
* [tesseract](https://github.com/ropensci/tesseract) - OCR engine

## Proxy Server

* [httr](https://github.com/r-lib/httr) - Proxy configuration
* [curl](https://github.com/jeroen/curl) - Proxy support
* [RCurl](https://cran.r-project.org/package=RCurl) - Proxy handling

## Other R Lists

* [CRAN Task Views](https://cran.r-project.org/web/views/) - Curated package lists
* [Awesome R](https://github.com/qinwf/awesome-R) - Curated R resources
* [rOpenSci Packages](https://ropensci.org/packages/) - Scientific R packages
