---
title: General Questions
layout: layouts/page.njk
permalink: /questions/general-questions/index.html
---

* What did you learn yesterday/this week?
* What excites or interests you about coding?
* What is a recent technical challenge you experienced and how did you solve it?
* When building a new web site or maintaining one, can you explain some techniques you have used to increase performance?
* Can you describe some SEO best practices or techniques you have used lately?
* Can you explain any common techniques or recent issues solved in regards to front-end security?


* What actions have you personally taken on recent projects to increase maintainability of your code?


* Talk about your preferred development environment.
==> mac or linux with vim

* Which version control systems are you familiar with?
==> git

* Can you describe your workflow when you create a web page?
==> planning, wire frame; design; coding; refactoring

* If you have 5 different stylesheets, how would you best integrate them into the site?
==> Performance-wise, HTTP requests are expensive. Devs should do well to minimize the number of stylessheets, minimize the http requests.
==> in most cases, build one big sylesheet; it also depends on the site; concatenating multiple stylesheets via gulp, webpack.

* Can you describe the difference between progressive enhancement and graceful degradation?
==>Graceful degradation is the practice of building an application for modern browsers while ensuring it remains functional in older browsers.
==>Progressive enhancement is the practice of building an application for a base level of user experience, but adding functional enhancements when a browser supports it.

* How would you optimize a website's assets/resources?
==> make all assets small/compressed as possible; Set servers caching parameters to deliver your assets more efficiently;
    avoid unnecessary assets/avoid too many server requests on pages; use svg, use icon; TinyPNG,
* How many resources will a browser download from a given domain at a time?
==> it depends on browsers. Most can allow 6 concurrent connections.

* What are the exceptions?
==> When a JavaScript statement generates an error, it is said to throw an exception.  Instead of proceeding to the next statement,
    the JavaScript interpreter checks for exception handling code.
    If there is no exception handler, then the program returns from whatever function threw the exception.
    This is repeated for each function on the call stack until an exception handler is found or until the top level function is reached,
    causing the program to terminate.

* Name 3 ways to decrease page load (perceived or actual load time).
==> compress and optimize image; reduce redirects; cache web page; enable browser caching; asynchroonous loading css and js file; minify css and js (bundle size); CDN; minimize http requests; defer js load; reducer server response time; lazy loading;reduce external script;

* If you jumped on a project and they used tabs and you used spaces, what would you do?
==> linting kicks in

* Describe how you would create a simple slideshow page.

* If you could master one technology this year, what would it be?
Rust

* Explain the importance of standards and standards bodies.


* What is Flash of Unstyled Content? How do you avoid FOUC?
==> A flash of unstyled content (FOUC, also flash of unstyled text) is an instance where a web page appears briefly with the browser's default styles prior to loading an external CSS stylesheet,
    due to the web browser engine rendering the page before all information is retrieved.

    put styles on the top

* Explain what ARIA and screenreaders are, and how to make a website accessible.
* Explain some of the pros and cons for CSS animations versus JavaScript animations.
==> https://www.vibrantsoftware.com/resources/blog/vibrant/2017/05/03/using-css-animations-vs-javascript-animations
* What does CORS stand for and what issue does it address?
==> smae-origin policy is an important concept in the web security model.

* How did you handle a disagreement with your boss or your collaborator?
* What resources do you use to learn about the latest in front end development and design?
* What skills are needed to be a good front-end developer?
==> js, css, html, CLI, git, responsiveness, system design,
* What role do you see yourself?
* Explain the difference between cookies, session storage, and local storage?
==> https://krishankantsinghal.medium.com/local-storage-vs-session-storage-vs-cookie-22655ff75a8
