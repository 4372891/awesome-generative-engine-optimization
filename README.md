# Awesome Generative Engine Optimization - Open Source GEO Tools 🚀

A curated directory of open-source GEO tools. Built specifically for startups, consultants, and developers optimizing web infrastructure for LLMs, RAG systems, and AI search engines (ChatGPT, Perplexity, Gemini, Claude).

## 1. Technical GEO & Ingestion Infrastructure
 
### 1a. AI crawler access & bot rules
 
| Repo | ⭐ | What it does |
|---|---|---|
| [ai-robots-txt/ai.robots.txt](https://github.com/ai-robots-txt/ai.robots.txt) | 3.9k | Community list of AI crawlers with ready-made robots.txt, .htaccess, Nginx, Caddy, and HAProxy configs. The standard starting point. |
| [ipanalytics/AI-Crawler-Blocklist](https://github.com/ipanalytics/ai-crawler-blocklist) | 2 | AI crawler lists and firewall snippets from official operator sources, including verified IP lists and robots.txt presets (training opt-out, search-safe). |
| [josezuma/ai-crawlers](https://github.com/josezuma/ai-crawlers) | – | Machine-readable dataset of AI crawler user agents with robots.txt recipes, verified weekly. |
| [henu-wang/ai-crawlers-reference](https://github.com/henu-wang/ai-crawlers-reference) | 1 | Database of AI search crawler user agents with robots.txt examples. |
| [henu-wang/ai-robots-txt-generator](https://github.com/henu-wang/ai-robots-txt-generator) | 3 | Generates robots.txt rules for GPTBot, PerplexityBot, ClaudeBot, and similar crawlers. |
| [GGeronik/consent-txt](https://github.com/GGeronik/consent-txt) | 1 | Define AI permissions once; outputs robots.txt, AIPREF headers, X-Robots-Tag, and TDMRep rules. |
| [First-Point/ai-txt-skill](https://github.com/First-Point/ai-txt-skill) | 2 | Claude Code skill that generates and audits ai.txt, robots.txt, llms.txt, and TDM opt-out files. |
| [lord-alfred/ipranges](https://github.com/lord-alfred/ipranges) | – | Daily-updated IP ranges by provider, for confirming a "GPTBot" visit really comes from OpenAI. |
| [TecharoHQ/anubis](https://github.com/TecharoHQ/anubis) | – | Proof-of-work reverse proxy that blocks scrapers while letting chosen crawlers through. |
| [samber/the-great-gpt-firewall](https://github.com/samber/the-great-gpt-firewall) | – | Tracks which websites restrict AI crawlers. |
 
### 1b. AI crawler logs & bot traffic
 
| Repo | ⭐ | What it does |
|---|---|---|
| [siteline-ai/agent-analytics-skill](https://github.com/siteline-ai/agent-analytics-skill) | – | Pulls AI bot visits from server logs, classifies 30+ bots, links them to AI referral traffic, and writes a recommendations report. |
| [PascaleBeier/hitkeep](https://github.com/PascaleBeier/hitkeep) | 93 | Open-source, AI-native web analytics; self-hosted as one Go binary. |
| [stani-chirk/logwick](https://github.com/stani-chirk/logwick) | 5 | Self-hosted server log analytics that classifies AI bots like GPTBot and ClaudeBot. |
| [surfacedby/ai-traffic-alerts-for-cloudflare](https://github.com/surfacedby/ai-traffic-alerts-for-cloudflare) | 4 | Cloudflare Worker that alerts you when AI assistants send visitors or AI crawlers arrive. |
| [arturseo-geo/mcp-crawl-parity](https://github.com/arturseo-geo/mcp-crawl-parity) | 1 | MCP server comparing Googlebot vs AI crawler behavior using Nginx logs and Search Console data. |
| [abbottis/logwerk](https://github.com/abbottis/logwerk) | 1 | Offline-first server log analyzer dashboard that runs entirely in the browser. |
| [monteduro/laravel-datafast-aicrawl](https://github.com/monteduro/laravel-datafast-aicrawl) | 2 | Server-side AI crawler tracking for Laravel apps. |
| [allinurl/goaccess](https://github.com/allinurl/goaccess) | – | Real-time terminal log analyzer; shows which AI crawlers hit which URLs. |
| [matomo-org/device-detector](https://github.com/matomo-org/device-detector) | – | User-agent parser with bot definitions for classifying crawler traffic. |
 
### 1c. llms.txt — spec, generators, directories
 
| Repo | ⭐ | What it does |
|---|---|---|
| [AnswerDotAI/llms-txt](https://github.com/AnswerDotAI/llms-txt) | 2.4k | Home of the /llms.txt specification plus its reference parser and CLI tools. |
| [langchain-ai/mcpdoc](https://github.com/langchain-ai/mcpdoc) | 1k | Serves llms.txt sources to IDEs and agents over MCP. |
| [thedaviddias/llms-txt-hub](https://github.com/thedaviddias/llms-txt-hub) | 914 | Large directory of sites and tools that publish or implement llms.txt. |
| [firecrawl/create-llmstxt-py](https://github.com/firecrawl/create-llmstxt-py) | 326 | Generates llms.txt and llms-full.txt for any website using Firecrawl and OpenAI. MIT. |
| [madarco/ragrabbit](https://github.com/madarco/ragrabbit) | 136 | Self-hosted AI site search that also generates llms.txt from its index. |
| [mensfeld/llm-docs-builder](https://github.com/mensfeld/llm-docs-builder) | 96 | Converts markdown docs into LLM/RAG-ready output and builds llms.txt automatically. |
| [thedaviddias/mcp-llms-txt-explorer](https://github.com/thedaviddias/mcp-llms-txt-explorer) | 78 | MCP server for exploring websites that publish llms.txt. |
| [dotenvx/llmstxt](https://github.com/dotenvx/llmstxt) | – | Turns an existing sitemap.xml into llms.txt with one npx command. |
| [apify/actor-llmstxt-generator](https://github.com/apify/actor-llmstxt-generator) | – | Crawls a site and outputs llms.txt (Apify Actor). |
| [raphaelstolt/llms-txt-php](https://github.com/raphaelstolt/llms-txt-php) | – | PHP library to write, read, and validate llms.txt. |
| [robbrad/llmstxt-generator-github-action](https://github.com/robbrad/llmstxt-generator-github-action) | – | GitHub Action that builds llms.txt and llms-full.txt from markdown docs. |
| [josezuma/llmstxt-gen](https://github.com/josezuma/llmstxt-gen) | – | CLI that generates llms.txt from any website. |
| [shimo4228/llms-txt-writer](https://github.com/shimo4228/llms-txt-writer) | 3 | Claude Code skill that writes and checks llms.txt and FAQ docs against AI citation research. |
| [silverbackmarketing/ai-readiness](https://github.com/silverbackmarketing/ai-readiness) | 3 | Generates 18 AI-readiness files (llms.txt, ai.txt, and more) from one command. |
 
### 1d. llms.txt & AI-readiness plugins by platform
 
| Platform | Repo | ⭐ | What it does |
|---|---|---|---|
| Next.js | [TurboDocx/next-plugin-llms](https://github.com/TurboDocx/next-plugin-llms) | – | Scans the app directory and generates llms.txt and llms-full.txt. |
| Nuxt | [nuxt-content/nuxt-llms](https://github.com/nuxt-content/nuxt-llms) | – | Generates /llms.txt automatically from Nuxt content. |
| Nuxt | [harlan-zw/nuxt-seo](https://github.com/harlan-zw/nuxt-seo) | – | Structured data, meta, sitemaps, robots, and AEO coverage for Nuxt. |
| VitePress | [okineadev/vitepress-plugin-llms](https://github.com/okineadev/vitepress-plugin-llms) | – | llms.txt plus per-page markdown for VitePress sites. |
| Astro Starlight | [delucis/starlight-llms-txt](https://github.com/delucis/starlight-llms-txt) | – | llms.txt for Starlight documentation sites. |
| Astro | [tfmurad/astro-llms-md](https://github.com/tfmurad/astro-llms-md) | 52 | llms.txt, llms-full.txt, and per-page markdown. |
| MkDocs | [pawamoy/mkdocs-llmstxt](https://github.com/pawamoy/mkdocs-llmstxt) | – | Emits /llms.txt during the MkDocs build. |
| MkDocs | [ultralytics/mkdocs](https://github.com/ultralytics/mkdocs) | 85 | SEO metadata, JSON-LD, social cards, and llms.txt. |
| Sphinx | [jdillard/sphinx-llms-txt](https://github.com/jdillard/sphinx-llms-txt) | – | llms.txt for Sphinx documentation projects. |
| WordPress | [WP-Autoplugin/llms-txt-for-wp](https://github.com/WP-Autoplugin/llms-txt-for-wp) | 49 | Customizable llms.txt for WordPress. |
| WordPress | [JonImmsWordpressDev/stratawp-seo](https://github.com/JonImmsWordpressDev/stratawp-seo) | 37 | SEO plugin with technical SEO and AI citation tracking. |
| WordPress | [AEO-God-Mode/aeo-god-mode](https://github.com/AEO-God-Mode/aeo-god-mode) | 19 | Schema, llms.txt, AI crawler controls, and citation tracking. |
| WordPress | [AEO-Content-Inc/aeo-content-ai-studio](https://github.com/AEO-Content-Inc/aeo-content-ai-studio) | 5 | Manages llms.txt, ai.txt, structured data, and semantic HTML. |
| WooCommerce | [madeburo/GEO-AI-Woo](https://github.com/madeburo/GEO-AI-Woo) | 30 | llms.txt, AI crawler rules, and AI metadata. |
| Shopify | [madeburo/GEO-AI-Shopify](https://github.com/madeburo/GEO-AI-Shopify) | 10 | llms.txt, AI crawler rules, and metadata for Shopify stores. |
| Magento 2 | [angeo-dev/module-llms-txt](https://github.com/angeo-dev/module-llms-txt) | 16 | llms.txt, llms-full.txt, and markdown page mirrors. |
| Laravel | [schaefersoft/laravel-llms-txt](https://github.com/schaefersoft/laravel-llms-txt) | 6 | llms.txt and llms-full.txt for Laravel apps. |
| Laravel | [GitHiteshZope/aigeo](https://github.com/GitHiteshZope/aigeo) | – | Surfaces products in AI-generated answers. |
| TYPO3 | [rtfirst/llms-txt](https://github.com/rtfirst/llms-txt) | 3 | llms.txt index files, with optional API key protection. |
| Joomla | [WebTolk/WT-LLMs](https://github.com/WebTolk/WT-LLMs) | 1 | llms.txt, llms-full.txt, and llms.json. |
 
### 1e. Agent-friendly serving (markdown twins & AI-only payloads)
 
| Repo | ⭐ | What it does |
|---|---|---|
| [nlweb-ai/NLWeb](https://github.com/nlweb-ai/NLWeb) | 6.3k | Reference implementation that adds natural-language interfaces to websites, serving people and AI agents (via MCP) from the same APIs. MIT. |
| [rubenmarcus/aeo.js](https://github.com/rubenmarcus/aeo.js) | 136 | AEO library that generates llms.txt, robots.txt, sitemap, and JSON-LD. |
| [dodopayments/dualmark](https://github.com/dodopayments/dualmark) | 108 | Serves a markdown version of each page to AI agents alongside HTML for humans, via content negotiation. |
| [agent-ecosystem/agent-docs-spec](https://github.com/agent-ecosystem/agent-docs-spec) | 59 | Specification for making documentation sites readable by AI coding agents. |
| [yazinsai/site-md](https://github.com/yazinsai/site-md) | 58 | Next.js middleware: clean markdown for agents and crawlers, HTML for humans. |
| [continuedev/next-geo](https://github.com/continuedev/next-geo) | 19 | Serves markdown instead of HTML to LLMs in Next.js App Router apps. |
| [frontier-infra/avl](https://github.com/frontier-infra/avl) | 16 | "Agent View Layer": text companions for AI agents, CMS plugins, and agent-ready discovery. |
| [aagedik/aigeoradar-aipm](https://github.com/aagedik/aigeoradar-aipm) | 12 | Open JSON spec for per-page metadata aimed at AI crawlers and RAG systems. |
| [SynSwarm/synswarm-protocol](https://github.com/SynSwarm/synswarm-protocol) | 3 | Edge middleware serving structured payloads to AI crawlers. |
| [JGinSJ/edge-ai-markdown](https://github.com/JGinSJ/edge-ai-markdown) | 1 | Akamai EdgeWorker serving token-efficient markdown to AI crawlers. |
| [prerex/prerex](https://github.com/prerex/prerex) | 1 | WordPress prerendering so search engines and AI crawlers see full content. |
 
### 1f. Machine-readability audits & linters
 
| Repo | ⭐ | What it does |
|---|---|---|
| [onvoyage-ai/gtm-engineer-skills](https://github.com/onvoyage-ai/gtm-engineer-skills) | 1.3k | Claude Code skill for raising AEO and GEO scores: 16 checks across 6 dimensions, with framework-specific fixes. |
| [Auriti-Labs/geo-optimizer-skill](https://github.com/Auriti-Labs/geo-optimizer-skill) | 1.1k | Audits robots.txt bot access, llms.txt depth, JSON-LD richness, brand entity coherence, and citability, then generates fixes. CLI, Python, MCP, Astro. |
| [jdevalk/specification.website](https://github.com/jdevalk/specification.website) | 878 | Platform-agnostic website spec covering HTML, accessibility, security, SEO, and agent readiness. |
| [jianruntech/geo-score](https://github.com/jianruntech/geo-score) | 411 | 0–100 readiness score on an open rubric, plus citation tracking with your own keys. CLI, GitHub Action, MCP. |
| [squirrelscan/squirrelscan](https://github.com/squirrelscan/squirrelscan) | 272 | Website QA tool with 300+ audit rules built for coding agents. |
| [Houseofmvps/claude-rank](https://github.com/Houseofmvps/claude-rank) | 147 | Explains why a site isn't cited by AI and fixes discoverability files; 170+ rules across 10 scanners. |
| [OranAi-Ltd/orangeo-ai-visibility-skill](https://github.com/OranAi-Ltd/orangeo-ai-visibility-skill) | 138 | Checks robots.txt, llms.txt, schema, citation signals, competitor gaps, and buyer prompts. |
| [spronta/crawlie](https://github.com/spronta/crawlie) | 111 | Fast, free technical SEO and GEO crawler for humans and agents. |
| [Cognitic-Labs/geoskills](https://github.com/Cognitic-Labs/geoskills) | 31 | Six agent skills to diagnose, fix, and monitor AI visibility. |
| [TheSmokeDev/geo-skills](https://github.com/TheSmokeDev/geo-skills) | 27 | 29 GEO agent skills plus a CLI for audits, citability, and crawler checks. |
| [fseixas/super-geo-agent-readiness](https://github.com/fseixas/super-geo-agent-readiness) | 26 | Agent-readiness skill exposing MCP, llms.txt, and OAuth to AI agents. |
| [glincker/geokit](https://github.com/glincker/geokit) | 17 | Lighthouse-style 0–100 AI-readiness audit. |
| [vinpatel/aeorank](https://github.com/vinpatel/aeorank) | 16 | 0–100 AI visibility score across 12 dimensions; generates AI-readable files. CLI and GitHub Action. |
| [techhorizonlabs/thl-open](https://github.com/techhorizonlabs/thl-open) | 16 | Turns a client site into an AI-readiness audit, ranked fix plan, and branded report. |
| [IliasSami/scrawly-seo-crawler](https://github.com/IliasSami/scrawly-seo-crawler) | 15 | Desktop crawler with 250+ technical SEO, GEO, and AI-search checks. |
| [SamurAIGPT/geo-checker](https://github.com/SamurAIGPT/geo-checker) | 15 | Next.js app auditing how likely landing pages are to be cited by AI search. |
| [angeo-dev/module-aeo-audit](https://github.com/angeo-dev/module-aeo-audit) | 11 | Magento 2 CLI scoring robots.txt, llms.txt, and schema signals, with fix commands and CI gating. |
| [sprawf/geoscore](https://github.com/sprawf/geoscore) | 11 | SEO and AI visibility audit built on Cloudflare Workers and D1. |
| [Saqierma/miaowageo](https://github.com/Saqierma/miaowageo) | 11 | Tests whether major AI chatbots can crawl, understand, and cite a site. |
| [metehan777/http-header-link-graph](https://github.com/metehan777/http-header-link-graph) | 9 | Publishes a site's link graph and heading map in HTTP headers so large sites can be crawled without parsing HTML. |
| [agencyenterprise/aiseo-audit](https://github.com/agencyenterprise/aiseo-audit) | 8 | CLI scoring how easily AI engines can ingest, understand, and reuse a URL's content. |
| [bemoshiur/OmniRank](https://github.com/bemoshiur/OmniRank) | 8 | In-repo auditor that maps findings to source files, shows fix diffs, and generates llms.txt. |
| [Canonry/aeo-audit](https://github.com/Canonry/aeo-audit) | 6 | Technical AEO audit library and CLI for agents. |
| [antlio/agentimization](https://github.com/antlio/agentimization) | 5 | Scores how easily Claude, ChatGPT, Perplexity, and Gemini can find, understand, and cite a site. |
| [seo-skills/geo-audit-skill](https://github.com/seo-skills/geo-audit-skill) | 5 | Deterministic GEO scores via Python CLI and Claude Code skills. |
| [wusmaiv/geo-audit](https://github.com/wusmaiv/geo-audit) | 5 | Python CLI auditing page visibility to AI Overviews, ChatGPT, Perplexity, and Claude. |
| [iliasabk/geolint](https://github.com/iliasabk/geolint) | 3 | ESLint-style auditor for AI crawler access, llms.txt, structured data, and citability. |
| [vasco-branco06/geo-check](https://github.com/vasco-branco06/geo-check) | 3 | Checks whether AI crawlers can reach and read a site, then scores it. |
| [seryvon-com/seryvon](https://github.com/seryvon-com/seryvon) | 3 | Self-hosted audit with transparent, deterministic scoring across SEO, GEO, AEO. |
| [caiopizzol/pagesight](https://github.com/caiopizzol/pagesight) | 2 | Shows your site the way search engines and AI systems see it. |
| [lireking/seo-geo-audit](https://github.com/lireking/seo-geo-audit) | 2 | Dependency-free crawler checking classic SEO and AI-crawler readiness. |
| [ryanportfolio/willaicite](https://github.com/ryanportfolio/willaicite) | 1 | Deterministic audit of whether AI answer engines can retrieve and quote a site. |
 
### 1g. Corporate entity mapping & structured data
 
| Repo | ⭐ | What it does |
|---|---|---|
| [schemaorg/schemaorg](https://github.com/schemaorg/schemaorg) | – | The Schema.org vocabulary itself — the source of truth for JSON-LD types. |
| [google/schema-dts](https://github.com/google/schema-dts) | – | TypeScript types for Schema.org, so invalid markup fails at build time. |
| [ookyet/web3-identity-seo](https://github.com/ookyet/web3-identity-seo) | 334 | Turns ENS identities into Google-recognized entities with Schema.org, verification, and indexing. |
| [jdevalk/seo-graph](https://github.com/jdevalk/seo-graph) | 50 | Builds connected Schema.org JSON-LD graphs for JavaScript sites, with an Astro integration. |
| [saadsalmankhan/entity-seo-skill](https://github.com/saadsalmankhan/entity-seo-skill) | 10 | Skill and playbook for ranking a person or brand for its own name, with JSON-LD and Search Console automation. |
| [terekhindc/open-entity-graph](https://github.com/terekhindc/open-entity-graph) | – | Public registry of Schema.org JSON-LD organization records, CC0, meant as a "source of truth" for AI models. |
| [josezuma/schema-for-ai](https://github.com/josezuma/schema-for-ai) | – | Annotated JSON-LD templates tuned for AI extraction. |
| [theseoriddler/google_knowledge_panel_mcp](https://github.com/theseoriddler/google_knowledge_panel_mcp) | 2 | MCP server for Knowledge Graph lookup, panel readiness audits, Wikidata mapping, and JSON-LD generation. |
| [aksanovdgtl-cmyk/brand-entity-check](https://github.com/aksanovdgtl-cmyk/brand-entity-check) | 1 | Checks 18 homepage entity signals, Organization schema, sameAs, and Wikidata presence. |
| [erwantanguy/geo-authority-suite-v1.2](https://github.com/erwantanguy/geo-authority-suite-v1.2) | 1 | WordPress plugin for schema.org entities, JSON-LD, and llms.txt. |
| [LucasFerrazSEO/entity-sameas-check](https://github.com/LucasFerrazSEO/entity-sameas-check) | 0 | Audits Organization and Person sameAs links for dead profiles, duplicates, and Wikidata consistency. |
| [agencekoeki/awesome-entity-seo](https://github.com/agencekoeki/awesome-entity-seo) | 2 | Practitioner reference for entity SEO and Knowledge Graph work. |
| [alexrodrigues43/Semantico-Entity-Engine](https://github.com/alexrodrigues43/Semantico-Entity-Engine) | 1 | Entity modeling, Wikidata reconciliation, knowledge graph views, and JSON-LD/RDF export. **Note:** code is public but marked "all rights reserved," so it isn't open source. |
 
---
 
## 2. Information Architecture & Content Synthesis
 
### 2a. Chunking, embeddings & retrieval simulation
 
| Repo | ⭐ | What it does |
|---|---|---|
| [tmolavi/sage-audit](https://github.com/tmolavi/sage-audit) | 1 | Splits content into 60–120 token passages, embeds them locally, simulates RAG retrieval, scores "Citation Survival Probability," and exports RAG-ready chunks plus llms.txt. The closest match to this category. |
| [tmolavi/mcp-geo-server](https://github.com/tmolavi/mcp-geo-server) | 3 | MCP server for GEO and RAG-readiness audits with JSON-LD support. |
| [DivitMittal/citestage](https://github.com/DivitMittal/citestage) | 4 | Local, reproducible generative-search simulator that diagnoses why AI engines don't cite a project. |
| [Hero777-tech/georankpy](https://github.com/Hero777-tech/georankpy) | – | Python GEO toolkit whose score includes "Chunk Retrievability" (RAG-readiness of each section). |
| [chonkie-ai/chonkie](https://github.com/chonkie-ai/chonkie) | – | *Borrowed from the RAG world:* lightweight token, sentence, and semantic chunking — handy for seeing how retrieval systems slice your pages. |
| [adbar/trafilatura](https://github.com/adbar/trafilatura) | – | *Borrowed:* extracts the main text from HTML the way indexing pipelines do — a quick check of what survives extraction. |
 
### 2b. Answer-first layouts & content linters
 
| Repo | ⭐ | What it does |
|---|---|---|
| [cucuwang/geoptimize](https://github.com/cucuwang/geoptimize) | 299 | Deterministic content-readiness linter for GEO on Next.js and static sites. |
| [deepakness/google-ai-search-optimization](https://github.com/deepakness/google-ai-search-optimization) | 133 | Agent skill based on Google's guidance for AI Overviews and AI Mode. |
| [IJONIS/geo-lint](https://github.com/IJONIS/geo-lint) | 40 | GEO content linter with 90+ rules and a suggested fix for each issue. |
| [zubair-trabzada/geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude) | – | Citability skill scores content 0–100 on how quotable it is for AI, with targeted rewrites. |
| [imsankz/SEOflow](https://github.com/imsankz/SEOflow) | – | GEO audit mode scores each post on answer-first openings, question headings, FAQ blocks, and list/table density. |
| [fritzhand/geo-landing-page](https://github.com/fritzhand/geo-landing-page) | 10 | Astro landing page template with JSON-LD, auto llms.txt, and FAQ microdata built in. |
| [goldk3y/agentblog](https://github.com/goldk3y/agentblog) | 10 | Next.js blog structured for AI search engines, with an agent writing layer. |
| [rakeshcheekatimala/answerlint](https://github.com/rakeshcheekatimala/answerlint) | 7 | Lighthouse-inspired CLI scoring content for AEO and GEO. |
| [Alpha-Park/genpark-generative-engine-optimization-and-citation-scorer-skill](https://github.com/Alpha-Park/genpark-generative-engine-optimization-and-citation-scorer-skill) | 7 | Scores content for citation visibility, factual definitions, and structured metrics. |
| [paultaki/get-cited-by-ai](https://github.com/paultaki/get-cited-by-ai) | 3 | Claude Code skill with writing rules drawn from 26,767 measured AI citations. |
 
### 2c. Content creation, rewriting & publishing
 
| Repo | ⭐ | What it does |
|---|---|---|
| [yaojingang/GEOFlow](https://github.com/yaojingang/GEOFlow) | 3.8k | GEO content and multi-site publishing platform with AI quality checks. |
| [gbessoni/seobuild-onpage](https://github.com/gbessoni/seobuild-onpage) | 251 | AI agent that writes pages built to rank in Google and be cited by LLMs. |
| [geo-team-red/geo-optimizer](https://github.com/geo-team-red/geo-optimizer) | 202 | Pluggable GEO framework in Go with built-in and custom strategies. |
| [mverab/eGEOagents](https://github.com/mverab/eGEOagents) | 199 | Rewrites site content for ChatGPT, Perplexity, AI Overviews, Claude, and Gemini; batch and competitor modes. |
| [chnjames/AIGEOTOOLS](https://github.com/chnjames/AIGEOTOOLS) | 173 | Content platform for getting brands cited in AI answers, with keyword strategy and analytics (Chinese). |
| [yaojingang/GEOHub](https://github.com/yaojingang/GEOHub) | 164 | GEO and SEO agent skills covering discovery, diagnosis, content, and measurement. |
| [HeiGeAi/HeiGe-GEO-SEO](https://github.com/HeiGeAi/HeiGe-GEO-SEO) | 67 | China-focused GEO content system for AI assistants. MIT. |
| [shadowresearch/auto-geo](https://github.com/shadowresearch/auto-geo) | 26 | GEO engine aimed at getting brands mentioned in major AI chatbots. |
| [CDragon123-code/geo-copilot](https://github.com/CDragon123-code/geo-copilot) | 20 | Chrome extension that captures LLM answers, finds patterns, and drafts articles. |
 
### 2d. Research code & benchmarks
 
| Repo | ⭐ | What it does |
|---|---|---|
| [GEO-optim/GEO](https://github.com/GEO-optim/GEO) | 339 | Official code for the original GEO paper (Aggarwal et al.), plus the GEO-Bench dataset. |
| [cxcscmu/AutoGEO](https://github.com/cxcscmu/AutoGEO) | 224 | ICLR 2026: learns generative-engine preferences and rewrites content to match. |
| [Wu-beining/generative-engine-optimization-research-hub](https://github.com/Wu-beining/generative-engine-optimization-research-hub) | 71 | Running bibliography of GEO, AEO, and AIO papers with code links. |
| [AIcling/agentic_geo](https://github.com/AIcling/agentic_geo) | 38 | AgenticGEO: self-evolving strategy archive for visibility in black-box generative search. |
| [Generative-Engine-Marketing/GEM-Bench](https://github.com/Generative-Engine-Marketing/GEM-Bench) | 19 | Benchmark for generative engine marketing (ad-injected AI responses). |
| [QianfengWen/SafeGEO](https://github.com/QianfengWen/SafeGEO) | 5 | EMNLP 2026 benchmark of GEO attacks on LLM recommendation agents, with mitigations. |
| [tmolavi/geo-scope](https://github.com/tmolavi/geo-scope) | 4 | Framework for reproducible, multi-model AI visibility benchmarks. |
| [parameterlab/c-seo-bench](https://github.com/parameterlab/c-seo-bench) | – | C-SEO Bench (NeurIPS 2025 Datasets & Benchmarks). |
| [Wu-beining/MAGEO](https://github.com/Wu-beining/MAGEO) | – | MAGEO (ACL Findings 2026). |
| [qychen2001/CC-GSEO-Bench](https://github.com/qychen2001/CC-GSEO-Bench) | – | CC-GSEO-Bench benchmark. |
| [psbagga17/E-GEO](https://github.com/psbagga17/E-GEO) | – | E-GEO research code. |
| [899ms/geo-citation-lab](https://github.com/899ms/geo-citation-lab) | 0 | Dataset and pipeline for studying how AI search engines pick citations. MIT / CC BY 4.0. |
 
---
 
## 3. Trackers & Visibility Mentions
 
### 3a. Self-hosted tracking platforms
 
| Repo | ⭐ | What it does |
|---|---|---|
| [yaojingang/GEORank](https://github.com/yaojingang/GEORank) | 496 | Self-hostable GEO ranking workbench (Next.js + FastAPI) that turns diagnoses into prompts and action plans. |
| [ai-search-guru/getcito](https://github.com/ai-search-guru/getcito-worlds-first-open-source-aio-aeo-or-geo-tool) | 485 | AI search optimization and visibility tracking tool. |
| [elmohq/elmo](https://github.com/elmohq/elmo) | 441 | Tracks mentions and citations across ChatGPT, Claude, Perplexity, Gemini, Copilot, Grok, and AI Overviews. MIT. |
| [Albert-Weasker/niubigeo](https://github.com/Albert-Weasker/niubigeo) | – (305 forks) | Start from a domain to see how models describe you, which competitors they name, and which sources they cite; keeps raw answers as evidence. Apache 2.0. |
| [usenotra/notra](https://github.com/usenotra/notra) | 265 | Asks AI assistants buyer questions to show your visibility, competitors, and fixes. |
| [oneglanse/oneglanse](https://github.com/oneglanse/oneglanse) | 214 | Tracks mentions and citations through the real product interfaces of major AI tools. MIT. |
| [limelit-co/open](https://github.com/limelit-co/open) | 190 | One Go binary with SQLite, MCP-first, bring your own keys. |
| [Canonry/canonry](https://github.com/Canonry/canonry) | 168 | Agent-first AEO/GEO operating platform with CLI, SQLite, and MCP. |
| [ansvisor/ansvisor](https://github.com/ansvisor/ansvisor) | 122 | Visibility, citations, prompts, and competitors across eight engines, including Google AI Mode. |
| [databluedev/searchmirror](https://github.com/databluedev/searchmirror) | 111 | Self-hosted rank tracker plus AI visibility monitor. AGPL-3.0. |
| [alexpospekhov/searchstack-aeo](https://github.com/alexpospekhov/searchstack-aeo) | 103 | Monitor AI and search visibility from one CLI, aimed at small teams. |
| [AI2HU/gego](https://github.com/AI2HU/gego) | 91 | Schedules prompts across LLMs, records web-search citations, tracks brand mentions. Go, GPL-3.0. |
| [letterstory/lettertrace](https://github.com/letterstory/lettertrace) | – | Bring-your-own-key tracker with 95% confidence ranges on mention rates (Wilson score). MIT. |
| [geostorm-ai/geostorm](https://github.com/geostorm-ai/geostorm) | 33 | Monitors how AI systems perceive and recommend your software. |
| [anyin-ai/aperture](https://github.com/anyin-ai/aperture) | 27 | Self-hosted, BYOK alternative to Profound and Peec AI. |
| [hellowalt/aeo-radar](https://github.com/hellowalt/aeo-radar) | 26 | AEO monitor for ChatGPT and other answer engines. |
| [aicw-io/aicw-ai-mentions](https://github.com/aicw-io/aicw-ai-mentions) | 25 | Tracks how often products are mentioned in popular AI chatbots. |
| [moaljumaa/habibi](https://github.com/moaljumaa/habibi) | 24 | Self-hosted AI visibility and citation tracker. |
| [IamRamgarhia/All-In-One-Free-SEO-Tool](https://github.com/IamRamgarhia/All-In-One-Free-SEO-Tool) | 24 | 99-tool SEO suite including AI search visibility. MIT. |
| [craftsail/craftsail-growth](https://github.com/craftsail/craftsail-growth) | 16 | GEO dashboard: AI mentions, share of voice, and AI crawler access. |
| [Citatra/Citatra](https://github.com/Citatra/Citatra) | 16 | AEO/GEO platform for competitor monitoring and AI search visibility. |
| [codextde/autoseo](https://github.com/codextde/autoseo) | 13 | AI SEO and GEO platform tracking mentions alongside classic SEO tools. |
| [jonradoff/llmopt](https://github.com/jonradoff/llmopt) | 10 | Analyzes how LLMs and AI search engines cite brands. |
| [sharozdawa/ai-visibility](https://github.com/sharozdawa/ai-visibility) | 10 | Alternative to Otterly/AthenaHQ across ChatGPT, Perplexity, Claude, Gemini. |
| [Manavarya09/citelens](https://github.com/Manavarya09/citelens) | 9 | Tracks Google rankings and AI citations versus competitors. |
| [compiuta-origin/sonde-analytics](https://github.com/compiuta-origin/sonde-analytics) | 8 | Self-hosted analytics on how your brand shows up in LLM answers. |
| [dipakkr/ai-seo-platform](https://github.com/dipakkr/ai-seo-platform) | 4 | Tracks brand visibility across ChatGPT, Perplexity, Gemini, and Claude. |
| [melonwer/hearsay](https://github.com/melonwer/hearsay) | 3 | Self-hosted tracker of how major chatbots discuss your brand, with MCP. |
| [EdgeForgeLab/OpenCiteX](https://github.com/EdgeForgeLab/OpenCiteX) | 3 | GEO radar for visibility and citation rates across AI engines. |
| [rastmob/ai-visibility-tracker](https://github.com/rastmob/ai-visibility-tracker) | 3 | Tracks visibility across ChatGPT, Gemini, Perplexity, Claude, and Google AI. |
| [ankit373/citegeo](https://github.com/ankit373/citegeo) | 1 | Asks AI models buyer questions and stores every raw answer as evidence. |
 
### 3b. CLI, MCP & agent-skill trackers
 
| Repo | ⭐ | What it does |
|---|---|---|
| [onism1767-creator/potato](https://github.com/onism1767-creator/potato) | 199 | Measures how often a brand is mentioned and cited in Claude's web-search answers; runs locally. |
| [AKzar1el/mcp-geo](https://github.com/AKzar1el/mcp-geo) | 46 | Tracks citations across seven AI search surfaces. |
| [khadinakbarlabs/ai-brand-monitor-mcp](https://github.com/khadinakbarlabs/ai-brand-monitor-mcp) | 38 | MCP tool for mentions, share of voice, citations, and competitors. |
| [FayAndXan/xanlens](https://github.com/FayAndXan/xanlens) | 33 | Asks seven AI engines whether they recognize your brand. |
| [gooseworks-ai/goose-aeo](https://github.com/gooseworks-ai/goose-aeo) | 33 | AEO tracking CLI and dashboard driven by coding agents. |
| [Pupok462/open-geo](https://github.com/Pupok462/open-geo) | 27 | Reads the answer a logged-in user sees by running an agent in a real browser. |
| [followanton/sleepwalker](https://github.com/followanton/sleepwalker) | 25 | AI visibility data (prompts, answers, citations) via MCP, API, CLI, or app. |
| [WorkSmartAI-alt/ai-visibility-monitor](https://github.com/WorkSmartAI-alt/ai-visibility-monitor) | 21 | Finds winnable buyer queries, competitor citation gaps, and content to publish next. |
| [webappski/aeo-platform](https://github.com/webappski/aeo-platform) | 13 | Measures brand presence, audits AI-bot crawlability, exports a brand context for a 30-step plan. |
| [petar-nauka/ai-visibility-skill](https://github.com/petar-nauka/ai-visibility-skill) | 9 | Checks whether AI assistants recommend your brand and suggests fixes. |
| [Rankfor/rankfor-open](https://github.com/Rankfor/rankfor-open) | 8 | Measures brand stability and detects LLM hallucinations about your brand. |
| [Het161/CiteMind](https://github.com/Het161/CiteMind) | 6 | Tracks AI citations and learns which fixes restore lost citations. |
| [optifeed/optifeed-radar](https://github.com/optifeed/optifeed-radar) | 5 | CLI and MCP server checking whether AI assistants recommend your brand. |
| [DivitMittal/answerci](https://github.com/DivitMittal/answerci) | 4 | CI-native LLM visibility monitoring for open-source projects and technical brands. |
| [Devansh-365/cited](https://github.com/Devansh-365/cited) | 4 | One-minute check of whether ChatGPT, Perplexity, and Google AI recommend you. |
| [pixelstrunk/ai-visibility-checker](https://github.com/pixelstrunk/ai-visibility-checker) | 4 | Checks if ChatGPT, Gemini, or Google AI Mode names your brand. |
| [studiomeyer-io/studiomeyer-geo](https://github.com/studiomeyer-io/studiomeyer-geo) | 3 | MCP server with 30 tools across eight LLM platforms. |
| [WannabDad/aeo-brand-scan](https://github.com/WannabDad/aeo-brand-scan) | 3 | Scores how AI search describes your brand versus competitors. |
| [cloro-dev/geo-tracker](https://github.com/cloro-dev/geo-tracker) | 2 | Schedules prompts across engines and stores answers in your own Postgres. |
| [humanswith-ai/ai-visibility-probe-lite](https://github.com/humanswith-ai/ai-visibility-probe-lite) | 2 | Dependency-free probe of mention and citation share across ChatGPT, Perplexity, Gemini. |
| [josezuma/geo-watch](https://github.com/josezuma/geo-watch) | – | CLI that monitors brand citations in AI model outputs. |
 
### 3c. Niche trackers (ecommerce, local, datasets)
 
| Repo | ⭐ | What it does |
|---|---|---|
| [local-falcon/mcp](https://github.com/local-falcon/mcp) | 24 | Local SEO and AI visibility: geo-grid rank tracking and competitor analysis. |
| [syntropicsignal-ai/ai-visibility-audit](https://github.com/syntropicsignal-ai/ai-visibility-audit) | 6 | Ecommerce: does ChatGPT, Gemini, or Google AI recommend your store or a competitor? PDF report. |
| [angeo-dev/module-aeo-brand-visibility](https://github.com/angeo-dev/module-aeo-brand-visibility) | 5 | Magento 2 module scoring AI brand visibility, with dashboard and CI gate. |
| [trakkr-aisearch/ai-500](https://github.com/trakkr-aisearch/ai-500) | 5 | Monthly public snapshots of global AI visibility rankings as a dataset. |
| [MohammadThabetHassan/facts-only](https://github.com/MohammadThabetHassan/facts-only) | 5 | Browser extension flagging paid or planted sources in AI chatbot answers. |
| [MentionNetwork/ecommerce-ai-visibility-engine](https://github.com/MentionNetwork/ecommerce-ai-visibility-engine) | 3 | Shows how AI sells your products versus the retailers it recommends. |
| [moreyiyi04-design/geo-monitor-audit](https://github.com/moreyiyi04-design/geo-monitor-audit) | 3 | Comparison of Chinese GEO monitoring tools: free tiers, engines covered, disclosure gaps. |
 
---
 
## Bonus: All-in-one suites & skill packs (span all three categories)
 
| Repo | ⭐ | What it does |
|---|---|---|
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 54.5k | Marketing skills for Claude Code and AI agents, including SEO and analytics. |
| [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | 14.9k | SEO skill for Claude Code with 25 sub-skills, including schema and GEO/AEO. |
| [Ryze-AI-Adgent/open-seo-mcp-skills](https://github.com/Ryze-AI-Adgent/open-seo-mcp-skills) | 5.2k | Free SEO MCP server plus SEO/GEO skills, including AI visibility. |
| [aaron-he-zhu/aaron-marketing-skills](https://github.com/aaron-he-zhu/aaron-marketing-skills) | 2.9k | 120 marketing skills across seven disciplines, including SEO/GEO. |
| [indranilbanerjee/digital-marketing-pro](https://github.com/indranilbanerjee/digital-marketing-pro) | 833 | AI marketing system spanning SEO, AEO/GEO, content, and analytics. |
| [AgriciDaniel/codex-seo](https://github.com/AgriciDaniel/codex-seo) | 809 | Codex-first SEO suite: 26 workflows, GEO/AEO, schema. |
| [aigclink/geolook](https://github.com/aigclink/geolook) | 770 | End-to-end GEO: analysis, diagnosis, strategy, tickets, execution, verification. |
| [leopard627/fire-your-seo-agency](https://github.com/leopard627/fire-your-seo-agency) | 730 | Claude Code skill for SEO, AEO, GEO, LLMO, and Naver search. |
| [unifapi-agent/agents](https://github.com/unifapi-agent/agents) | 530 | Marketing agents over MCP: SEO audits, GEO/AI visibility, competitive intel. |
| [ViryaZheng/recomby-geo](https://github.com/ViryaZheng/recomby-geo) | 459 | GEO "AI employee" stack: skills package plus curated agents and CLIs. MIT. |
| [alirezarezvani/claude-code-aso-skill](https://github.com/alirezarezvani/claude-code-aso-skill) | 440 | AEO automation framework for Claude Code with sub-agents. |
| [beyondtahir/beyondseo](https://github.com/beyondtahir/beyondseo) | 171 | Python SEO platform covering crawling, SEO/AEO/GEO, and competitors. |
| [seranking/seo-skills](https://github.com/seranking/seo-skills) | 160 | Claude skills for the SE Ranking MCP server, including AI search share of voice. |
| [Infrasity-Labs/dev-gtm-claude-skills](https://github.com/Infrasity-Labs/dev-gtm-claude-skills) | 139 | GEO and AI-discoverability skills for developer-focused companies. |
| [AkashPriyadarshii/jev-seo](https://github.com/AkashPriyadarshii/jev-seo) | 96 | Rust SEO/GEO toolkit: audits, crawls, AI citation checks, MCP server. |
| [akii-technologies-ltd/akii-seo-ai-search-optimizer](https://github.com/akii-technologies-ltd/akii-seo-ai-search-optimizer) | 76 | Claude Code plugin: audits, schema generation, AI visibility tracking. |
| [Hainrixz/claude-seo-ai](https://github.com/Hainrixz/claude-seo-ai) | 71 | Two-score audit (search + AI) with an opt-in fixer. |
 
## Bonus: Curated lists, guides & playbooks
 
| Repo | ⭐ | Focus |
|---|---|---|
| [amplifying-ai/awesome-generative-engine-optimization](https://github.com/amplifying-ai/awesome-generative-engine-optimization) | 523 | Guides, tools, and research. |
| [luka2chat/awesome-geo](https://github.com/luka2chat/awesome-geo) | 130 | General GEO resources. |
| [izak-fisher/generative-engine-optimization-tools](https://github.com/izak-fisher/generative-engine-optimization-tools) | 117 | GEO tools list. |
| [discoveredlabs/awesome-aeo-seo](https://github.com/discoveredlabs/awesome-aeo-seo) | 114 | AEO and SEO resources for engineers and growth teams. |
| [AgriciDaniel/flow](https://github.com/AgriciDaniel/flow) | 90 | Evidence-led SEO playbook for AI search, with sourced statistics. |
| [RankSpotAI/awesome-geo-tools](https://github.com/RankSpotAI/awesome-geo-tools) | 79 | Tools compared by engines tracked, refresh rate, cost, and data export. |
| [TraceCohenTech/ai-seo-playbook](https://github.com/TraceCohenTech/ai-seo-playbook) | 71 | SEO and GEO/AEO playbook with tested scripts and measurement method. |
| [LLM-X-Factorer/awesome-geo-cn](https://github.com/LLM-X-Factorer/awesome-geo-cn) | 42 | Chinese-language GEO resources for domestic AI search platforms. |
| [alternbits/awesome-ai-visibility](https://github.com/alternbits/awesome-ai-visibility) | 29 | AI visibility marketing tools. |
| [cloudapp-dev/awesome-open-geo](https://github.com/cloudapp-dev/awesome-open-geo) | 5 | Only free, self-hostable GEO tools — a great companion to this list. |
| [JingHao-Leon/geo-book](https://github.com/JingHao-Leon/geo-book) | 5 | Chinese GEO handbook from hands-on testing across six domestic AI engines. |
| [elmohq/awesome-answer-engine-optimization](https://github.com/elmohq/awesome-answer-engine-optimization) | 4 | AEO/GEO docs, crawler user agents, specs, research. |
| [josezuma/awesome-ai-visibility](https://github.com/josezuma/awesome-ai-visibility) | 3 | AI visibility, GEO, and AEO resources. |
| [DavidHuji/Awesome-GEO](https://github.com/DavidHuji/Awesome-GEO) | – | Research-paper focused GEO list. |
