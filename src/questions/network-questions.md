---
title: Network Questions
layout: layouts/page.njk
permalink: /questions/network-questions/index.html
---

1: * Traditionally, why has it been better to serve site assets from multiple domains?
-->
Parallelization
Reduced header overhead

https://travishorn.com/why-it-is-better-to-serve-site-assets-from-multiple-domains-972a2bf69d71



2: * Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
-->
https://medium.com/@maneesha.wijesinghe1/what-happens-when-you-type-an-url-in-the-browser-and-press-enter-bb0aa2449c1a



3: * What are the differences between Long-Polling, Websockets and Server-Sent Events?
https://medium.com/system-design-blog/long-polling-vs-websockets-vs-server-sent-events-c43ba96df7c1
Server Sent Events example: feed, sport score


4: * Explain the following request and response headers:
  4.1: * Diff. between Expires, Date, Age and If-Modified-...
        MDN
  4.2: * Do Not Track
        https://www.avast.com/c-what-is-do-not-track
  4.3: * Cache-Control
        private, max-age=XXXX, no-cache
  4.4: * Transfer-Encoding
        https://www.geeksforgeeks.org/http-headers-transfer-encoding/
  4.5: * ETag
        token to avoid the redownload if no change
  4.6: * X-Frame-Options
        The X-Frame-Options HTTP response header can be used to indicate whether or not a browser should be allowed to render a page in a <frame>, <iframe>, <embed> or <object>.



5: * What are HTTP methods? List all HTTP methods that you know, and explain them.
HTTP defines a set of request methods to indicate the desired action to be performed for a given resource
GET, HEAD, POST, PUT, DELETE, CONNECT, OPTIONS, TRACE, PATH


6: * What is domain pre-fetching and how does it help with performance?
https://www.keycdn.com/support/prefetching

7: * What is a CDN and what is the benefit of using one?
Content Delivery Network
https://medium.com/pixboost/cdn-explained-why-when-and-how-to-use-it-for-your-website-7d360a93cc04

