# Technical GEO Audit Toolkit

Open-source tools for running technical GEO audits on websites. Every tool here:

- has an open-source license,
- runs on your own machine or server (no hosted service needed for the audit part),
- checks either **information retrieval** (can AI crawlers reach and read the site?) or **information architecture** (is the content structured, chunked and extractable so AI can understand and quote it?), or both.

Checked against each repository (README, files, license, last update) on October 14, 2026. The label after each link tells you how it runs: **Python tool** installs with `uv tool install`, **Node tool** runs with `npx` (needs Node.js), **self-hosted app** is a dashboard you start on your server and open in a browser.

## 1. All-in-one technical GEO audits

Point them at a URL; they check AI crawler access, rendering, llms.txt, structured data and how quotable the content is.

- [Auriti-Labs/geo-optimizer-skill](https://github.com/Auriti-Labs/geo-optimizer-skill) (Python tool): Scores a site 0–100 across 9 categories and 27 AI crawlers, then generates the fixes (robots.txt, llms.txt, schema). Can also audit a whole sitemap.
- [jianruntech/geo-score](https://github.com/jianruntech/geo-score) (Python tool): 0–100 readiness score on an open, versioned rubric. One file with no dependencies.
- [rubenmarcus/aeo.js](https://github.com/rubenmarcus/aeo.js) (Node tool): `npx aeo.js check yoursite.com` gives a 0–100 score, an access table for 23 AI crawlers, average content citability and the top fixes.
- [Houseofmvps/claude-rank](https://github.com/Houseofmvps/claude-rank) (Node tool): 10 scanners and 170+ checks on a live URL (up to 50 pages) or a local project folder, with separate GEO and AEO audits.
- [Canonry/aeo-audit](https://github.com/Canonry/aeo-audit) (Node tool): Scores a URL or a whole sitemap across 16 factors (structured data, llms.txt, E-E-A-T, extractability, snippet eligibility) and ranks the fixes. Can also audit a built site offline.
- [iliasabk/geolint](https://github.com/iliasabk/geolint) (Node tool): Checks 51 AI crawler names against robots.txt and runs 52 rules (llms.txt, structured data, citability), with a concrete fix for each finding.
- [antlio/agentimization](https://github.com/antlio/agentimization) (Node tool): 36 checks in 8 categories: llms.txt, markdown versions, heading structure, server vs client rendering, redirects, canonicals and access gates.
- [ryanportfolio/willaicite](https://github.com/ryanportfolio/willaicite) (Node tool): 0–100 score over nine dimensions. Fetches each page twice, as a browser and as an AI crawler, to catch blocks robots.txt doesn't show, and checks for a quotable answer near the top.
- [vinpatel/aeorank](https://github.com/vinpatel/aeorank) (Node tool): Scores crawler access and how easily AI can extract your content (12 dimensions), then writes 8 fix files.
- [glincker/geokit](https://github.com/glincker/geokit) (Node tool): Lighthouse-style 0–100 AI-readiness audit, plus generators for llms.txt, JSON-LD, robots.txt and sitemap. Last updated February 2026.
- [wusmaiv/geo-audit](https://github.com/wusmaiv/geo-audit) (Python tool): One URL in, scored report out: AI crawler rules, llms.txt, JSON-LD and passage citability. No API key.
- [seo-skills/geo-audit-skill](https://github.com/seo-skills/geo-audit-skill) (Python tool): SEOmator's audit: which AI crawlers get in, whether passages can be quoted as-is, authorship and date markup, llms.txt and feeds. Every number is reproducible.
- [TheSmokeDev/geo-skills](https://github.com/TheSmokeDev/geo-skills) (Python tool): `geoskills inspect` crawls a site read-only and scores citability, technical setup and more (0–100). Also ships agent skills.
- [vasco-branco06/geo-check](https://github.com/vasco-branco06/geo-check) (Python tool): Checks whether AI crawlers can reach and read a site, with two separate scores so blocking AI training doesn't cost points while blocking AI search does.
- [OranAi-Ltd/orangeo-ai-visibility-skill](https://github.com/OranAi-Ltd/orangeo-ai-visibility-skill) (Python script): No-dependency readiness check: AI crawler access, llms.txt, sitemap, meta tags, schema and proof pages. Run `scripts/check_ai_readiness.py` directly.
- [bemoshiur/OmniRank](https://github.com/bemoshiur/OmniRank) (Python tool): Scores a page's live HTML for SEO, answer-engine and GEO rules (for example a 40–60 word answer block near the top), then generates llms.txt and a facts.json file.
- [AkashPriyadarshii/jev-seo](https://github.com/AkashPriyadarshii/jev-seo) (Rust tool): SEO and GEO command-line suite: AI crawler checks in robots.txt, JSON-LD validation, file audits and content briefs.
- [Saqierma/miaowageo](https://github.com/Saqierma/miaowageo) (Node app): 28 technical checks with evidence, including firewall and CDN rules that silently block AI bots. README mostly in Chinese.
- [seryvon-com/seryvon](https://github.com/seryvon-com/seryvon) (Self-hosted app): Repeatable audit across SEO, GEO, Google AI Overviews, answer engines and AI agents. Anything it can't measure is marked "not measured", never guessed.

## 2. Whole-site crawlers with AI-search checks

For crawling every page of a site, not just one URL.

- [IliasSami/scrawly-seo-crawler](https://github.com/IliasSami/scrawly-seo-crawler) (Desktop app): 250 technical SEO, GEO and AI-agent checks on every page, with plain-language fixes. A free alternative to Screaming Frog.
- [spronta/crawlie](https://github.com/spronta/crawlie) (Node tool): Fast crawler for broken links, redirects, missing metadata and 40+ SEO and AI-search checks.
- [squirrelscan/squirrelscan](https://github.com/squirrelscan/squirrelscan) (CLI program): 300+ rules in 22 categories, including "agent experience" checks for how well AI agents can use a site.
- [lireking/seo-geo-audit](https://github.com/lireking/seo-geo-audit) (Node scripts): Crawler that finds content AI crawlers can't see because it only appears after JavaScript runs. No dependencies.

## 3. Content structure, extractability & chunking

Information architecture: is the content split, structured and written so AI retrieval systems can find and quote it?

- [tmolavi/sage-audit](https://github.com/tmolavi/sage-audit) (Python tool): Splits content into 60–120 token passages, embeds them locally, simulates AI retrieval and scores how likely each passage is to survive it. Also checks entity markup and exports RAG-ready chunks. Works on a URL or raw HTML.
- [agencyenterprise/aiseo-audit](https://github.com/agencyenterprise/aiseo-audit) (Node tool): Reads a page the way an AI engine would: does it name its subject consistently, answer directly and back claims with sources? Labels each factor by how strong the research behind it is.
- [cucuwang/geoptimize](https://github.com/cucuwang/geoptimize) (Node tool): Repeatable content lint for document structure and sourced claims, on a URL or a built site folder.
- [rakeshcheekatimala/answerlint](https://github.com/rakeshcheekatimala/answerlint) (Node tool): Audits content for whether AI answer engines can understand, trust and cite it, and what to improve.
- [IJONIS/geo-lint](https://github.com/IJONIS/geo-lint) (Node tool): Linter with 90+ SEO and GEO rules for Markdown/MDX source files (not live URLs), with a suggested fix for each issue. Last updated March 2026.
- [DivitMittal/citestage](https://github.com/DivitMittal/citestage) (Rust tool): Simulates an answer engine step by step (crawl, parse, index, retrieve, rerank, cite) to show where your content loses to competitors. Developer setup needed.

## 4. AI crawler log analysis

Are AI bots actually crawling the site, and which pages?

- [stani-chirk/logwick](https://github.com/stani-chirk/logwick) (Node app): Reads server or CDN logs and separates real users, search crawlers, AI training scrapers and AI assistants fetching pages live. Local dashboard; data stays on your machine.
- [abbottis/logwerk](https://github.com/abbottis/logwerk) (Browser app): Drop an Nginx or Apache log into a local web page to see which of 70+ crawlers visited, by company and purpose (for example ChatGPT search vs training). Nothing is uploaded.

## 5. Structured data & entities

- [LucasFerrazSEO/entity-sameas-check](https://github.com/LucasFerrazSEO/entity-sameas-check) (Python tool): Checks the sameAs links in Organization and Person JSON-LD for dead profiles, duplicates and consistency with Wikidata. Reports are in Brazilian Portuguese.

## 6. Tracking platforms with a built-in technical audit

Mainly for checking whether AI engines mention you, but each includes a technical audit you can run on its own.

- [aigclink/geolook](https://github.com/aigclink/geolook) (Self-hosted app): Site audit built as a chain of four layers (access → orientation → understanding → quotability), then fix tickets with acceptance criteria and before/after checks.
- [optifeed/optifeed-radar](https://github.com/optifeed/optifeed-radar) (Node tool): `npx optifeed-radar audit yourbrand.com` scores AI-crawler access, llms.txt, schema, meta tags and sitemap with no API keys.
- [webappski/aeo-platform](https://github.com/webappski/aeo-platform) (Node tool): Audits AI-bot crawlability and authority signals alongside brand measurement.
- [shadowresearch/auto-geo](https://github.com/shadowresearch/auto-geo) (Node tool): `auto-geo doctor` audits any page for citation readiness. File-based, no server or account.
