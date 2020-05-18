# Internet

The worldwide network of networks that link several billion devices. It consists of millions of private, public, academic, business, and government networks of local to global scope, linked by a broad array of electronic, wireless, and optical networking technologies. It provides a variety of information and communication facilities, consisting of interconnected networks using standardized communication protocols.

## How the Web works

So what happens when you visit a webpage?

Basically a connection between your computer (`Client`) and another remote computer (`Server`) is created. When you visit a site, you're looking the content of a remote computer. The `Server` stores or hosts webpages, sites or apps. When a client wants to access a webpage, it is downloaded from the server onto the client machine to be displayed in the user's web browser.

In addition to the client and the server, the other parts involved in the navigation:

* `Your internet connection`: Allows you to send and receive data on the web.
* `TCP/IP`: Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the web.
* `DNS`: Domain Name Servers are like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's real address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place.
* `HTTP`: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other.
* `Component files`: A website is made up of many different files. These files come in two main types:
  * `Code files`: Websites are built primarily from HTML, CSS, and JavaScript.
  * `Assets`: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.


## Navigation process:

1. You type a web address in your browser.
2. The browser asks the DNS server for real server address.
3. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client. The TCP/IP, manages the messaging in between the client and the server.
4. If the server approves the client's request, the server sends the client a "200 OK" message, then it starts sending the website's files to the browser as a series of small chunks called data packets.
5. The browser assembles the small chunks into a complete website and displays it to you.

## What's HTTP - DNS?

HTTP is an application-level protocol, which allows the fetching of resources, such as HTML documents. It is the foundation of any data exchange on the Web and it is a client-server protocol, which means requests are initiated by the recipient, usually the Web browser. A complete document is reconstructed from the different sub-documents fetched, for instance text, layout description, images, videos, scripts, and more.

<img src="https://mdn.mozillademos.org/files/13673/HTTP%20&%20layers.png" alt="HTTP as an application layer protocol, on top of TCP (transport layer) and IP (network layer) and below the presentation layer." />

### HTTP flow

When a client wants to communicate with a server, either the final server or an intermediate proxy, it performs the following steps:

1. Open a TCP connection: The TCP connection is used to send a request, or several, and receive an answer. The client may open a new connection, reuse an existing connection, or open several TCP connections to the servers.
2. Send an HTTP message: HTTP messages (before HTTP/2) are human-readable. With HTTP/2, these simple messages are encapsulated in frames, making them impossible to read directly, but the principle remains the same.

```text
GET / HTTP/1.1
Host: developer.mozilla.org
Accept-Language: fr
```
3. Read the response sent by the server, such as:

```text
HTTP/1.1 200 OK
Date: Sat, 09 Oct 2010 14:28:02 GMT
Server: Apache
Last-Modified: Tue, 01 Dec 2009 20:18:22 GMT
ETag: "51142bc1-7449-479b075b2891b"
Accept-Ranges: bytes
Content-Length: 29769
Content-Type: text/html

<!DOCTYPE html... (here comes the 29769 bytes of the requested web page)
```
4. Close or reuse the connection for further requests.

More about HTTP on:

https://dev.opera.com/articles/http-lets-get-it-on/

### DNS

Real web addresses are special numbers that look like this: 63.245.215.20. This is called an IP address, and it represents a unique location on the web. These are special servers that match up a web address you type into your browser (like "mozilla.org") to the website's real (IP) address.

At its most basic, DNS is a directory of names that match with numbers. The numbers, in this case are IP addresses, which computers use to communicate with each other.

### How DNS servers work

The DNS directory that matches name to numbers isn’t located all in one place in some dark corner of the internet. Like the internet itself, the directory is distributed around the world, stored on domain name servers that all communicate with each other on a very regular basis to provide updates and redundancies.

## Sources

* [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Glossary/Internet)
* [How the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
* [What is DNS and how does it work?](https://www.networkworld.com/article/3268449/what-is-dns-and-how-does-it-work.html)
* [An overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
