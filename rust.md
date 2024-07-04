# Rust Web Scraping

This list contains Rust libraries related to web scraping and data processing.

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
* [Other Rust Lists](#other-rust-lists)

## Network

* General
  * [reqwest](https://github.com/seanmonstar/reqwest) - An ergonomic HTTP client
  * [ureq](https://github.com/algesten/ureq) - Simple, safe HTTP client
  * [hyper](https://github.com/hyperium/hyper) - Fast HTTP implementation
  * [curl](https://github.com/alexcrichton/curl-rust) - Rust bindings to libcurl
  * [isahc](https://github.com/sagebind/isahc) - The practical HTTP client
  * [surf](https://github.com/http-rs/surf) - Cross-platform async HTTP client

* Asynchronous
  * [tokio](https://github.com/tokio-rs/tokio) - Async runtime and utilities
  * [async-h1](https://github.com/http-rs/async-h1) - Async HTTP/1.1 parser
  * [h2](https://github.com/hyperium/h2) - HTTP/2.0 client and server

## Web-scraping Frameworks

* Full Featured Crawlers
  * [spider](https://github.com/spider-rs/spider) - Fast web crawler with async support
  * [crawler](https://github.com/saintfish/crawler-rust) - Multi-threaded web crawler
  * [scraper-rs](https://github.com/causal-agent/scraper) - HTML parsing and querying

* Other
  * [url_hunter](https://github.com/jongold/url_hunter) - Fast URL extractor
  * [oxipng](https://github.com/shssoichiro/oxipng) - Multithreaded PNG optimizer

## HTML/XML Parsing

* [scraper](https://github.com/causal-agent/scraper) - HTML parsing and querying
* [select](https://github.com/utkarshkukreti/select.rs) - HTML5 parsing and querying
* [kuchiki](https://github.com/kuchiki-rs/kuchiki) - HTML/XML tree manipulation
* [quick-xml](https://github.com/tafia/quick-xml) - High-performance XML reader/writer
* [html5ever](https://github.com/servo/html5ever) - High-performance browser-grade parser
* [roxmltree](https://github.com/RazrFalcon/roxmltree) - Fast, safe XML parsing

## Text Processing

* General
  * [regex](https://github.com/rust-lang/regex) - Regular expressions implementation
  * [fancy-regex](https://github.com/fancy-regex/fancy-regex) - Advanced regex features
  * [onig](https://github.com/rust-onig/rust-onig) - Rust binding for Oniguruma

* String Manipulation
  * [string-utils](https://github.com/magiclen/string-utils) - String manipulation
  * [unicode-segmentation](https://github.com/unicode-rs/unicode-segmentation) - Unicode text segmentation
  * [rust-stemmers](https://github.com/CurrySoftware/rust-stemmers) - Word stemming

* Character Encoding
  * [encoding_rs](https://github.com/hsivonen/encoding_rs) - Character encoding conversion
  * [chardetng](https://github.com/hsivonen/chardetng) - Character encoding detection
  * [encoding](https://github.com/lifthrasiir/rust-encoding) - Character encoding support

## Specific Formats Processing

* General
  * [serde](https://github.com/serde-rs/serde) - Serialization framework
  * [serde_json](https://github.com/serde-rs/json) - JSON serialization
  * [toml](https://github.com/alexcrichton/toml-rs) - TOML format parser
  * [yaml-rust](https://github.com/chyh1990/yaml-rust) - YAML format parser

* Office
  * [calamine](https://github.com/tafia/calamine) - Excel file reader
  * [docx-rs](https://github.com/bokuweb/docx-rs) - Docx file manipulation
  * [lopdf](https://github.com/J-F-Liu/lopdf) - PDF document manipulation
  * [rust_xlsxwriter](https://github.com/jmcnamara/rust_xlsxwriter) - Excel file writer

## Natural Language Processing

* [rust-bert](https://github.com/guillaume-be/rust-bert) - Ready-to-use NLP pipelines
* [whatlang](https://github.com/greyblake/whatlang-rs) - Natural language detection
* [lingua](https://github.com/pemistahl/lingua-rs) - Language detection library
* [rust-stemmer](https://github.com/CurrySoftware/rust-stemming) - Stemming algorithms
* [tokenizers](https://github.com/huggingface/tokenizers) - Fast tokenizers

## Browser Automation and Emulation

* [fantoccini](https://github.com/jonhoo/fantoccini) - High-level WebDriver client
* [headless_chrome](https://github.com/atroche/rust-headless-chrome) - Chrome automation
* [thirtyfour](https://github.com/stevepryde/thirtyfour) - Selenium WebDriver client
* [chromiumoxide](https://github.com/mattsse/chromiumoxide) - Chrome DevTools Protocol

## Multiprocessing

* [rayon](https://github.com/rayon-rs/rayon) - Data parallelism library
* [crossbeam](https://github.com/crossbeam-rs/crossbeam) - Concurrent programming
* [threadpool](https://github.com/rust-threadpool/rust-threadpool) - Thread pool implementation
* [num_cpus](https://github.com/seanmonstar/num_cpus) - CPU count detection

## Queue

* [lapin](https://github.com/CleverCloud/lapin) - RabbitMQ client
* [redis-rs](https://github.com/redis-rs/redis-rs) - Redis client
* [rsmq](https://github.com/smrchy/rsmq-rs) - Redis simple message queue
* [deadqueue](https://github.com/bikeshedder/deadqueue) - Dead simple queue

## Email

* [lettre](https://github.com/lettre/lettre) - Email client
* [mail-parser](https://github.com/staktrace/mail-parser) - Email parsing
* [email](https://github.com/niconicoj/email) - Email parsing and generation
* [rust-imap](https://github.com/jonhoo/rust-imap) - IMAP client

## URL and Network Address Manipulation

* URL
  * [url](https://github.com/servo/rust-url) - URL parser
  * [urlencoding](https://github.com/kaj/urlencoding) - URL encoding/decoding
  * [percent-encoding](https://github.com/servo/rust-url) - Percent encoding

* Network Address
  * [ipnetwork](https://github.com/achanda/ipnetwork) - IP network calculations
  * [trust-dns](https://github.com/bluejekyll/trust-dns) - DNS client and server

## Web Content Extracting

* Text and Meta Data
  * [readability](https://github.com/kumabook/readability) - Text extraction
  * [html2text](https://github.com/veddan/rust-htmlescape) - HTML to text conversion
  * [feed-rs](https://github.com/feed-rs/feed-rs) - Feed (RSS/Atom) parser

## Asynchronous

* [tokio](https://github.com/tokio-rs/tokio) - Async runtime
* [async-std](https://github.com/async-rs/async-std) - Async runtime and utilities
* [futures](https://github.com/rust-lang/futures-rs) - Async abstractions
* [smol](https://github.com/smol-rs/smol) - Small and fast async runtime

## WebSocket

* [tungstenite](https://github.com/snapview/tungstenite-rs) - WebSocket stream
* [tokio-tungstenite](https://github.com/snapview/tokio-tungstenite) - Async WebSocket
* [websocket](https://github.com/websockets-rs/rust-websocket) - WebSocket protocol

## DNS Resolving

* [trust-dns](https://github.com/bluejekyll/trust-dns) - DNS client and server
* [hickory-dns](https://github.com/hickory-dns/hickory-dns) - Async DNS client/server
* [domain](https://github.com/NLnetLabs/domain) - DNS library

## Computer Vision

* [image](https://github.com/image-rs/image) - Image processing library
* [opencv](https://github.com/twistedfall/opencv-rust) - OpenCV bindings
* [rustface](https://github.com/atomashpolskiy/rustface) - Face detection library

## Proxy Server

* [sozu](https://github.com/sozu-proxy/sozu) - HTTP reverse proxy
* [toxy-proxy](https://github.com/cetra3/toxy-proxy) - TCP proxy server
* [shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) - Proxy server

## Other Rust Lists

* [awesome-rust](https://github.com/rust-unofficial/awesome-rust) - Curated list of Rust tools
* [rust-web-framework-comparison](https://github.com/flosse/rust-web-framework-comparison) - Web framework comparison
