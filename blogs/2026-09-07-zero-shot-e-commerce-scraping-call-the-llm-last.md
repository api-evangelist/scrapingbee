---
title: "Zero-Shot E-Commerce Scraping: Call the LLM Last"
url: "https://www.scrapingbee.com/blog/ecommerce-scraping-cascade-scrapy-local-llm/"
date: "2026-09-07"
feed_url: "https://www.scrapingbee.com/blog/index.xml"
---
When a scraper breaks, the reflex is to reach for a language model. For zero-shot e-commerce scraping, that reflex is usually the most expensive move you can make: a model call per page cost me about 30 seconds on local hardware. The product data is often already in the page as JSON, and much of the drift that follows a site change heals without a model.
