# Awesome API Schema & OpenAPI Previewer [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, renderers, editors, and SaaS platforms for viewing, interacting with, and rendering OpenAPI (Swagger) and API schemas.

---

## Sector Overview & Market Dynamics

The global API management and documentation tooling sector is estimated at **$8.0B – $10.3B** (projected to reach over $30B+ by 2030 at ~16%–25% CAGR), with developer documentation tools accounting for over $1B in North America alone. The market exhibits a **bifurcated, moderately concentrated structure at the enterprise management layer** (where major cloud platforms and incumbents like Microsoft, AWS, Google Cloud/Apigee, and Postman command a substantial revenue share), but remains **highly fragmented across the documentation, previewer, and DX tooling layer**, where nimble open-source renderers and specialized modern SaaS platforms compete aggressively for developer mindshare without a single winner-take-all monopoly.

---

## SaaS Platforms & Hosted Previewers

A comparison of commercial and hosted API documentation and previewer platforms, sorted in descending order by company scale (valuation / annual revenue).

| Product | Company Scale (Valuation / Revenue) | Pricing (Starting Paid Tier) | Free Tier / Trial Limits | Key Strengths & Focus |
|---|---|---|---|---|
| **[Postman](https://www.postman.com/)** | **$5.6B Valuation** (~$434M total funding raised) | **$9 / user / month** (billed annually, Solo plan) or **$19 / user / month** (billed annually, Team plan) | **Free forever**: 1 user seat, unlimited collection runs, unlimited local/cloud mock servers, native Git sync, 50 AI credits/mo, and up to 1,000 API monitoring requests/mo. | Industry-standard API client and workspace with integrated schema documentation preview, API governance, and test automation. |
| **[Stoplight (SmartBear)](https://stoplight.io/)** | **$1.8B+ Valuation** ($250M+ ARR, parent SmartBear) | **$39 / month** (billed annually, Starter plan; SwaggerHub at $19/user/month) | **Free forever**: 1 user seat, single workspace, basic API design/mocking/docs preview with limited public/private projects. (Plus a 14-day full Pro trial). | Design-first API ecosystem featuring Spectral linting, Prism mock servers, and embeddable Elements renderer. |
| **[Mintlify](https://mintlify.com/)** | **$500M Valuation** (~$23M ARR, Series B) | **$450 / month** (billed annually) or $540 / month (billed monthly, Pro plan) | **Free forever (Starter)**: Up to 5 editor seats, full core docs platform, custom domain support, web editor, GitHub sync, search, MCP server, and interactive API playground (excludes automated AI writing assistant, analytics, and password protection). | AI-native documentation platform tailored for modern developer experience, lightning-fast setup, and MDX components. |
| **[Fern](https://buildwithfern.com/)** | **~$33M – $53M Valuation** (~$3.3M ARR; acquired by Postman in Jan 2026) | **Enterprise custom pricing** (previously Team plan at $150/mo; paid tier now sales-led) | **Free forever (Developer)**: Up to 10 team members, 1 site, 1,000 pages, API explorer, web editor, MCP servers, and 250 AI credits/month. | OpenAPI to interactive docs with built-in, multi-language idiomatic client SDK generation (TypeScript, Python, Go, Java). |
| **[ReadMe](https://readme.com/)** | **~$10M+ ARR** (~$10.3M total VC funding) | **$250 / month** (billed annually, Pro plan; 14-day free trial) | **Free forever (Starter)**: 1 project, 1 editor seat, custom domain, bi-directional Git sync, interactive API reference, customizable themes, 7-day analytics, and `llms.txt`/MCP server. | Interactive API developer portals with personalized API key injection, metrics/API logs explorer, and live playgrounds. |
| **[Scalar (Hosted)](https://scalar.com/)** | **Seed-stage Startup** (~16.4k GitHub stars on open-source engine) | **$150 / month** ($125/mo billed annually, Pro plan; starts with 7-day trial) | **Free forever**: Up to 3 APIs, 1 editor seat, 1 SDK target up to 25 endpoints, beautiful hosted docs, and landing page generator. | Ultra-fast OpenAPI 3.1 & 3.0 renderer with built-in modern API client, search, and native framework adapters. |
| **[Redocly](https://redocly.com/)** | **Bootstrapped / Profitable Scale-up** (Seed funded ~$2.8M) | **$249 / month** (billed annually at $2,988/yr, Pro plan) | **No permanent free hosted tier** (offers a **30-day free trial** of Pro/Scale plans with no credit card required; core Redoc CE renderer is free and open source forever). | Enterprise-grade API documentation portals, multi-format (OpenAPI, GraphQL, AsyncAPI) support, and flat-rate pricing with unlimited seats. |

---

## Open-Source Renderers & Tools

Standalone, open-source libraries and components that can be self-hosted or embedded into web applications.

| Project | License | GitHub Stars | Strengths & Verified Details |
|---|---|---|---|
| **[Redoc](https://github.com/Redocly/redoc)** | MIT | ~26,000 | Clean three-column layout with sticky sidebar navigation. Best-in-class for long-form reference reading and comprehensive documentation sites. |
| **[Scalar](https://github.com/scalar/scalar)** | MIT (renderer) | ~16,400 | Modern, ultra-responsive UI supporting OpenAPI 3.1/3.0. Features an integrated API client, theme customization, and default adoption in ASP.NET Core. |
| **[Swagger Editor](https://github.com/swagger-api/swagger-editor)** | Apache-2.0 | ~9,500 | Browser-based visual and code editor for authoring and validating OpenAPI/Swagger definitions with live preview panel. |
| **[Stoplight Elements](https://github.com/stoplightio/elements)** | Apache-2.0 | ~2,500 | Drop-in Web Components designed for easy embedding into existing sites, React applications, or static documentation portals. |
| **[RapiDoc](https://github.com/rapi-doc/RapiDoc)** | MIT | ~1,900 | Zero-build self-hosting via a single `<rapi-doc>` custom HTML element. Highly configurable, customizable styling, and built-in interactive console. |

---

## Contributing

Contributions are welcome! Please read the contribution guidelines before submitting a pull request.
