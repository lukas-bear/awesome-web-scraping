# Ruby Web Scraping

This list contains Ruby libraries related to web scraping and data processing.

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
* [Other Ruby Lists](#other-ruby-lists)

## Network

* General
  * [httparty](https://github.com/jnunemaker/httparty) - Makes HTTP fun again
  * [http](https://github.com/tarcieri/http) - Simple Ruby DSL for HTTP requests
  * [excon](https://github.com/excon/excon) - Fast HTTP(S) 1.1 for Ruby
  * [Faraday](https://github.com/lostisland/faraday) - HTTP client with multiple adapter support
  * [RestClient](https://github.com/rest-client/rest-client) - Simple HTTP and REST client
  * [Typhoeus](https://github.com/typhoeus/typhoeus) - Parallel HTTP requests with libcurl
  * [Mechanize](https://github.com/sparklemotion/mechanize) - Automated web interaction
  * [Savon](https://github.com/savonrb/savon) - SOAP client for Ruby
  * [Http-2](https://github.com/igrigorik/http-2) - Pure Ruby HTTP/2 protocol implementation

* Asynchronous
  * [EM-HTTP-Request](https://github.com/igrigorik/em-http-request) - EventMachine based HTTP client
  * [Celluloid::IO](https://github.com/celluloid/celluloid-io) - Evented IO for Celluloid actors

## Web-scraping Frameworks

* Full Featured Crawlers
  * [upton](https://github.com/propublica/upton) - Batteries-included scraping framework
  * [Anemone](https://github.com/chriskite/anemone) - Web spider framework
  * [Spidr](https://github.com/postmodern/spidr) - Versatile web spidering library
  * [kimuraframework](https://github.com/vifreefly/kimuraframework) - Modern scraping with browser support

* Other
  * [Wombat](https://github.com/felipecsl/wombat) - Web scraper with elegant DSL
  * [arachnid2](https://github.com/samnissen/arachnid2) - Fast framework-less crawler

## HTML/XML Parsing

* [nokogiri](https://github.com/sparklemotion/nokogiri) - HTML, XML, SAX parser
* [loofah](https://github.com/flavorjones/loofah) - HTML/XML manipulation and sanitization
* [HappyMapper](https://github.com/dam5s/happymapper) - XML to Ruby data structures
* [Oga](https://github.com/YorickPeterse/oga) - XML/HTML parser without dependencies
* [Ox](https://github.com/ohler55/ox) - Fast XML parser and Object marshaller
* [ROXML](https://github.com/Empact/roxml) - Ruby-XML bidirectional mapping
* [nokolexbor](https://github.com/serpapi/nokolexbor) - Fast HTML5 parser based on Lexbor

## Text Processing

* General
  * [Kiba](https://github.com/thbar/kiba) - Data-processing ETL framework
  * [diffy](https://github.com/samg/diffy) - String and file diff generator
  * [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) - Common information extractor

* Date & Time
  * [Chronic](https://github.com/mojombo/chronic) - Natural language date/time parser
  * [Chronic Duration](https://github.com/hpoydar/chronic_duration) - Natural language time spans
  * [Kronic](https://github.com/xaviershay/kronic) - Human readable date parser

* Text Analysis
  * [N-Gram](https://github.com/reddavis/N-Gram) - N-Gram generator
  * [FuzzyMatch](https://github.com/seamusabshere/fuzzy_match) - String similarity matching
  * [TF-IDF](https://github.com/reddavis/TF-IDF) - Term frequency analysis

## Specific Formats Processing

* General
  * [json](https://github.com/flori/json) - Pure Ruby and C JSON implementation
  * [OJ](https://github.com/ohler55/oj) - Optimized JSON processor
  * [BSON](https://github.com/mongodb/bson-ruby) - BSON specification implementation
  * [MessagePack](https://github.com/msgpack/msgpack-ruby) - Efficient binary serialization

* Office
  * [spreadsheet](https://github.com/zdavatz/spreadsheet) - Excel file manipulation
  * [roo](https://github.com/Empact/roo) - Spreadsheet interface with Google support
  * [rubyXL](https://github.com/weshatheleopard/rubyXL) - Excel XLSX manipulation
  * [Yomu](https://github.com/Erol) - Document text and metadata extraction

## Natural Language Processing

* [Treat](https://github.com/louismullie/treat) - NLP toolkit
* [Text](https://github.com/threedaymonk/text) - Text algorithms collection
* [Stanford Core NLP](https://github.com/louismullie/stanford-core-nlp) - Ruby bindings
* [Open NLP](https://github.com/louismullie/open-nlp) - OpenNLP bindings
* [whatlanguage](https://github.com/peterc/whatlanguage) - Language detection
* [ruby-stemmer](https://github.com/aurelian/ruby-stemmer) - Word stemming algorithms

## Browser Automation and Emulation

* [selenium](https://github.com/seleniumhq/selenium) - Browser automation framework
* [Watir](https://github.com/watir/watir) - WebDriver-based automation
* [capybara-webkit](https://github.com/thoughtbot/capybara-webkit) - Headless WebKit testing
* [poltergeist](https://github.com/teampoltergeist/poltergeist) - PhantomJS driver

## Multiprocessing

* [Celluloid](https://github.com/celluloid/celluloid) - Actor-based concurrency
* [Parallel](https://github.com/grosser/parallel) - Parallel processing made simple
* [thread](https://github.com/meh/ruby-thread) - Thread library extensions
* [childprocess](https://github.com/jarib/childprocess) - Cross-platform process management

## Queue

* [Sidekiq](http://sidekiq.org) - Background job processing
* [Resque](https://github.com/resque/resque) - Redis-backed job queue
* [Delayed::Job](https://github.com/collectiveidea/delayed_job) - Database-backed queue
* [Sneakers](https://github.com/jondot/sneakers) - RabbitMQ job processing

## Email

* [mail](https://github.com/mikel/mail) - Ruby mail library
* [Pony](https://github.com/benprew/pony) - Express email sending
* [Mailman](https://github.com/mailman/mailman) - Incoming email processing
* [Email Reply Parser](https://github.com/github/email-reply-parser) - Email parsing

## URL and Network Address Manipulation

* URL
  * [addressable](https://github.com/sporkmonger/addressable) - RFC-compliant URL implementation
  * [URI](https://ruby-doc.org/stdlib/libdoc/uri/rdoc/URI.html) - Standard library URI tools

* Network Address
  * [IPAddr](https://ruby-doc.org/stdlib/libdoc/ipaddr/rdoc/IPAddr.html) - IP address manipulation

## Web Content Extracting

* Text and Meta Data from HTML pages
  * [Metainspector](https://github.com/jaimeiniesta/metainspector) - Web page meta extraction
  * [Ruby Readability](https://github.com/cantino/ruby-readability) - Content extraction
  * [LinkThumbnailer](https://github.com/gottfrois/link_thumbnailer) - Link preview generation

## Asynchronous

* [EventMachine](https://github.com/eventmachine/eventmachine) - Event-driven I/O
* [Celluloid::IO](https://github.com/celluloid/celluloid-io) - Evented IO for Celluloid

## WebSocket

* [em-websocket](https://github.com/igrigorik/em-websocket) - EventMachine WebSocket server
* [Faye](http://faye.jcoglan.com/ruby.html) - Pub/sub messaging server
* [Slanger](https://github.com/stevegraham/slanger) - Pusher protocol server

## DNS Resolving

* [em-resolve-replace](https://github.com/mperham/em-resolv-replace) - Async DNS resolution
* [Celluloid::DNS](https://github.com/celluloid/celluloid-dns) - DNS client/server

## Computer Vision

* [ruby-opencv](https://github.com/ruby-opencv/ruby-opencv) - OpenCV wrapper

## Proxy Server

* [Tinyproxy](https://github.com/shivammathur/tinyproxy) - Lightweight HTTP/HTTPS proxy
* [em-proxy](https://github.com/igrigorik/em-proxy) - EventMachine proxy server

## Other Ruby Lists

* [awesome-ruby](https://github.com/markets/awesome-ruby) by markets
* [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby) by Sdogruyol
* [ruby-nlp](https://github.com/diasks2/ruby-nlp) - NLP libraries collection
