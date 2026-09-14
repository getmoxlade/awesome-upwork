# Awesome Upwork [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, APIs, data sources and resources for working with [Upwork](https://www.upwork.com) — for freelancers, agencies, recruiters, and developers building on Upwork data.

Not affiliated with, endorsed by, or sponsored by Upwork Inc. Upwork is a trademark of Upwork Inc. Entries are listed for usefulness, not endorsement; check each tool's terms before use.

## Contents

- [Official API & SDKs](#official-api--sdks)
- [MCP Servers](#mcp-servers)
- [Job Data & Scrapers](#job-data--scrapers)
- [Freelancer & Talent Data](#freelancer--talent-data)
- [Client & Market Intelligence](#client--market-intelligence)
- [Open-Source Scrapers & Job Feeds](#open-source-scrapers--job-feeds)
- [Proposal & Bidding Tools](#proposal--bidding-tools)
- [Job Aggregators](#job-aggregators)
- [Desktop & Time Tracker Utilities](#desktop--time-tracker-utilities)
- [Guides & Playbooks](#guides--playbooks)
- [Communities & Status](#communities--status)

## Official API & SDKs

Upwork's own GraphQL API and the official client libraries. The API is keyed and reviewed per application.

- [Upwork API Documentation](https://www.upwork.com/developer/documentation/graphql/api/docs/index.html) - The official GraphQL API reference: jobs, contracts, messages, reports.
- [Upwork Developers Portal](https://www.upwork.com/developer/) - Register an application, request API access, manage keys.
- [python-upwork](https://github.com/upwork/python-upwork) - Official Python bindings for the Upwork API.
- [python-upwork-oauth2](https://github.com/upwork/python-upwork-oauth2) - Official Python bindings, OAuth2 flow.
- [node-upwork](https://github.com/upwork/node-upwork) - Official Node.js bindings for the Upwork API.
- [node-upwork-oauth2](https://github.com/upwork/node-upwork-oauth2) - Official Node.js bindings, OAuth2 flow.
- [php-upwork](https://github.com/upwork/php-upwork) - Official PHP bindings for the Upwork API.
- [php-upwork-oauth2](https://github.com/upwork/php-upwork-oauth2) - Official PHP bindings, OAuth2 flow.
- [ruby-upwork](https://github.com/upwork/ruby-upwork) - Official Ruby bindings for the Upwork API.
- [golang-upwork](https://github.com/upwork/golang-upwork) - Official Go bindings for the Upwork API.
- [golang-upwork-oauth2](https://github.com/upwork/golang-upwork-oauth2) - Official Go bindings, OAuth2 flow.
- [java-upwork](https://github.com/upwork/java-upwork) - Official Java bindings for the Upwork API.
- [java-upwork-oauth2](https://github.com/upwork/java-upwork-oauth2) - Official Java bindings, OAuth2 flow.
- [tap-upwork](https://github.com/Automattic/tap-upwork) - Singer tap for extracting data from the Upwork GraphQL API, by Automattic.
- [powerbi-upwork](https://github.com/ranmax123/powerbi-upwork) - Power BI custom connector for the Upwork API.

## MCP Servers

Model Context Protocol endpoints that let AI agents work with Upwork data and workflows.

- [upwork-mcp](https://github.com/vanooo/upwork-mcp) - MCP server for Upwork via browser automation: search jobs, manage proposals, messages and contracts from Claude Code.
- [upwork-mcp-server](https://github.com/AbbottDevelopments/upwork-mcp-server) - Open-source MCP server over Upwork's GraphQL API: search jobs, manage contracts, send messages.
- [realitech upwork-mcp](https://lobehub.com/mcp/realitechteam-upwork-mcp) - MCP server exposing the Upwork GraphQL API as agent tools; session persisted after one interactive login.
- [@chinchillaenterprises/mcp-upwork](https://www.npmjs.com/package/@chinchillaenterprises/mcp-upwork) - Upwork MCP server with GraphQL API, proposal webhooks and external token management.
- [Moxlade — Upwork Buyer Intelligence](https://buyer.moxlade.com/?ref=awesome-upwork) - MCP endpoint over a proprietary Upwork corpus: who the anonymous client behind a posting really is, what they have actually paid, and the market rate for a skill. Answers only; the corpus never leaves.
- [Upwork MCP — SaaS Ideas](https://apify.com/epicscrapers/upwork-scraper-mcp) - Mines Upwork postings for SaaS product ideas, exposed over MCP.

## Job Data & Scrapers

Hosted actors that return Upwork job postings as structured rows. Most are pay-per-result; check pricing on each listing.

- [Upwork Job Scraper](https://apify.com/neatrat/upwork-job-scraper) - The most-used Upwork job scraper on Apify; search filters, structured job output.
- [Upwork Job Extractor](https://apify.com/flash_mage/upwork) - Job extraction with search-term and category filters.
- [Upwork Scraper — Freelance Jobs](https://apify.com/blackfalcondata/upwork-scraper) - Jobs with client details, budget and skill filters.
- [Upwork Jobs Scraper](https://apify.com/devcake/upwork-jobs-scraper) - Job listings with client history and proposal counts.
- [Upwork Job Scraper (subscription)](https://apify.com/deltaspider/upwork-job-scraper) - Monthly-rental job scraper with scheduled extraction.
- [Upwork Job Finder](https://apify.com/nahom.network/upwork-job-finder) - Job listings by keyword and category.
- [Upwork Jobs Scraper](https://apify.com/gio21/upwork-jobs-scraper) - Per-job pricing, search-URL driven.
- [Upwork Jobs Bulk Scraper](https://apify.com/hello.datawizards/upwork-jobs) - Bulk job extraction.
- [Upwork Jobs Scraper](https://apify.com/easyapi/upwork-jobs-scraper) - Job listings with filtering.
- [Upwork Jobs Scraper](https://apify.com/orgupdate/upwork-jobs-scraper) - Jobs with client and budget fields; has an open-source companion repo.
- [Upwork Search Jobs](https://apify.com/memo23/upwork-jobs-scraper) - Detailed job extraction from search pages.
- [Upwork Jobs 130K+](https://apify.com/memo23/upwork-jobs-scraper-ppe) - Large pre-indexed job dataset at low per-row cost.
- [Upwork Jobs & Freelancers](https://apify.com/sian.agency/upwork-jobs-scraper) - Jobs and freelancer profiles in one actor.
- [Upwork Scraper](https://apify.com/the-empire-strikes-back/upwork-scraper) - Job listings scraper.
- [Upwork Scraper — Freelance Jobs](https://apify.com/thirdwatch/upwork-jobs-scraper) - Jobs and freelancer data.
- [Upwork Jobs Scraper](https://apify.com/igview-owner/upwork-jobs-scraper) - Job listing extraction.
- [Upwork Job Scraper](https://apify.com/chronometrica/upwork-job-scraper) - Fresh job listings by search.
- [Upwork Jobs Scraper](https://apify.com/curious_coder/upwork-jobs-scraper) - Low-cost bulk job scraping.
- [Upwork Jobs Scraper](https://apify.com/valig/upwork-jobs-scraper) - One of the cheapest per-1k job scrapers on the store.
- [Upwork Job Extractor](https://apify.com/ninz/upwork-job-extractor) - Search-driven job extraction.
- [Upwork Jobs Scraper](https://apify.com/kaix/upwork-jobs-scraper) - Very low per-row pricing.
- [Upwork Jobs Universal](https://apify.com/scrapifier/upwork-jobs-universal-scraper) - Job monitoring across searches.
- [Upwork Jobs Scraper](https://apify.com/trakk/upwork-jobs-scraper) - Current job listings by query.
- [Upspy](https://apify.com/angelbots/upspy-apify-actor) - Upwork jobs scraper with monitoring.
- [Upwork Job Monitor](https://apify.com/deepmine/upwork-job-monitor) - Subscription monitor for new postings.
- [Upwork Jobs Finder](https://apify.com/deepmine/upwork-jobs-finder) - Subscription job finder.
- [UpworkHawk](https://apify.com/inexhaustible_glass/upwork-hawk) - Job scraper with smart filtering.
- [Upwork Job Scraper](https://apify.com/scrapfox/upwork-job-scraper-pro) - Job listings with reviews on the listing.
- [Cheapest Upwork Jobs](https://apify.com/energizing_technology/cheapest-upwork-jobs-scraper) - Budget-priced job stream.
- [Upwork Jobs Scraper](https://apify.com/accountable_eel/upwork-jobs-lookup) - Per-posting pricing.
- [Upwork Job Scraper](https://apify.com/corvuslab/upwork-job-scraper) - Job listing extraction.
- [Upwork Jobs Scraper](https://apify.com/scrapersdelight/upwork-jobs-scraper) - Per-job pricing.

## Freelancer & Talent Data

Sources that return freelancer profiles rather than job postings — rates, Job Success Score, earnings, work history.

- [Moxlade — Upwork Freelancer Search](https://apify.com/moxlade/upwork-freelancers?ref=awesome-upwork) - Search 30,000+ profiles by rate, JSS, country, hours; exact earnings and contract history with feedback both ways, live or from a daily-refreshed census.
- [Upwork Freelancers Scraper](https://apify.com/parseforge/upwork-freelancers-scraper) - The most-used talent scraper on Apify; exact earnings, top-rated filtering, 26 fields.
- [Upwork Talent Scraper](https://apify.com/bovi/upwork-talent-scraper) - Public profiles with exact lifetime earnings and an earnings-hidden flag.
- [Upwork Talent Search](https://apify.com/powerai/upwork-talent-scraper) - Rich freelancer profiles from a talent search URL.
- [Upwork Talent Scraper](https://apify.com/crw/upwork-talent-scraper) - Profiles with ciphertext IDs, rate-band and badge filters.
- [Upwork Freelancer & Talent](https://apify.com/parseforge/upwork-scraper) - Freelancer profiles with job-relevance scoring.
- [Upwork Freelancers Scraper](https://apify.com/gio21/upwork-freelancers-scraper) - Profile search by keyword and country.
- [Upwork Freelancers Scraper](https://apify.com/jungle_synthesizer/upwork-freelancers-scraper) - Freelancer search and extraction.

## Client & Market Intelligence

Tools that analyse the demand side: who is hiring, what they pay, and which postings are worth a proposal.

- [Upwork Rate & Market Intelligence](https://apify.com/bovi/upwork-market-intelligence) - Benchmark the going rate for any freelance skill.
- [Upwork Job Demand Analytics](https://apify.com/glowing_glove/upwork-job-demand-buyer-intent-scraper) - Monitor freelance demand and buyer activity over time.
- [Upwork Job Fit Ranker](https://apify.com/fractionalhqforyou/upwork-job-fit-ranker) - Rank open postings against your own profile.
- [Freelance Lead Radar](https://apify.com/scrapemint/upwork-opportunity-alert) - Surfaces high-intent freelance opportunities for developers.
- [Upwork High-Intent Projects](https://apify.com/technicaldost/upwork-high-intent-job-lead-scorer) - Filters for postings that signal real budget and intent.
- [Upwork Jobs with Country Filter](https://apify.com/getdataforme/upwork-jobs-with-country-filter) - Job listings filtered by client country.
- [Upwork Job Search Scraper](https://apify.com/reapx/upwork-job-search-scraper) - Compare open roles across searches.

## Open-Source Scrapers & Job Feeds

Self-hosted alternatives — run them yourself, no per-row cost.

- [UpworkScraper](https://github.com/roperi/UpworkScraper) - Scrape your best-match job postings from Upwork (Python).
- [Upwork-Job-Scraper](https://github.com/richardadonnell/Upwork-Job-Scraper) - "No Upwork RSS feed? No problem" — scrape and track job listings.
- [Upwork-Job-Scraper](https://github.com/asaniczka/Upwork-Job-Scraper) - Real-time updates and archiving of Upwork jobs for analysis.
- [Upwork-Jobs-scraper](https://github.com/hashiromer/Upwork-Jobs-scraper-) - Fetch newly posted Upwork jobs (Go).
- [upwork-job-scraper](https://github.com/sudhamjayanthi/upwork-job-scraper) - Browse Upwork jobs from your terminal.
- [Upwork-job-checker](https://github.com/Lazar-T/Upwork-job-checker) - Get notified when a new job is posted.
- [upwork-scraping](https://github.com/s-alexander-s/upwork-scraping) - Upwork scraping notebooks and analysis.
- [upwork-jobs-scraper](https://github.com/samir-bensayou/upwork-jobs-scraper) - Self-hosted jobs scraper API with Cloudflare bypass.
- [Upwork-Job-feed-api](https://github.com/sushil-rgb/Upwork-Job-feed-api--Web-scraping-niche-) - API that serves Upwork job listings from RSS.
- [upwork-telegram-bot](https://github.com/iJohnMaged/upwork-telegram-bot) - Pipe new Upwork jobs into Telegram.
- [Apify-Upwork-Jobs-Scraper](https://github.com/orgupdate/Apify-Upwork-Jobs-Scraper) - Open-source companion to an Apify job scraper.

## Proposal & Bidding Tools

- [Upwork-AI-jobs-applier](https://github.com/kaymen99/Upwork-AI-jobs-applier) - AI agents that find, qualify and draft applications for Upwork jobs.
- [Upwork-Auto-Jobs-Applier-using-AI](https://github.com/AIXerum/Upwork-Auto-Jobs-Applier-using-AI) - UpworkScribe AI: automated job discovery and proposal writing.
- [upwork-skills](https://github.com/abullaisi/upwork-skills) - AI agent skills for Upwork freelancers, from a Top Rated Plus playbook.
- [Upwork-Proposal-AI](https://github.com/aoulaa/Upwork-Proposal-AI) - Free, privacy-focused Chrome extension that drafts proposals.
- [upwork-toolkit](https://github.com/neeilya/upwork-toolkit) - Chrome extension that assists with project bidding on Upwork.

## Job Aggregators

Multi-platform feeds that include Upwork alongside other marketplaces.

- [workaholic](https://github.com/DykstraBruno/workaholic) - Aggregates and filters freelance listings from Upwork, Workana, 99Freelas and more.
- [geezap](https://github.com/theihasan/geezap) - AI-powered job aggregation platform (Laravel) unifying multiple job sources.

## Desktop & Time Tracker Utilities

- [upwork-wayland](https://github.com/MarSoft/upwork-wayland) - Bridge between the GNOME screenshot protocol and Sway, so the Upwork time tracker works on Wayland.
- [upwork-wayland-workaround](https://github.com/muhammad-rafey/upwork-wayland-workaround) - Screenshot bridge enabling Upwork time tracking on GNOME Wayland.

## Guides & Playbooks

- [OdeskConf guide](https://github.com/odeskconf/guide) - Long-running community guide to working on Upwork (Russian).
- [Freelancer'in Finansal Yol Haritası](https://github.com/birlikteihracat/freelancerin-finansal-yol-haritasi) - Company formation, incentives and tax for freelancers exporting via Upwork and Fiverr (Turkish).
- [Upwork additional questions and answers](https://github.com/kcoitk/Upwork-additional-questions-and-answers-of-job-application) - Collected answers to Upwork's application screening questions.
- [Upwork cover letter samples](https://github.com/rahmandikahaekal/Upwork-coverletter) - Cover letter templates for proposals.
- [Upwork CoverLetter](https://github.com/qodrorid/Upwork-CoverLetter) - Proposal cover letter examples.

## Communities & Status

- [r/Upwork](https://www.reddit.com/r/Upwork/) - The largest Upwork discussion community.
- [r/freelance](https://www.reddit.com/r/freelance/) - General freelancing discussion, heavy Upwork overlap.
- [Upwork Community](https://community.upwork.com/) - Upwork's official user forum.
- [Upwork Help Center](https://support.upwork.com/) - Official documentation and policy reference.
- [Upwork Status](https://status.upwork.com/) - Platform incident and uptime status.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) first.

Removal requests from tool owners are honoured without argument — open an issue.
