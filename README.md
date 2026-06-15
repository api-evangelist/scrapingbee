# ScrapingBee (scrapingbee)

ScrapingBee is a France-based web scraping API that handles headless browsers, proxy rotation, anti-bot defenses, and CAPTCHA solving so developers can extract data from any website with a single API call. The platform exposes a unified HTML scraping endpoint alongside dedicated APIs for Google Search, Amazon, Walmart, YouTube, and ChatGPT, with JavaScript rendering, AI-powered data extraction, screenshots, and an MCP server for agentic workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scrapingbee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scrapingbee/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI Extraction
- Anti-Bot
- Data Aggregation
- Data Extraction
- Headless Browser
- JavaScript Rendering
- Proxy Rotation
- Screenshots
- Search Engine
- Web Scraping

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-25

## APIs

### ScrapingBee HTML API

The core HTML API extracts rendered HTML, screenshots, or structured JSON from any website using headless Chrome with automatic proxy rotation. Supports JavaScript rendering (5 credits per request), js_scenario for automated clicks/scroll/form-fill interactions, wait/wait_for/wait_browser timing controls, residential premium_proxy (10-25 credits), stealth_proxy pool (75 credits), country_code geotargeting, custom cookies and headers, and AI-powered extraction via the ai_query parameter or CSS/XPath extract_rules.

- **Human URL:** [https://www.scrapingbee.com](https://www.scrapingbee.com)
- **Base URL:** `https://app.scrapingbee.com/api/v1`

#### Tags

- HTML Extraction
- JavaScript Rendering
- Headless Browser
- Web Scraping
- Screenshots

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/)
- [Getting Started](https://www.scrapingbee.com/documentation/#quickstart)
- [Authentication](https://www.scrapingbee.com/documentation/#authentication)
- [OpenAPI](openapi/scrapingbee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrapingbee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapingbee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ScrapingBee Google Search API

The Google Search API returns structured JSON SERP data covering organic results, knowledge graph, featured snippets, related searches, news, maps, image results, and ads. Supports search_type (web, news, maps, images), country_code localization, light_request mode for cheaper faster queries, full_html alongside structured output, and any extra Google query parameters (gl, hl, num, start).

- **Human URL:** [https://www.scrapingbee.com/documentation/google/](https://www.scrapingbee.com/documentation/google/)
- **Base URL:** `https://app.scrapingbee.com/api/v1/google`

#### Tags

- Search Engine
- SERP
- Google
- Structured Data

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/google/)
- [Postman Collection](collections/scrapingbee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapingbee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ScrapingBee Data Extraction API

The Data Extraction API layers structured-data extraction rules on top of HTML API calls so callers receive parsed JSON instead of raw HTML. Supports CSS selectors, XPath expressions, nested objects and arrays, attribute extraction, and AI-powered natural-language extraction where you describe what you need in plain English.

- **Human URL:** [https://www.scrapingbee.com/features/data-extraction/](https://www.scrapingbee.com/features/data-extraction/)
- **Base URL:** `https://app.scrapingbee.com/api/v1`

#### Tags

- AI Extraction
- Data Extraction
- Structured Data
- CSS Selectors

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/data-extraction/)
- [Postman Collection](collections/scrapingbee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapingbee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ScrapingBee AI Web Scraping API

The AI Web Scraping API leverages LLM-driven extraction to lift content from web pages by expressing what you need in plain English via the ai_query parameter, with no CSS selectors, XPath, or parsing code required. Supports JSON and Markdown output for downstream agentic use.

- **Human URL:** [https://www.scrapingbee.com/features/ai-web-scraping-api/](https://www.scrapingbee.com/features/ai-web-scraping-api/)
- **Base URL:** `https://app.scrapingbee.com/api/v1`

#### Tags

- AI
- LLM
- Data Extraction
- Natural Language

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/)
- [Postman Collection](collections/scrapingbee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapingbee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ScrapingBee Screenshot API

The Screenshot API captures full-page or viewport screenshots of any URL using headless Chrome, with control over viewport size, full_page rendering, image format, and combination with JavaScript scenarios for capturing post-interaction states.

- **Human URL:** [https://www.scrapingbee.com/features/screenshot-api/](https://www.scrapingbee.com/features/screenshot-api/)
- **Base URL:** `https://app.scrapingbee.com/api/v1`

#### Tags

- Screenshots
- Headless Browser
- Image Capture

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/#screenshot)
- [Postman Collection](collections/scrapingbee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapingbee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.scrapingbee.com)
- [Documentation](https://www.scrapingbee.com/documentation/)
- [Getting Started](https://www.scrapingbee.com/documentation/#quickstart)
- [Pricing](https://www.scrapingbee.com/pricing/)
- [Blog](https://www.scrapingbee.com/blog/)
- [Sign Up](https://app.scrapingbee.com/account/register)
- [Login](https://app.scrapingbee.com/account/login)
- [Support](https://help.scrapingbee.com)
- [Status](https://status.scrapingbee.com)
- [Changelog](https://www.scrapingbee.com/changelog/)
- [Terms of Service](https://www.scrapingbee.com/terms-and-conditions/)
- [Privacy Policy](https://www.scrapingbee.com/privacy-policy/)
- [GitHub Organization](https://github.com/ScrapingBee)
- [LinkedIn](https://www.linkedin.com/company/scrapingbee)
- [Python S D K](https://github.com/ScrapingBee/scrapingbee-python)
- [Node S D K](https://github.com/ScrapingBee/scrapingbee-node)
- [C L I](https://github.com/ScrapingBee/scrapingbee-cli)
- [Postman Collection](https://www.postman.com/api-evangelist/scraping/documentation/ygpc6xm/scrapingbee) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [M C P Server](https://github.com/ScrapingBee/mcp-server)
- [Integration](https://github.com/ScrapingBee/scrapingbee-n8n)
- [Integration](https://github.com/ScrapingBee/scrapy-scrapingbee)
- [Integration](https://github.com/ScrapingBee/langchain-scrapingbee)
- [Plans](plans/scrapingbee-plans-pricing.yml)
- [Rate Limits](rate-limits/scrapingbee-rate-limits.yml)
- [Fin Ops](finops/scrapingbee-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
