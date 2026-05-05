---
title: "How to extract content from a Shadow DOM"
url: "https://www.scrapingbee.com/tutorials/how-to-extract-content-from-a-shadow-dom/"
date: "Mon, 01 Jan 0001 00:00:00 +0000"
author: ""
feed_url: "https://www.scrapingbee.com/index.xml"
---
<p>Certain websites may hide all of their page content inside a shadow root, which makes scraping them quite challenging. This is because most scrapers cannot directly access HTML content embedded within a shadow root. Here is a guide on how you can extract such data via ScrapingBee.</p>
<hr />
<p>We will use a quite popular site as an example: <a href="http://www.msn.com/">www.msn.com</a><br />If you inspect any article on this page, let’s use this <a href="https://www.msn.com/en-us/lifestyle/lifestyle-buzz/kate-middleton-and-prince-william-s-new-home-forest-lodge-almost-went-to-a-different-royal-couple/ar-AA1KNPyI?ocid=hpmsn&amp;amp;cvid=68a6f93e8ed04131b40f3dc49ecfba6c&amp;amp;ei=18">one</a>. You can see that all of its contents are inside a shadow root:<br /><img alt="" src="https://www.scrapingbee.com/uploads/image-11.png" /></p>
