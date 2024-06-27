# Java Web Scraping

This list contains Java libraries related to web scraping and data processing.

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

### HTTP Clients
* [Apache HttpClient](https://hc.apache.org/) - Foundational HTTP client library
* [OkHttp](https://square.github.io/okhttp/) - Modern HTTP client
* [Java 11 HttpClient](https://docs.oracle.com/en/java/javase/11/docs/api/java.net.http/java/net/http/HttpClient.html) - Built-in HTTP client
* [Unirest](https://kong.github.io/unirest-java/) - Simplified HTTP client

### Asynchronous Clients
* [Apache Async HttpClient](https://hc.apache.org/) - Async HTTP client
* [AsyncHttpClient](https://github.com/AsyncHttpClient/async-http-client) - Async HTTP client
* [Retrofit](https://square.github.io/retrofit/) - Type-safe HTTP client
* [Netty](https://netty.io/) - Asynchronous network application framework

## Web Scraping

### Full Featured Crawlers
* [ACHE Crawler](https://github.com/ViDA-NYU/ache) - Focused web crawler
* [Apache Nutch](http://nutch.apache.org/) - Production-grade crawler
* [Heritrix](https://github.com/internetarchive/heritrix3) - Internet Archive's web crawler
* [StormCrawler](http://stormcrawler.net/) - SDK for building low-latency crawlers

### Frameworks and Tools
* [Crawler4j](https://github.com/CrawlScript/crawler4j) - Open source web crawler
* [JSoup](https://jsoup.org/) - HTML parsing with CSS selectors
* [Jaunt](http://jaunt-api.com/) - Web scraping and JSON parsing
* [WebMagic](https://github.com/code4craft/webmagic) - Scalable crawler framework

## HTML/XML

### Parsing
* [JSoup](https://jsoup.org/) - HTML parsing and manipulation
* [Apache Tika](https://tika.apache.org/) - Content detection and extraction
* [dom4j](https://dom4j.github.io/) - Flexible XML framework
* [JAXP](https://docs.oracle.com/javase/tutorial/jaxp/) - Built-in XML processing
* [htmlunit](http://htmlunit.sourceforge.net/) - GUI-Less browser for Java programs

### Generation and Processing
* [j2html](https://j2html.com/) - HTML generation in Java
* [CommonMark-Java](https://github.com/commonmark/commonmark-java) - Markdown processing
* [vtd-xml](https://sourceforge.net/projects/vtd-xml/) - XML processing
* [XStream](https://x-stream.github.io/) - XML serialization

## Text Processing

### Core Libraries
* [Apache Commons Lang](https://commons.apache.org/proper/commons-lang/) - String utilities
* [Apache Commons Text](https://commons.apache.org/proper/commons-text/) - Text algorithms
* [Apache Tika](https://tika.apache.org/) - Content detection and text extraction
* [ICU4J](https://icu.unicode.org/) - Unicode and globalization support

### Date and Time
* [Joda-Time](https://www.joda.org/joda-time/) - Date and time library
* [java.time](https://docs.oracle.com/javase/8/docs/api/java/time/package-summary.html) - Built-in date/time API

## Specific Formats Processing

### Data Formats
* [Jackson](https://github.com/FasterXML/jackson) - JSON processing
* [Gson](https://github.com/google/gson) - JSON library
* [Apache Avro](https://avro.apache.org/) - Data serialization
* [Protocol Buffers](https://github.com/protocolbuffers/protobuf/tree/master/java) - Data format

### Document Processing
* [Apache PDFBox](https://pdfbox.apache.org/) - PDF manipulation
* [Apache POI](https://poi.apache.org/) - Microsoft documents processing
* [iText](https://itextpdf.com/en) - PDF generation and manipulation

## Natural Language Processing

* [Apache OpenNLP](https://opennlp.apache.org/) - Machine learning NLP toolkit
* [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/) - NLP services
* [LingPipe](http://alias-i.com/lingpipe/) - Text processing toolkit
* [Apache Lucene](https://lucene.apache.org/) - Text search engine library

## Browser Automation

* [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver/) - Browser automation
* [Playwright](https://github.com/microsoft/playwright-java) - Modern browser automation
* [htmlunit](http://htmlunit.sourceforge.net/) - GUI-Less browser
* [jBrowserDriver](https://github.com/MachinePublishers/jBrowserDriver) - Selenium-compatible browser

## Concurrent Processing

* [ExecutorService](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ExecutorService.html) - Thread pool execution
* [ForkJoinPool](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ForkJoinPool.html) - Work-stealing pool
* [RxJava](https://github.com/ReactiveX/RxJava) - Reactive extensions
* [Project Reactor](https://projectreactor.io/) - Reactive library

## Queue Systems

* [Apache Kafka](https://kafka.apache.org/) - Distributed streaming platform
* [RabbitMQ Java](https://www.rabbitmq.com/java-client.html) - Message broker client
* [ActiveMQ](https://activemq.apache.org/) - Message broker
* [Apache Camel](https://camel.apache.org/) - Integration framework

## Email

* [JavaMail](https://javaee.github.io/javamail/) - Email handling
* [Spring Mail](https://docs.spring.io/spring-framework/docs/current/reference/html/integration.html#mail) - Email integration
* [Simple Java Mail](http://www.simplejavamail.org/) - Email library
* [Apache Commons Email](https://commons.apache.org/proper/commons-email/) - Email utilities

## URL and Network Address

* [java.net.URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html) - URL handling
* [Apache Commons Validator](https://commons.apache.org/proper/commons-validator/) - URL validation
* [Guava URLs](https://github.com/google/guava/wiki/StringsExplained#urls) - URL utilities

## Content Extraction

* [Boilerpipe](https://github.com/kohlschutter/boilerpipe) - Boilerplate removal
* [Apache Tika](https://tika.apache.org/) - Content extraction
* [Readability4J](https://github.com/dankito/Readability4J) - Web page extraction

## WebSocket

* [Java WebSocket](https://github.com/TooTallNate/Java-WebSocket) - WebSocket implementation
* [Spring WebSocket](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#websocket) - WebSocket support
* [Tyrus](https://tyrus-project.github.io/) - Reference implementation

## DNS Resolving

* [dnsjava](https://github.com/dnsjava/dnsjava) - DNS implementation
* [spotify-dns-java](https://github.com/spotify/dns-java) - DNS resolver

## Proxy Server

* [JPROXY](https://github.com/Atsushi2049/JPROXY) - HTTP/HTTPS proxy
* [Proxy Vole](https://github.com/MarkusBernhardt/proxy-vole) - Proxy detection
