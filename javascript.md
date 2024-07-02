# JavaScript Web Scraping

This list contains JavaScript libraries related to web scraping and data processing.

## Contents

* [Network](#network)
* [Web Scraping](#web-scraping)
* [HTML/XML](#htmlxml)
* [Text Processing](#text-processing)
* [Specific Formats Processing](#specific-formats-processing)
* [Natural Language Processing](#natural-language-processing)
* [Browser Automation](#browser-automation)
* [Multiprocessing](#multiprocessing)
* [Queue and Job Processing](#queue-and-job-processing)
* [Email Processing](#email-processing)
* [URL and Network Address](#url-and-network-address)
* [Content Extraction](#content-extraction)
* [WebSocket](#websocket)
* [DNS Resolving](#dns-resolving)
* [Computer Vision](#computer-vision)
* [Proxy Management](#proxy-management)
* [Data Structure](#data-structure)

## Network

* [axios](https://github.com/axios/axios) - Promise based HTTP client
* [node-fetch](https://github.com/node-fetch/node-fetch) - Light-weight module that brings Fetch API to Node.js
* [got](https://github.com/sindresorhus/got) - Human-friendly HTTP request library
* [superagent](https://github.com/visionmedia/superagent) - Ajax with less suck (HTTP client)
* [request](https://github.com/request/request) - Simplified HTTP request client
* [undici](https://github.com/nodejs/undici) - HTTP/1.1 client, written from scratch
* [socks5-http-client](https://github.com/mattcg/socks5-http-client) - SOCKS v5 HTTP client implementation
* [urllib](https://github.com/node-modules/urllib) - Request HTTP(s) URLs in a complex world
* [needle](https://github.com/tomas/needle) - Streamable HTTP client with proxy, iconv, cookie, deflate & multipart support

## Web Scraping

### Frameworks and Tools

* [puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API
* [playwright](https://github.com/microsoft/playwright) - Browser automation for Chromium, Firefox and WebKit
* [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible implementation of jQuery for servers
* [crawlee](https://github.com/apify/crawlee) - Web scraping and browser automation library
* [node-crawler](https://github.com/sylvinus/node-crawler) - Web Crawler/Spider with jQuery
* [webparsy](https://github.com/joseconstela/webparsy) - Scraping with Puppeteer and YAML
* [node-simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Flexible event driven crawler
* [Ayakashi](https://github.com/ayakashi-io/ayakashi) - Scraping framework with maintenance features

## HTML/XML

### Parsing
* [parse5](https://github.com/inikulin/parse5) - HTML5 specification-compliant parser
* [htmlparser2](https://github.com/fb55/htmlparser2) - Forgiving HTML/XML parser
* [sax-js](https://github.com/isaacs/sax-js) - SAX-style parser
* [cheerio](https://github.com/cheeriojs/cheerio) - jQuery implementation for servers

### Sanitizing
* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML with whitelist configuration
* [surgeon](https://github.com/gajus/surgeon) - Declarative DOM extraction evaluator
* [sanitize-html](https://github.com/apostrophecms/sanitize-html) - Clean up user-submitted HTML

## Text Processing

### General
* [string.js](https://github.com/jprichardson/string.js) - Extra string methods
* [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization

### Date and Time
* [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates
* [date](https://github.com/MatthewMueller/date) - Date() for humans

### HTML Entities
* [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder

### Specialized Processing
* [accounting.js](https://github.com/openexchangerates/accounting.js) - Number, money and currency formatting
* [money.js](https://github.com/openexchangerates/money.js) - Currency conversion library
* [UAParser.js](https://github.com/faisalman/ua-parser-js) - User-Agent string parser

## Specific Formats Processing

### Office Documents
* [js-xlsx](https://github.com/SheetJS/js-xlsx) - Excel file format parser and writer

### Data Formats
* [papaparse](https://github.com/mholt/PapaParse) - Powerful CSV parser
* [json5](https://github.com/json5/json5) - JSON for humans
* [js-yaml](https://github.com/nodeca/js-yaml) - YAML parser and dumper

### Markdown
* [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with plugins
* [turndown](https://github.com/mixmark-io/turndown) - HTML to Markdown converter

### Feed Parsing
* [node-feedparser](https://github.com/danmactough/node-feedparser) - RSS, Atom, and RDF feed parsing

## Natural Language Processing

* [natural](https://github.com/NaturalNode/natural) - General natural language facilities
* [compromise](https://github.com/spencermountain/compromise) - Natural language processing
* [franc](https://github.com/wooorm/franc) - Natural language detection
* [node-summary](https://github.com/jbrooksuk/node-summary) - Text summarization

## Browser Automation

* [puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API
* [playwright](https://github.com/microsoft/playwright) - Browser automation library
* [nightmare](https://github.com/segmentio/nightmare) - High-level browser automation
* [casperjs](https://github.com/casperjs/casperjs) - Navigation scripting & testing utility
* [zombie](https://github.com/assaf/zombie) - Headless browser testing

## Multiprocessing

* [nexpect](https://github.com/nodejitsu/nexpect) - Control child processes
* [respawn](https://github.com/mafintosh/respawn) - Spawn and restart crashed processes
* [node-webworker](https://github.com/pgriess/node-webworker) - WebWorkers implementation

## Queue and Job Processing

* [bull](https://github.com/OptimalBits/bull) - Redis-based queue for jobs and messages
* [kue](https://github.com/Automattic/kue) - Priority job queue backed by redis
* [bee-queue](https://github.com/bee-queue/bee-queue) - Simple, fast, robust job/task queue

## Email Processing

* [mailparser](https://github.com/nodemailer/mailparser) - MIME message parser
* [email-templates](https://github.com/forwardemail/email-templates) - Create, preview, and send custom email templates

## URL and Network Address

### URL Processing
* [url-parse](https://github.com/unshiftio/url-parse) - URL parser for Node.js and browser
* [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings
* [URI.js](https://github.com/medialize/URI.js) - URL mutation library

### Network Address Processing
* [node-ip](https://github.com/indutny/node-ip) - IP address tools
* [ip-address](https://github.com/beaugunderson/ip-address) - IPv6 and IPv4 address manipulation

## Content Extraction

* [readability](https://github.com/mozilla/readability) - Standalone version of Firefox Reader View
* [node-read](https://github.com/bndr/node-read) - Get readable content from pages
* [node-ytdl-core](https://github.com/fent/node-ytdl-core) - Youtube video downloader
* [metascraper](https://github.com/microlinkhq/metascraper) - Scrape metadata from websites

## WebSocket

* [ws](https://github.com/websockets/ws) - Simple and fast WebSocket client/server
* [socket.io](https://github.com/socketio/socket.io) - Realtime application framework
* [WebSocket-Node](https://github.com/theturtle32/WebSocket-Node) - WebSocket implementation

## DNS Resolving

* [multicast-dns](https://github.com/mafintosh/multicast-dns) - Multicast-dns implementation
* [node-dns](https://github.com/tjfontaine/node-dns) - DNS implementation in JavaScript

## Computer Vision

* [tracking.js](https://github.com/eduardolundgren/tracking.js) - Computer Vision on the web
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten

## Proxy Management

* [proxy-chain](https://github.com/apifytech/proxy-chain) - Proxy server implementation
* [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) - The one-liner proxy middleware
* [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy for testing

## Data Structure

* [immutable](https://github.com/facebook/immutable-js) - Immutable persistent data collections
* [lodash](https://github.com/lodash/lodash) - Utility library for arrays, numbers, objects, strings
