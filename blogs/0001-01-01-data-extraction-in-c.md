---
title: "Data extraction in C#"
url: "https://www.scrapingbee.com/tutorials/data-extraction-in-c/"
date: "Mon, 01 Jan 0001 00:00:00 +0000"
author: ""
feed_url: "https://www.scrapingbee.com/index.xml"
---
<p>One of the most important features of ScrapingBee, is the ability to extract exact data without need to post-process the request’s content using external libraries.</p>
<p>We can use this feature by specifying an additional parameter with the name <code>extract_rules</code>. We specify the label of elements we want to extract, their CSS Selectors and ScrapingBee will do the rest!</p>
<p>Let’s say that we want to extract the title &amp; the subtitle of the <a href="https://www.scrapingbee.com/documentation/data-extraction/">data extraction documentation page</a>. Their CSS selectors are <code>h1</code> and <code>span.text-[20px]</code> respectively. To make sure that they’re the correct ones, you can use the JavaScript function: <code>document.querySelector(&quot;CSS_SELECTOR&quot;)</code> in that page’s developer tool’s console.</p>
