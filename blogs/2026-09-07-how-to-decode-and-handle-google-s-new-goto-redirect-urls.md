---
title: "How to Decode and Handle Google's New /goto Redirect URLs"
url: "https://www.scrapingbee.com/blog/google-goto-redirect-urls/"
date: "2026-09-07"
feed_url: "https://www.scrapingbee.com/blog/index.xml"
---
Google /goto redirect URLs are starting to appear in Search results instead of direct destination links, often carrying opaque CAES tokens that are not immediately useful to scrapers. In this article, we'll look at how to decode Google /goto URLs, what the CAES token actually contains, when these redirects tend to appear, and how to resolve them efficiently in Python. We'll also walk through our own browser and scraping experiments and show a practical way to handle /goto links in a real Google scraper.
