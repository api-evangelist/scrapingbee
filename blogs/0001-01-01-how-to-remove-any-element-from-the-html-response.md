---
title: "How to remove any element from the HTML response"
url: "https://www.scrapingbee.com/tutorials/how-to-remove-any-element-from-the-html-response/"
date: "Mon, 01 Jan 0001 00:00:00 +0000"
author: ""
feed_url: "https://www.scrapingbee.com/index.xml"
---
<p>Sometimes you may need to remove specific HTML elements from the page's content, either to get cleaner results for your <a href="https://www.scrapingbee.com/documentation/data-extraction/">data extraction rules</a>, or to simply delete unnecessary content from your response.</p>
<p>To achieve that using ScrapingBee, you can use a<a href="https://www.scrapingbee.com/documentation/js-scenario/">JavaScript Scenario</a>, with an evaluate instruction and execute this custom JS code:</p>
<pre tabindex="0"><code>document.querySelectorAll("ELEMENT-CSS-SELECTOR").forEach(function(e){e.remove();});​
</code></pre><p>For example, to remove all of the &lt;style&gt; elements from the response, you can use this JavaScript Scenario:</p>
