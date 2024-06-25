# Go Web Scraping

This list contains Go libraries related to web scraping and data processing.

## Contents

* [Network](#network)
* [Web Scraping](#web-scraping)
* [HTML/XML](#htmlxml)
* [Text Processing](#text-processing)
* [Specific Formats Processing](#specific-formats-processing)
* [Natural Language Processing](#natural-language-processing)
* [Browser Automation](#browser-automation)
* [Concurrent Processing](#concurrent-processing)
* [Queue Systems](#queue-systems)
* [Email](#email)
* [URL and Network Address](#url-and-network-address)
* [Content Extraction](#content-extraction)
* [WebSocket](#websocket)
* [DNS Resolving](#dns-resolving)
* [Proxy Server](#proxy-server)

## Network

### Standard Libraries
* [net](https://golang.org/pkg/net/) - Built-in package for network operations
* [net/http](https://golang.org/pkg/net/http/) - HTTP client and server implementations

### HTTP Clients
* [fasthttp](https://github.com/valyala/fasthttp) - Fast HTTP package for Go
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client
* [gorequest](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with Promise-like interface

## Web Scraping

### Full Featured Crawlers
* [Pholcus](https://github.com/henrylee2cn/pholcus) - Distributed, high concurrency crawler
* [go_spider](https://github.com/hu17889/go_spider) - Modular and concurrent crawler framework
* [ants-go](https://github.com/wcong/ants-go) - Distributed crawler engine

### Full Featured Scrapers
* [colly](https://github.com/gocolly/colly) - Elegant scraping framework
* [geziyor](https://github.com/geziyor/geziyor) - Fast scraping framework with JS rendering
* [dataflow kit](https://github.com/slotix/dataflowkit) - Extract structured data from websites
* [flyscrape](https://github.com/philippta/flyscrape) - Standalone and scriptable scraper
* [goscrapy](https://github.com/tech-engine/goscrapy) - Scrapy-inspired framework
* [ferret](https://github.com/MontFerret/ferret) - Declarative web scraping tool

## HTML/XML

### Parsing
* [encoding/xml](https://golang.org/pkg/encoding/xml/) - Built-in XML parser
* [GoQuery](https://github.com/PuerkitoBio/goquery) - jQuery-like syntax for HTML
* [xpath](https://github.com/antchfx/xpath) - XPath package
* [cascadia](https://github.com/andybalholm/cascadia) - CSS selector implementation
* [mxj](https://github.com/clbanning/mxj) - XML to JSON/Map converter

### Sanitization
* [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML sanitizer

## Text Processing

### String Manipulation
* [regexp](https://golang.org/pkg/regexp/) - Regular expression package
* [go-humanize](https://github.com/dustin/go-humanize) - Format numbers and dates
* [xstrings](https://github.com/huandu/xstrings) - String functions collection

### Format Processing
* [slug](https://github.com/gosimple/slug) - URL-friendly slugify
* [go-slugify](https://github.com/mozillazg/go-slugify) - Multi-language slug support
* [goregen](https://github.com/zach-klippenstein/goregen) - Random string generation

## Specific Formats Processing

### Data Formats
* [encoding/json](https://golang.org/pkg/encoding/json/) - JSON encoding/decoding
* [toml](https://github.com/BurntSushi/toml) - TOML format parser
* [gofeed](https://github.com/mmcdole/gofeed) - RSS and Atom feed parser
* [blackfriday](https://github.com/russross/blackfriday) - Markdown processor

### Document Processing
* [go-vcard](https://github.com/emersion/go-vcard) - vCard format parser
* [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA protocol parser
* [gographviz](https://github.com/awalterschulze/gographviz) - Graphviz DOT parser

## Natural Language Processing

### Core NLP
* [prose](https://github.com/jdkato/prose) - Text processing library
* [go-nlp](https://github.com/nuance/go-nlp) - NLP utilities
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Language detection

### Language-Specific
* [gojieba](https://github.com/yanyiwu/gojieba) - Chinese word segmentation
* [go-stem](https://github.com/agonopol/go-stem) - Porter stemming algorithm
* [MMSEGO](https://github.com/awsong/MMSEGO) - Chinese word splitting
* [when](https://github.com/olebedev/when) - Natural language date/time parser

## Browser Automation

* [chromedp](https://github.com/chromedp/chromedp) - Chrome DevTools Protocol driver
* [rod](https://github.com/go-rod/rod) - High-level Chrome automation
* [playwright-go](https://github.com/mxschmitt/playwright-go) - Playwright driver

## Email

* [email](https://github.com/jordan-wright/email) - Robust email library
* [go-imap](https://github.com/emersion/go-imap) - IMAP client/server library
* [Gomail](https://github.com/go-gomail/gomail/) - SMTP email sender
* [hermes](https://github.com/matcornic/hermes) - Clean HTML email generator
* [MailHog](https://github.com/mailhog/MailHog) - Email testing tool

## Queue Systems

* [NSQ](https://github.com/nsqio/nsq) - Realtime distributed messaging
* [NATS](https://github.com/nats-io/go-nats) - Cloud native messaging system
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue

## WebSocket

* [gorilla/websocket](https://github.com/gorilla/websocket) - WebSocket implementation
* [nhooyr/websocket](https://github.com/nhooyr/websocket) - WebSocket library
* [melody](https://github.com/olahol/melody) - WebSocket framework

## DNS Resolving

* [net](https://golang.org/pkg/net/) - Built-in DNS functions
* [miekg/dns](https://github.com/miekg/dns) - DNS library

## Proxy Server

* [gin](https://github.com/codegangsta/gin) - Live reload utility
* [Caddy](https://github.com/caddyserver/caddy) - Web server with proxy capabilities
* [goproxy](https://github.com/elazarl/goproxy) - HTTP/HTTPS proxy library
