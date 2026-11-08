# Awesome-API-Schema-Openapi-Previewer

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **your list mixes renderers, editors, and hosted docs platforms**, and the open-source star counts are missing.



## The category problem



Your list combines three different layers:



- **Renderers** (Redoc, RapiDoc, Scalar, Stoplight Elements, Swagger UI): they take an OpenAPI spec and display it. All are open source (MIT or Apache 2.0) .

- **Editors** (Swagger Editor): it is an authoring tool, not a previewer. It is Apache 2.0 and runs in the browser .

- **Hosted platforms** (Mintlify, Fern): they include renderers but are commercial docs platforms, not standalone previewers .



Listing them as alternatives to each other will mislead readers.



## What the search results actually contain



**Open-source renderers (usable):**



| Renderer | License | Key strength | Verified detail |

|---|---|---|---|

| **Redoc** | MIT | Long-form reference reading | Three-column layout, sticky sidebar, best for comprehension over execution  |

| **Scalar** | MIT (renderer); SDK generator proprietary | Modern UI, OpenAPI 3.1, AI-era features | Free hosted docs; Pro $150/month . GitBook's API explorer is powered by Scalar  |

| **RapiDoc** | MIT | Self-hosting, one script tag | Single web component, HTML attributes, near-zero build tooling  |

| **Stoplight Elements** | Apache-2.0 | Embedding into existing sites | Web components designed for embedding; v9.0.0  |

| **Swagger Editor** | Apache-2.0 | Editing OpenAPI/Swagger | Browser-based editor, dist v4.14.8  |



**No star counts surfaced** for Redoc, Scalar, RapiDoc, Elements, or Swagger Editor in these results.



**SaaS pricing (usable):**

- **Mintlify**: Starter **$0/month** (5 editor seats, full platform, custom domain, MCP server, API playground); Pro **$450/month annual** or $540 monthly; Enterprise contact .

- **Fern**: Hobby **$0** (2 team members, 250 AI credits); Team **$150/month** with 25% annual discount; Enterprise custom .

- **Scalar**: Free; Pro **$150/month**; Business **$600/month**; Enterprise custom .



**What is missing:**

- **No pricing** for Postman Schema Documentation Preview or Microcks Schema Viewer.

- **No star counts** for any open-source project.

- **No information** on "Docusaurus OpenAPI" as a distinct product—Docusaurus is a static site generator; OpenAPI rendering requires plugins, and no such plugin surfaced.



## What I recommend



**Split into two honest categories:**



**1. Open-Source Renderers** (strong section):

- **Redoc** (MIT) — long-form reference 

- **Scalar** (MIT renderer) — modern UI, OpenAPI 3.1 

- **RapiDoc** (MIT) — self-hosting, single script tag 

- **Stoplight Elements** (Apache-2.0) — embeddable web components 

- **Swagger Editor** (Apache-2.0) — editor, not a renderer 



**2. Hosted Docs Platforms** (proprietary):

- **Mintlify** — $0 Starter, $450/month Pro 

- **Fern** — $0 Hobby, $150/month Team 

- **Scalar** — $0 Free, $150/month Pro 



**Remove or reframe:**

- **Postman Schema Documentation Preview** — mark "pricing not surfaced"; it is a feature inside a proprietary client.

- **Microcks Schema Viewer** — Microcks is an open-source mocking/testing platform , not primarily a previewer. It belongs in a mocking list.

- **Docusaurus OpenAPI** — no such standalone product surfaced; Docusaurus is a static site generator requiring plugins.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate star counts, invent pricing for Postman or Microcks, or present Docusaurus as an OpenAPI previewer.
