# ScrapingBee (scrapingbee)
ScrapingBee is a France-based web scraping API that handles headless browsers, proxy rotation, anti-bot defenses, and CAPTCHA solving so developers can extract data from any website with a single API call. The platform exposes a unified HTML scraping endpoint alongside dedicated APIs for Google Search, Amazon, Walmart, YouTube, and ChatGPT, with JavaScript rendering, AI-powered data extraction, screenshots, and an MCP server for agentic workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/scrapingbee/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags:

 - AI Extraction, Anti-Bot, Data Aggregation, Data Extraction, Headless Browser, JavaScript Rendering, Proxy Rotation, Screenshots, Search Engine, Web Scraping

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-25

## APIs

### ScrapingBee HTML API
The core HTML API extracts rendered HTML, screenshots, or structured JSON from any website using headless Chrome with automatic proxy rotation. Supports JavaScript rendering, js_scenario interactions, wait/wait_for/wait_browser timing, residential premium_proxy, stealth_proxy pool, country_code geotargeting, custom cookies and headers, and AI extraction via ai_query or CSS/XPath extract_rules.

**Human URL:** [https://www.scrapingbee.com](https://www.scrapingbee.com)

**Base URL:** https://app.scrapingbee.com/api/v1

#### Tags:

 - HTML Extraction, JavaScript Rendering, Headless Browser, Web Scraping, Screenshots

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/)
- [GettingStarted](https://www.scrapingbee.com/documentation/#quickstart)
- [Authentication](https://www.scrapingbee.com/documentation/#authentication)
- [OpenAPI](openapi/scrapingbee-openapi.yml)

### ScrapingBee Google Search API
Returns structured JSON SERP data covering organic results, knowledge graph, featured snippets, related searches, news, maps, image results, and ads. Supports search_type, country_code localization, light_request mode, and full_html.

**Human URL:** [https://www.scrapingbee.com/documentation/google/](https://www.scrapingbee.com/documentation/google/)

**Base URL:** https://app.scrapingbee.com/api/v1/google

#### Tags:

 - Search Engine, SERP, Google, Structured Data

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/google/)

### ScrapingBee Data Extraction API
Structured-data extraction layered on HTML API calls. CSS selectors, XPath, nested objects, arrays, attribute extraction, and AI-powered natural-language extraction.

**Human URL:** [https://www.scrapingbee.com/features/data-extraction/](https://www.scrapingbee.com/features/data-extraction/)

**Base URL:** https://app.scrapingbee.com/api/v1

#### Tags:

 - AI Extraction, Data Extraction, Structured Data, CSS Selectors

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/data-extraction/)

### ScrapingBee AI Web Scraping API
LLM-driven extraction that lifts content from web pages by expressing what you need in plain English via the ai_query parameter. No CSS selectors, XPath, or parsing code required. JSON and Markdown output.

**Human URL:** [https://www.scrapingbee.com/features/ai-web-scraping-api/](https://www.scrapingbee.com/features/ai-web-scraping-api/)

**Base URL:** https://app.scrapingbee.com/api/v1

#### Tags:

 - AI, LLM, Data Extraction, Natural Language

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/)

### ScrapingBee Screenshot API
Captures full-page or viewport screenshots of any URL using headless Chrome, with viewport, full_page, format, and js_scenario controls.

**Human URL:** [https://www.scrapingbee.com/features/screenshot-api/](https://www.scrapingbee.com/features/screenshot-api/)

**Base URL:** https://app.scrapingbee.com/api/v1

#### Tags:

 - Screenshots, Headless Browser, Image Capture

#### Properties

- [Documentation](https://www.scrapingbee.com/documentation/#screenshot)

## Common Properties

- [Website](https://www.scrapingbee.com)
- [Documentation](https://www.scrapingbee.com/documentation/)
- [GettingStarted](https://www.scrapingbee.com/documentation/#quickstart)
- [Pricing](https://www.scrapingbee.com/pricing/)
- [Blog](https://www.scrapingbee.com/blog/)
- [SignUp](https://app.scrapingbee.com/account/register)
- [Login](https://app.scrapingbee.com/account/login)
- [Support](https://help.scrapingbee.com)
- [Status](https://status.scrapingbee.com)
- [ChangeLog](https://www.scrapingbee.com/changelog/)
- [TermsOfService](https://www.scrapingbee.com/terms-and-conditions/)
- [PrivacyPolicy](https://www.scrapingbee.com/privacy-policy/)
- [GitHubOrganization](https://github.com/ScrapingBee)
- [LinkedIn](https://www.linkedin.com/company/scrapingbee)
- [PythonSDK](https://github.com/ScrapingBee/scrapingbee-python)
- [NodeSDK](https://github.com/ScrapingBee/scrapingbee-node)
- [CLI](https://github.com/ScrapingBee/scrapingbee-cli)
- [PostmanCollection](https://www.postman.com/api-evangelist/scraping/documentation/ygpc6xm/scrapingbee)
- [MCPServer](https://github.com/ScrapingBee/mcp-server)
- [Integration: n8n](https://github.com/ScrapingBee/scrapingbee-n8n)
- [Integration: Scrapy](https://github.com/ScrapingBee/scrapy-scrapingbee)
- [Integration: LangChain](https://github.com/ScrapingBee/langchain-scrapingbee)
- [Plans](plans/scrapingbee-plans-pricing.yml)
- [RateLimits](rate-limits/scrapingbee-rate-limits.yml)
- [FinOps](finops/scrapingbee-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
