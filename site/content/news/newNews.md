---
newstitle: New News No 2
date: 2017-03-22T15:04:10.000Z
description: >-
  Web Site generators render content into HTML files. Most are “dynamic site
  generators.” That means the HTTP server (which is the program running on your
  website that the user’s browser talks to) runs the generator
image: /img/news/mediummembers.png
---

Creating the Page dynamically means that the computer hosting the HTTP server has to have enough memory and CPU to effectively run the generator around the clock. If not, then the user has to wait in a queue for the page to be generated.

Nobody wants users to wait longer than needed, so the dynamic site generators programmed their systems to cache the HTML files. When a file is cached, a copy of it is temporarily stored on the computer. It is much faster for the HTTP server to send that copy the next time the page is requested than it is to generate it from scratch.

## The little secrets of Chemex brewing

Hugo takes caching a step further. All HTML files are rendered on your computer. You can review the files before you copy them to the computer hosting the HTTP server. Since the HTML files aren’t generated dynamically, we say that Hugo is a “static site generator.”

Not running a web site generator on your HTTP server has many benefits. The most noticeable is performance - HTTP servers are very good at sending files. So good that you can effectively serve the same number of pages with a fraction of the memory and CPU needed for a dynamic site.

Hugo has two components to help you build and test your web site. The one that you’ll probably use most often is the built-in HTTP server. When you run hugo server, Hugo renders all of your content into HTML files and then runs an HTTP server on your computer so that you can see what the pages look like.