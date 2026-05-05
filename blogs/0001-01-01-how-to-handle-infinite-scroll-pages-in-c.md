---
title: "How to handle infinite scroll pages in C#"
url: "https://www.scrapingbee.com/tutorials/how-to-handle-infinite-scroll-pages-in-c/"
date: "Mon, 01 Jan 0001 00:00:00 +0000"
author: ""
feed_url: "https://www.scrapingbee.com/index.xml"
---
<p>Nowadays, most websites use different methods and techniques to decrease the load and data served to their clients’ devices. One of these techniques is the infinite scroll.</p>
<p>In this tutorial, we will see how we can scrape <a href="https://www.scrapingbee.com/blog/infinite-scroll-puppeteer/">infinite scroll</a> web pages using a <a href="https://www.scrapingbee.com/documentation/js-scenario/">js_scenario</a>, specifically the <code>scroll_y</code> and <code>scroll_x</code> features. And we will use <a href="https://demo.scrapingbee.com/infinite_scroll.html">this page</a> as a demo. Only 9 boxes are loaded when we first open the page, but as soon as we scroll to the end of it, we will load 9 more, and that will keep happening each time we scroll to the bottom of the page.</p>
