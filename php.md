# PHP Web Scraping

This list contains PHP libraries related to web scraping and data processing.

## Contents

* [Network](#network)
* [Web-scraping Frameworks](#web-scraping-frameworks)
* [HTML/XML Parsing](#htmlxml-parsing)
* [Text Processing](#text-processing)
* [Specific Formats Processing](#specific-formats-processing)
* [Natural Language Processing](#natural-language-processing)
* [Browser Automation](#browser-automation)
* [Multiprocessing](#multiprocessing)
* [Queue](#queue)
* [Cloud Computing](#cloud-computing)
* [Email](#email)
* [URL Manipulation](#url-manipulation)
* [Web Content Extracting](#web-content-extracting)
* [Asynchronous](#asynchronous)
* [WebSocket](#websocket)
* [DNS Resolving](#dns-resolving)
* [Computer Vision](#computer-vision)
* [Geocoding](#geocoding)
* [API Clients](#api-clients)

## Network

* [Guzzle](https://github.com/guzzle/guzzle) - A comprehensive HTTP client
* [Buzz](https://github.com/kriswallsmith/Buzz) - Simple HTTP client
* [Requests](https://github.com/rmccue/Requests) - Simple HTTP library
* [HTTPFul](https://github.com/nategood/httpful) - Chainable HTTP client
* [Symfony HttpClient](https://github.com/symfony/http-client) - HTTP client component
* [HTTPlug](https://github.com/php-http/httplug) - HTTP client abstraction
* [PHP cURL](https://www.php.net/manual/en/book.curl.php) - Client URL library

## Web-scraping Frameworks

* [Goutte](https://github.com/fabpot/Goutte) - Simple web scraper
* [PHP Spider](https://github.com/mvdbos/php-spider) - Comprehensive web spider
* [Crawler](https://github.com/crwlrsoft/crawler) - Library for rapid crawler development
* [Roach](https://github.com/roach-php/core) - Port of Python's Scrapy
* [Spatie Crawler](https://github.com/spatie/crawler) - Easy to use crawler
* [Symfony Panther](https://github.com/symfony/panther) - Browser automation and testing

## HTML/XML Parsing

* [HTML5 PHP](https://github.com/Masterminds/html5-php) - HTML5 parser and serializer
* [QueryPath](https://github.com/technosophos/querypath) - jQuery-like XML/HTML library
* [DiDOM](https://github.com/Imangazaliev/DiDOM) - Fast HTML parser
* [PHPScraper](https://github.com/spekulatius/phpscraper) - Opinionated web interface
* [DomCrawler](https://github.com/symfony/dom-crawler) - DOM navigation component
* [PHP Simple HTML DOM Parser](https://sourceforge.net/projects/simplehtmldom/) - HTML DOM parser

## Text Processing

### General
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - ANSI to HTML5 converter
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - UTF-8 string library
* [Stringy](https://github.com/danielstjules/Stringy) - String manipulation with multibyte support
* [Flux](https://github.com/selvinortiz/flux) - Regex building library

### Transliteration
* [Urlify](https://github.com/jbroadway/urlify) - PHP port of Django's URLify.js
* [Slugify](https://github.com/cocur/slugify) - String to slug converter

### User-agent
* [CrawlerDetect](https://github.com/JayBizzle/Crawler-Detect) - Bot/crawler detection
* [Device Detector](https://github.com/piwik/device-detector) - User agent parsing
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - Mobile device detection
* [UA Parser](https://github.com/ua-parser/uap-php) - User agent string parser

### Units of Measure
* [ByteUnits](https://github.com/gabrielelana/byte-units) - Byte units parsing
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - Unit conversion
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - Phone number handling

## Specific Formats Processing

### Data Formats
* [CSV](https://github.com/thephpleague/csv) - CSV manipulation
* [JsonMapper](https://github.com/netresearch/jsonmapper) - JSON to PHP class mapping
* [vobject](https://github.com/fruux/sabre-vobject) - vCard/iCalendar parsing
* [GeoJSON](https://github.com/jmikola/geojson) - GeoJSON implementation

### Office Documents
* [PHPWord](https://github.com/PHPOffice/PHPWord) - Microsoft Word documents
* [PHPExcel](https://github.com/PHPOffice/PHPExcel) - Microsoft Excel documents
* [PHPPowerPoint](https://github.com/PHPOffice/PHPPowerPoint) - PowerPoint documents
* [ExcelAnt](https://github.com/Wisembly/ExcelAnt) - Excel manipulation

### Markdown
* [PHP Markdown](https://github.com/michelf/php-markdown) - Markdown parser
* [CommonMark PHP](https://github.com/thephpleague/commonmark) - CommonMark spec parser
* [Parsedown](https://github.com/erusev/parsedown) - Fast Markdown parser

## Natural Language Processing

* [PHP NlpTools](https://github.com/angeloskath/php-nlp-tools) - NLP tools collection
* [nlpTools](https://github.com/atrilla/nlptools) - NLP toolkit
* [PHP Stemmer](https://github.com/wamania/php-stemmer) - Word stemming
* [TextAnalysis](https://github.com/yooper/php-text-analysis) - Text analysis

## Browser Automation

* [php-webdriver](https://github.com/facebook/php-webdriver) - WebDriver client
* [PHP PhantomJS](https://github.com/jonnnnyw/php-phantomjs) - PhantomJS integration
* [Mink](https://github.com/minkphp/Mink) - Browser emulator API
* [Laravel Dusk](https://github.com/laravel/dusk) - Browser testing and automation

## Multiprocessing

* [Spork](https://github.com/kriswallsmith/spork) - Process forking
* [Parallel](https://www.php.net/manual/en/book.parallel.php) - Parallel processing
* [pthreads](https://www.php.net/manual/en/book.pthreads.php) - Multi-threading
* [Spatie Async](https://github.com/spatie/async) - Asynchronous and parallel PHP

## Asynchronous

* [React](https://github.com/reactphp/react) - Event-driven I/O
* [Rx.PHP](https://github.com/asm89/Rx.PHP) - Reactive extensions
* [Evenement](https://github.com/igorw/evenement) - Event dispatcher
* [Broadway](https://github.com/qandidate-labs/broadway) - Event sourcing and CQRS

## Queue

* [Pheanstalk](https://github.com/pda/pheanstalk) - Beanstalkd client
* [PHP AMQP](https://github.com/videlalvaro/php-amqplib) - AMQP library
* [Bernard](https://github.com/bernardphp/bernard) - Multi-backend queue
* [Thumper](https://github.com/videlalvaro/Thumper) - RabbitMQ patterns

## Email

* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - Email parsing
* [Email Validator](https://github.com/nojacko/email-validator) - Address validation
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Email creation/transfer
* [SwiftMailer](https://github.com/swiftmailer/swiftmailer) - Email library

## URL Manipulation

* [Purl](https://github.com/jwage/purl) - URL manipulation
* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - Domain parsing
* [Uri](https://github.com/thephpleague/uri) - URL manipulation (PSR-7)
* [Url](https://github.com/crwlrsoft/url) - URL Swiss Army knife

## Web Content Extracting

* [Essence](https://github.com/felixgirault/essence) - Web media extraction
* [Embera](https://github.com/mpratt/Embera) - Oembed consumer
* [Embed](https://github.com/oscarotero/Embed) - Webpage information
* [Youtube-Downloader](https://github.com/jeckman/YouTube-Downloader) - YouTube video tools

## WebSocket

* [Ratchet](https://github.com/cboden/Ratchet) - WebSocket library
* [Hoa WebSocket](https://github.com/hoaproject/Websocket) - WebSocket library
* [Elephant.io](https://github.com/Wisembly/Elephant.io) - WebSocket library

## DNS Resolving

* [Net_DNS2](https://github.com/mikepultz/netdns2) - DNS resolver
* [PHP DNS](https://www.php.net/manual/en/function.dns-get-record.php) - DNS functions

## Computer Vision

* [OpenCV-for-PHP](https://github.com/mgdm/OpenCV-for-PHP) - OpenCV binding

## Geocoding

* [GeoCoder](http://geocoder-php.org/) - Geocoding library
* [GeoTools](https://github.com/php-loep/Geotools) - Geo-related tools
