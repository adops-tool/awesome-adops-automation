<div align="center">

[![awesome-adops-automation](image/awesome-adops-automation.png)](https://github.com/adops-tool/awesome-adops-automation/pulls)

[![animated-line](https://github.com/readme-SVG/animated-line/blob/main/STORAGE/line-svg-3D444D.svg)](https://github.com/readme-SVG/animated-line) <!-- -SVG-Line- -->

**A curated list of code, SDKs, and pipelines that replace manual trafficking, QA, and reporting work with scripts.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg)](LICENSE)

</div>

> Resource types: ![github](image/alg_R.png) GitHub repository; ![web](image/alg_I.png) documentation, specification, or hosted tool. Licenses, API permissions, and costs vary. Existing historical resources are labeled; new submissions should be actively maintained.

> **Safety:** Some tools can change campaigns, budgets, inventory, or consent settings. Review code and permissions, protect credentials, and use a sandbox or dry run before allowing production writes. Check privacy requirements before sharing tags, logs, or user data with third-party tools.

## Table of Contents

- [Ad Server APIs & Official SDKs](#ad-server-apis--official-sdks)
- [Campaign & Trafficking Automation](#campaign--trafficking-automation)
- [AI & MCP for AdOps](#ai--mcp-for-adops)
- [Header Bidding & Programmatic](#header-bidding--programmatic)
- [Ad Tag QA & Automated Testing](#ad-tag-qa--automated-testing)
- [Supply Chain, Privacy & Consent](#supply-chain-privacy--consent)
- [Data Pipelines & ETL for Ad Data](#data-pipelines--etl-for-ad-data)
- [Reporting, SQL & BI Templates](#reporting-sql--bi-templates)
- [Workflow Orchestration & No-Code/Low-Code](#workflow-orchestration--no-codelow-code)
- [Learning Resources & Communities](#learning-resources--communities)
- [Contributing](#contributing)
- [License](#license)

---

## Ad Server APIs & Official SDKs

*Client libraries and API references for publisher ad servers, buying platforms, and campaign management.*

### Google Ad Manager SDKs

![github](image/alg_R.png) [googleads-python-lib](https://github.com/googleads/googleads-python-lib) - Official Python client for the Google Ad Manager SOAP API.

![github](image/alg_R.png) [googleads-java-lib](https://github.com/googleads/googleads-java-lib) - Official Java client for the Google Ad Manager SOAP API.

![github](image/alg_R.png) [googleads-dotnet-lib](https://github.com/googleads/googleads-dotnet-lib) - Official .NET client for the Google Ad Manager SOAP API.

![github](image/alg_R.png) [googleads-php-lib](https://github.com/googleads/googleads-php-lib) - Official PHP client for the Google Ad Manager SOAP API.

![github](image/alg_R.png) [google-api-ads-ruby](https://github.com/googleads/google-api-ads-ruby) - Official Ruby client for the Google Ad Manager SOAP API.

![github](image/alg_R.png) [Ad Manager REST client for Python](https://github.com/googleapis/google-cloud-python/tree/main/packages/google-ads-admanager) - Official Python client for reading Ad Manager data and running reports via the REST API beta.

![github](image/alg_R.png) [Ad Manager REST client for Node.js](https://github.com/googleapis/google-cloud-node/tree/main/packages/google-ads-admanager) - Official Node.js client for reading Ad Manager data and running reports via the REST API beta.

![github](image/alg_R.png) [google-ad-manager-api](https://github.com/MailOnline/google-ad-manager-api) - Community TypeScript SOAP client with typed services, PQL helpers, pagination, and a report runner.

![github](image/alg_R.png) [Guardian Ad Manager API client](https://github.com/guardian/google-admanager-api) - JavaScript and TypeScript client for Ad Manager SOAP services, authentication, and reporting.

![github](image/alg_R.png) [pyadmanager](https://github.com/shani-suthar/pyadmanager) - Community Python client for reading Ad Manager REST resources and running saved reports.

### Google Ads SDKs

![github](image/alg_R.png) [google-ads-python](https://github.com/googleads/google-ads-python) - Official Python client library for the Google Ads API.

![github](image/alg_R.png) [google-ads-java](https://github.com/googleads/google-ads-java) - Official Java client library for the Google Ads API.

![github](image/alg_R.png) [google-ads-dotnet](https://github.com/googleads/google-ads-dotnet) - Official .NET client library for the Google Ads API.

![github](image/alg_R.png) [google-ads-php](https://github.com/googleads/google-ads-php) - Official PHP client library for the Google Ads API.

![github](image/alg_R.png) [google-ads-ruby](https://github.com/googleads/google-ads-ruby) - Official Ruby client library for the Google Ads API.

![github](image/alg_R.png) [google-ads-perl](https://github.com/googleads/google-ads-perl) - Official Perl client library for the Google Ads API.

![github](image/alg_R.png) [google-ads-api](https://github.com/Opteo/google-ads-api) - Community-maintained Node.js client for the Google Ads API.

### Google Marketing Platform clients

![github](image/alg_R.png) [Google API Python client](https://github.com/googleapis/google-api-python-client) - Client for Google discovery-based APIs including Campaign Manager 360 and Display & Video 360; in maintenance mode.

![github](image/alg_R.png) [Google APIs Node.js client](https://github.com/googleapis/google-api-nodejs-client) - Node.js client for Google APIs including Campaign Manager 360 and Display & Video 360.

### Other advertising SDKs

![github](image/alg_R.png) [facebook-python-business-sdk](https://github.com/meta/facebook-python-business-sdk) - Official Python SDK for the Meta Marketing API.

![github](image/alg_R.png) [facebook-nodejs-business-sdk](https://github.com/meta/facebook-nodejs-business-sdk) - Official Node.js SDK for the Meta Marketing API.

![github](image/alg_R.png) [facebook-java-business-sdk](https://github.com/meta/facebook-java-business-sdk) - Official Java SDK for the Meta Marketing API.

![github](image/alg_R.png) [facebook-php-business-sdk](https://github.com/meta/facebook-php-business-sdk) - Official PHP SDK for the Meta Marketing API.

![github](image/alg_R.png) [facebook-ruby-business-sdk](https://github.com/meta/facebook-ruby-business-sdk) - Official Ruby SDK for the Meta Marketing API.

![github](image/alg_R.png) [BingAds Python SDK](https://github.com/BingAds/BingAds-Python-SDK) - Microsoft Advertising client with campaign, bulk, and reporting services for Python.

![github](image/alg_R.png) [BingAds Java SDK](https://github.com/BingAds/BingAds-Java-SDK) - Microsoft Advertising client with campaign, bulk, and reporting services for Java.

![github](image/alg_R.png) [BingAds .NET SDK](https://github.com/BingAds/BingAds-dotNet-SDK) - Microsoft Advertising client for .NET applications.

![github](image/alg_R.png) [BingAds PHP SDK](https://github.com/BingAds/BingAds-PHP-SDK) - Microsoft Advertising client for PHP applications.

![github](image/alg_R.png) [TikTok Business API SDK](https://github.com/tiktok/tiktok-business-api-sdk) - TikTok client libraries for authentication, campaign creation, and reporting.

![github](image/alg_R.png) [Pinterest Python SDK](https://github.com/pinterest/pinterest-python-sdk) - Pinterest's Python SDK for advertising campaign management.

![github](image/alg_R.png) [adzerk-decision-sdk-js](https://github.com/adzerk/adzerk-decision-sdk-js) - Official JavaScript SDK for Kevel's real-time Decision API.

![github](image/alg_R.png) [adzerk-decision-sdk-python](https://github.com/adzerk/adzerk-decision-sdk-python) - Official Python SDK for Kevel's Decision API.

![github](image/alg_R.png) [adzerk-management-sdk-js](https://github.com/adzerk/adzerk-management-sdk-js) - Official JavaScript SDK for automating Kevel campaign and flight setup.

![github](image/alg_R.png) [adzerk-management-sdk-ruby](https://github.com/adzerk/adzerk-management-sdk-ruby) - Official Ruby SDK for the Kevel Management API.

![github](image/alg_R.png) [swift-package-manager-amazon-aps](https://github.com/amzn/swift-package-manager-amazon-aps) - Amazon Publisher Services bidding SDK distribution for iOS via Swift Package Manager.

### Official API references

![web](image/alg_I.png) [Google Ad Manager SOAP API](https://developers.google.com/ad-manager/api/start) - Manage Ad Manager inventory and orders and pull reports through the SOAP API.

![web](image/alg_I.png) [Google Ad Manager REST API beta](https://developers.google.com/ad-manager/api/beta/getting-started) - Getting started guide for reading Ad Manager data and running reports using the REST API.

![web](image/alg_I.png) [Enable Google Ad Manager API access](https://support.google.com/admanager/answer/3088588?hl=en) - Instructions for administrators to enable API access in an Ad Manager network.

![web](image/alg_I.png) [Google Ad Manager test networks](https://developers.google.com/ad-manager/api/environments) - Guide to isolated test networks and their limitations, including empty reports and no ad serving.

![web](image/alg_I.png) [Google Ads API](https://developers.google.com/google-ads/api/docs/get-started/introduction) - Manage Google Ads accounts, campaigns, ads, and bidding programmatically.

![web](image/alg_I.png) [Campaign Manager 360 API](https://developers.google.com/doubleclick-advertisers/rest) - Reporting and trafficking API for CM360 campaigns, placements, creatives, and reports.

![web](image/alg_I.png) [Display & Video 360 API](https://developers.google.com/display-video/api/reference/rest) - Manage DV360 advertisers, campaigns, insertion orders, line items, and other resources.

![web](image/alg_I.png) [Bid Manager API](https://developers.google.com/bid-manager/guides/get-started/overview) - Create and run Display & Video 360 reporting queries.

![web](image/alg_I.png) [Search Ads 360 Reporting API](https://developers.google.com/search-ads/reporting) - Read-only API for querying Search Ads 360 resources and performance data.

![web](image/alg_I.png) [AdSense Management API reports](https://developers.google.com/adsense/management/reference/rest/v2/accounts.reports) - Generate and retrieve AdSense publisher reports, including CSV output.

![web](image/alg_I.png) [AdMob API reporting](https://developers.google.com/admob/api/v1/reporting) - Generate AdMob network and mediation reports for mobile app inventory.

![web](image/alg_I.png) [Google Tag Manager API](https://developers.google.com/tag-platform/tag-manager/api/v2) - Manage containers, workspaces, tags, triggers, and variables programmatically.

![web](image/alg_I.png) [Google Data Manager API](https://developers.google.com/data-manager/api/devguides) - Send first-party audiences and conversion events to supported Google advertising products.

![web](image/alg_I.png) [Meta Marketing API](https://developers.facebook.com/documentation/ads-commerce/marketing-api/overview) - Create, manage, and analyze advertising across Meta technologies.

![web](image/alg_I.png) [Microsoft Advertising API](https://learn.microsoft.com/en-us/advertising/guides/client-libraries) - Guides and client libraries for Microsoft Advertising campaign management and reporting.

![web](image/alg_I.png) [Microsoft Monetize API](https://learn.microsoft.com/en-us/xandr/monetize/digital-platform-ui-api-info) - Digital Platform API guides for automating buy-side and sell-side operations and reporting.

![web](image/alg_I.png) [TikTok Marketing API](https://business-api.tiktok.com/portal/docs/marketing-api/v1.3) - Documentation for TikTok campaign management, reporting, and business integrations.

![web](image/alg_I.png) [LinkedIn Marketing APIs](https://learn.microsoft.com/en-us/linkedin/marketing/integrations/ads/ads-overview) - API overview for LinkedIn advertising accounts, campaigns, creatives, and analytics.

![web](image/alg_I.png) [Snap Ads API](https://developers.snap.com/marketing-api/Ads-API/introduction) - Create and manage Snapchat advertising campaigns and retrieve performance data.

![web](image/alg_I.png) [Pinterest API](https://developers.pinterest.com/docs/api/v5/introduction/) - Manage Pinterest advertising campaigns, targeting, and analytics through the REST API.

![web](image/alg_I.png) [Reddit Ads API](https://ads-api.reddit.com/docs/v3/api/reddit-advertising-api) - Manage Reddit ad accounts, campaigns, ads, and reporting via the API.

![web](image/alg_I.png) [X Ads API analytics](https://docs.x.com/x-ads-api/analytics) - Retrieve synchronous and asynchronous campaign performance metrics from X Ads.

![web](image/alg_I.png) [Amazon Ads API](https://advertising.amazon.com/about-api) - Programmatic access to Amazon Ads campaign management and reporting capabilities.

![web](image/alg_I.png) [Apple Ads Platform API](https://developer.apple.com/documentation/apple-ads-platform-api) - Manage App Store and Apple Maps advertising campaigns through Apple's API.

![web](image/alg_I.png) [Spotify Ads API](https://developer.spotify.com/documentation/ads-api) - Create and manage Spotify ad campaigns, assets, and performance reports.

![web](image/alg_I.png) [Yahoo DSP API](https://help.yahooinc.com/dsp-api/docs/dsp-api-help-home) - Manage DSP campaigns, line items, deals, and reporting through Yahoo's APIs.

![web](image/alg_I.png) [The Trade Desk Platform API](https://open.thetradedesk.com/advertiser/docsApp/Foundations/resources/doc/ApisPlatformOpenTTD) - REST and GraphQL interfaces for managing programmatic campaigns and related data.

![web](image/alg_I.png) [Criteo Retail Media API](https://developers.criteo.com/retail-media/docs/capability-map) - API capabilities for retail media campaigns, line items, and performance reporting.

![web](image/alg_I.png) [Kevel APIs](https://dev.kevel.com/reference/getting-started-with-kevel) - API overview for ad decisions, campaign management, inventory, and reporting.

![web](image/alg_I.png) [FreeWheel Publisher APIs](https://api-docs.freewheel.tv/publisher/docs/getting-started) - Integration guide for managing advertisers, campaigns, insertion orders, and placements.

![web](image/alg_I.png) [Equativ Monetization API](https://supply-api.eqtv.io/help/) - REST API reference for automating inventory, campaigns, insertions, and creatives.

![web](image/alg_I.png) [Equativ Auction Package API](https://help.equativ.com/manage-deals-with-the-api) - Guide to creating, updating, pausing, and reporting on programmatic deals.

![web](image/alg_I.png) [Adform Reporting Stats API](https://www.adformhelp.com/hc/en-us/articles/35919201471121-Guide-to-Generating-Advertiser-Reports-With-API) - Guide to requesting and retrieving asynchronous advertiser performance reports.

![web](image/alg_I.png) [AdButler Self-Serve API](https://www.adbutler.com/help/article/v1-self-serve-flow) - Workflow for creating campaign drafts, ad items, and placements; requires API and self-service add-ons.

### Conversion and event APIs

*These integrations can transmit personal data; check consent and applicable privacy requirements before sending events.*

![web](image/alg_I.png) [Meta Conversions API](https://developers.facebook.com/documentation/ads-commerce/conversions-api) - Send website, app, messaging, and offline events to Meta for measurement.

![web](image/alg_I.png) [LinkedIn Conversions API](https://learn.microsoft.com/en-us/linkedin/marketing/integrations/ads-reporting/conversions-api) - Create conversion rules and stream conversion events to LinkedIn.

![web](image/alg_I.png) [TikTok Events API](https://business-api.tiktok.com/portal/docs/events-api-2.0/v1.3) - Server-to-server integration for web, app, offline, and CRM events.

![web](image/alg_I.png) [Snap Conversions API](https://developers.snap.com/marketing-api/Conversions-API/Introduction) - Send web, app, and offline conversion events to Snap from a server.

![web](image/alg_I.png) [Pinterest Conversions API](https://developers.pinterest.com/docs/track-conversions/track-conversions-in-the-api/) - Send and test website, app, and offline conversion events.

![web](image/alg_I.png) [Reddit Conversions API](https://ads-api.reddit.com/docs/v3/guides/programs/capi/direct-integration) - Direct integration guide for server events, match keys, and event deduplication.

### Ad server implementations

![github](image/alg_R.png) [Revive Adserver](https://github.com/revive-adserver/revive-adserver) - Self-hosted ad server with XML-RPC services for managing campaigns and retrieving statistics.

---

## Campaign & Trafficking Automation

*Scripts, examples, and infrastructure-as-code tools for campaign creation, trafficking, and monitoring.*

### Campaign scripts and examples

![github](image/alg_R.png) [free-google-ads-scripts](https://github.com/charlesbannister/free-google-ads-scripts) - Collection of Google Ads scripts for account automation from Shabba.io / Automating AdWords.com.

![github](image/alg_R.png) [Google Ads Scripts Collection](https://github.com/itallstartedwithaidea/google-ads-scripts) - Scripts for bidding, budget management, monitoring, and reporting in Google Ads.

![github](image/alg_R.png) [Google Ads Bulk Campaign Builder](https://github.com/itallstartedwithaidea/google-ads-bulk-campaign-builder) - Creates Google Ads campaigns, ad groups, keywords, and responsive search ads from spreadsheet data.

![github](image/alg_R.png) [Google Ads read-only scripts](https://github.com/hustlemarketers-art/google-ads-scripts) - GAQL-based scripts for account audits and search-term reporting.

![github](image/alg_R.png) [adops-guard](https://github.com/deegitech/adops-guard) - Alpha CLI for Google Ads and Meta status and budget operations with dry runs; this version is tested only against mock APIs.

![github](image/alg_R.png) [Printing Press Google Ad Manager CLI](https://github.com/mvanhorn/printing-press-library/tree/main/library/marketing/google-ad-manager) - Community CLI and MCP server for Ad Manager REST beta reporting, pacing, and inventory; supports writes.

![github](image/alg_R.png) [DV360 API examples](https://github.com/googleads/googleads-displayvideo-examples) - Google's Java, PHP, and Python examples for the Display & Video 360 API.

![github](image/alg_R.png) [DV360 Triggerator](https://github.com/google/triggerator) - Applies rules and external data feeds to manage DV360 insertion orders and line items; not an officially supported Google product.

![github](image/alg_R.png) [If This Then Ad](https://github.com/google-marketing-solutions/if-this-then-ad) - Uses external data and rules to control supported Google Ads and DV360 campaign entities.

![web](image/alg_I.png) [Google Ads Scripts documentation](https://developers.google.com/google-ads/scripts/docs/getting-started) - Guides for JavaScript automations that run inside Google Ads.

![web](image/alg_I.png) [Google Ads Link Checker](https://developers.google.com/google-ads/scripts/docs/solutions/link-checker) - Google script that checks ad, keyword, and sitelink URLs and reports failures.

![web](image/alg_I.png) [Google Ads Account Anomaly Detector](https://developers.google.com/google-ads/scripts/docs/solutions/account-anomaly-detector) - Google script that alerts when account performance deviates from historical patterns.

![web](image/alg_I.png) [CM360 Apps Script service](https://developers.google.com/apps-script/advanced/doubleclick-campaigns) - Apps Script examples for accessing CM360 trafficking and reporting resources.

![web](image/alg_I.png) [DV360 Apps Script service](https://developers.google.com/apps-script/advanced/dv360) - Apps Script examples for listing campaigns and updating DV360 line items.

### Infrastructure as code

![github](image/alg_R.png) [Terraform provider for Ad Manager](https://github.com/VictorCano/terraform-provider-admanager) - Pre-release community Terraform/OpenTofu provider for GAM ad units, placements, and custom targeting.

![github](image/alg_R.png) [Terraform provider for Google Ads](https://github.com/vittorfp/terraform-provider-googleads) - Community beta provider for managing supported Google Ads resources as Terraform configuration.

---

## AI & MCP for AdOps

*Agent tools and Model Context Protocol (MCP) servers for querying or operating advertising accounts. Capabilities and safety controls vary; review each project before granting access.*

![github](image/alg_R.png) [Google Ads MCP Server](https://github.com/googleads/google-ads-mcp) - Google's MCP server for Google Ads queries and guarded asset and label operations.

![github](image/alg_R.png) [Google Ads API Developer Assistant](https://github.com/googleads/google-ads-api-developer-assistant) - Assistant for Google Ads API questions, GAQL validation, code generation, and data retrieval.

![web](image/alg_I.png) [Microsoft Monetize/Curate MCP](https://learn.microsoft.com/en-us/xandr/monetize/mcp-getting-started) - Guide to Microsoft's read-only alpha MCP server for reports, deal troubleshooting, and inventory queries.

![web](image/alg_I.png) [TikTok for Business MCP](https://business-api.tiktok.com/portal/docs/tiktok-ads-mcp-server/v1.3) - TikTok's hosted MCP server for campaign management, reporting, and other Ads API operations.

![web](image/alg_I.png) [Yahoo DSP MCP](https://help.yahooinc.com/dsp-api/docs/yahoo-dsp-mcp-server) - Yahoo's hosted MCP server for campaign, audience, and creative management using DSP permissions.

![web](image/alg_I.png) [Spotify Ads MCP](https://developer.spotify.com/documentation/ads-api/agents) - Spotify's closed-beta MCP server for accessing campaign insights; requires account-team approval.

![github](image/alg_R.png) [PubMatic MCP specifications](https://github.com/PubMatic/pubmatic-mcp-server) - Integration specifications for PubMatic's deal management, troubleshooting, and inventory discovery tools.

![github](image/alg_R.png) [OrbiAds GAM MCP](https://github.com/OrbiAds/Orbiads-GAM-MCP) - Hosted Google Ad Manager MCP server and CLI for inventory, trafficking, and reporting with confirm-before-write controls.

![github](image/alg_R.png) [Google Ad Manager MCP](https://github.com/MatiousCorp/google-ad-manager-mcp) - Community MCP server for working with GAM orders, line items, and creatives.

![github](image/alg_R.png) [LinkedIn Ads MCP Toolkit](https://github.com/adops-tool/linkedin-ads-mcp-toolkit) - MCP server for LinkedIn Ads analytics and campaign management, with an optional read-only mode.

![github](image/alg_R.png) [AdOps MCP](https://github.com/automatiabcn/adops-mcp) - CSV-first MCP analytics for exported Google Ads and Meta Ads data rather than a live API integration.

![github](image/alg_R.png) [Spotify Ads Agentic Tools](https://github.com/spotify/ads-agentic-tools) - Spotify's agent plugins for campaign setup, management, and reporting through the Ads API.

![github](image/alg_R.png) [AdButler Skills](https://github.com/adbutler/skills) - Agent instructions and code templates for AdButler campaign, video, targeting, and reporting workflows.

![github](image/alg_R.png) [Programmatic Skills](https://github.com/scumunna/programmatic-skills) - Agent playbooks for programmatic trading, CM360 trafficking, tag management, and reporting.

![github](image/alg_R.png) [AdTraffic.ai Kiki](https://github.com/kikiavalon/adtraffic) - Experimental CM360 trafficking assistant; its author states that the live API path is unverified.

![github](image/alg_R.png) [IAB Tech Lab Buyer Agent](https://github.com/IABTechLab/buyer-agent) - Agent project for discovering inventory and negotiating programmatic direct deals using OpenDirect.

![github](image/alg_R.png) [IAB Tech Lab Seller Agent](https://github.com/IABTechLab/seller-agent) - Agent project for managing publisher inventory and programmatic deal negotiations.

![github](image/alg_R.png) [Prebid Sales Agent](https://github.com/prebid/salesagent) - Alpha Ad Context Protocol sales agent with Google Ad Manager integration; see the reported [GAM pause/resume issue](https://github.com/prebid/salesagent/issues/2636).

---

## Header Bidding & Programmatic

*Header bidding implementations, setup utilities, and auction diagnostics.*

![github](image/alg_R.png) [Prebid.js](https://github.com/prebid/Prebid.js) - Browser-side header bidding library for running auctions across demand partners.

![github](image/alg_R.png) [Prebid Server](https://github.com/prebid/prebid-server) - Go implementation of server-side header bidding auctions.

![github](image/alg_R.png) [Prebid Server Java](https://github.com/prebid/prebid-server-java) - Java implementation of Prebid Server for server-side auctions.

![github](image/alg_R.png) [Prebid Mobile iOS](https://github.com/prebid/prebid-mobile-ios) - iOS SDK for integrating mobile apps with Prebid Server.

![github](image/alg_R.png) [Prebid Mobile Android](https://github.com/prebid/prebid-mobile-android) - Android SDK for integrating mobile apps with Prebid Server.

![github](image/alg_R.png) [Prebid Line Item Manager](https://github.com/prebid/line-item-manager) - CLI for creating and managing header bidding line items in Google Ad Manager, with dry-run support.

![github](image/alg_R.png) [Professor Prebid](https://github.com/prebid/professor-prebid) - Browser debugging tool for inspecting Prebid configuration and auction activity.

![web](image/alg_I.png) [Prebid documentation](https://docs.prebid.org/) - Integration guides for Prebid.js, Prebid Server, mobile SDKs, and advertising formats.

![github](image/alg_R.png) [OpenRTB 2.x](https://github.com/InteractiveAdvertisingBureau/openrtb2.x) - IAB Tech Lab's versioned OpenRTB specification for programmatic bid requests and responses.

![web](image/alg_I.png) [Google Authorized Buyers OpenRTB guide](https://developers.google.com/authorized-buyers/rtb/openrtb-guide) - Reference for Google's OpenRTB request and response fields, extensions, and tracking.

![github](image/alg_R.png) [rtblint](https://github.com/aleksUIX/rtblint) - CLI and library for validating OpenRTB bid requests and responses against versioned specifications.

---

## Ad Tag QA & Automated Testing

*Frameworks, inspectors, validators, and test players for advertising tags and traffic.*

### Browser and request inspection

![github](image/alg_R.png) [playwright](https://github.com/microsoft/playwright) - Cross-browser automation framework for scripted tag rendering and click-through QA.

![github](image/alg_R.png) [puppeteer](https://github.com/puppeteer/puppeteer) - Browser automation library for ad tag loading tests and screenshots.

![github](image/alg_R.png) [mitmproxy](https://github.com/mitmproxy/mitmproxy) - Scriptable HTTPS proxy for inspecting ad request and response traffic.

![github](image/alg_R.png) [devtools-protocol](https://github.com/ChromeDevTools/devtools-protocol) - Chrome DevTools Protocol reference for building browser and network inspection tools.

![github](image/alg_R.png) [Google Publisher Tag samples](https://github.com/googleads/google-publisher-tag-samples) - Official GPT examples for implementing and testing publisher ad slots.

![github](image/alg_R.png) [AdTrace GAM Inspector](https://github.com/adops-tool/adtrace-gam-inspector) - Chrome DevTools extension for inspecting GAM requests, targeting, delivery, and privacy signals.

![github](image/alg_R.png) [Programmatic Ad Scanner](https://github.com/Chrome-Extensions-labs/programmatic-ad-scanner) - Chrome extension that scans ad iframes and detects GPT, Prebid.js, and Amazon APS signals.

![github](image/alg_R.png) [ad-vitals](https://github.com/MATAPOMBO/ad-vitals) - CLI that associates layout shifts and browser performance measurements with ad slots.

![web](image/alg_I.png) [Google Publisher Console](https://developers.google.com/publisher-tag/guides/publisher-console) - Built-in GPT diagnostics for ad slots, page requests, and delivery troubleshooting.

![web](image/alg_I.png) [Publisher Debug](https://chromewebstore.google.com/detail/publisher-debug/nhijejfjieloehdlkicfakfjfmnkgnlf) - Chrome DevTools panel for inspecting GPT, Prebid, Amazon bidding, and consent signals.

![web](image/alg_I.png) [AdsDebugger](https://chromewebstore.google.com/detail/adsdebugger/bninkopdmdpoiekbcncongnpmbdhmkpg) - Chrome extension for inspecting GAM, Prebid, video requests, and tracking pixels.

![web](image/alg_I.png) [AdTech.dev Ad Inspector](https://chromewebstore.google.com/detail/adtechdev-ad-inspector/mmbfjiakfgpnpannoknhdbmoammbpdeh) - Chrome extension for inspecting ad slots, bids, targeting, and consent signals.

![web](image/alg_I.png) [AdTools](https://adtools.dev/) - Hosted testers for display tags and VAST, plus supply-chain and privacy-signal validators.

![web](image/alg_I.png) [AdOps Tag Inspector](https://iwakeimfarmakis-create.github.io/gam-tools/) - Static GAM tag and macro checks with spreadsheet batch scanning and an optional live preview.

### VAST, video, and pixel QA

![github](image/alg_R.png) [vastlint](https://github.com/aleksUIX/vastlint) - Validator for VAST, VMAP, and DAAST responses with command-line and library interfaces.

![github](image/alg_R.png) [pixellint](https://github.com/aleksUIX/pixellint) - Validator for conversion API payloads and tracking pixel URLs.

![github](image/alg_R.png) [vast-client-js](https://github.com/dailymotion/vast-client-js) - JavaScript library for parsing VAST responses and tracking video ad events.

![github](image/alg_R.png) [VAST Generator for Go](https://github.com/admein-advertising/admein-vast-generator) - Go library for generating, parsing, and validating VAST XML documents.

![github](image/alg_R.png) [VAST_Samples](https://github.com/InteractiveAdvertisingBureau/VAST_Samples) - Historical IAB sample VAST tags for testing video ad server and player integrations.

![github](image/alg_R.png) [VAST-Tester](https://github.com/IABTechLab/VAST-Tester) - Historical IAB Tech Lab tool for validating VAST tag responses.

![github](image/alg_R.png) [vast-tag-xml-examples](https://github.com/admein-advertising/vast-tag-xml-examples) - VAST 2.0, 3.0, and 4.x XML examples for video ad testing.

![github](image/alg_R.png) [videojs-ima](https://github.com/googleads/videojs-ima) - Google IMA SDK plugin for Video.js that can be used to build a test player.

![github](image/alg_R.png) [googleads-ima-html5](https://github.com/googleads/googleads-ima-html5) - Official samples for the HTML5 IMA SDK and video ad playback.

![web](image/alg_I.png) [IMA Video Suite Inspector](https://googleads.github.io/googleads-ima-html5/vsi/) - Google's hosted player for testing VAST tags or XML with the IMA SDK; playback can fire tracking events.

![web](image/alg_I.png) [VAST 4.3 specification](https://iabtechlab.com/wp-content/uploads/2022/09/VAST_4.3.pdf) - IAB Tech Lab's Video Ad Serving Template 4.3 specification.

---

## Supply Chain, Privacy & Consent

*Tools for seller authorization, supply-path inspection, and consent-signal implementations.*

### Supply-chain validation and quality

![github](image/alg_R.png) [Supply Chain Validation](https://github.com/InteractiveAdvertisingBureau/Supply-Chain-Validation) - IAB Tech Lab specifications and implementation guidance for ads.txt, app-ads.txt, and sellers.json.

![web](image/alg_I.png) [IAB Supply Chain Validation service](https://iabtechlab.com/software/supply-chain-validation/) - Hosted validation and alerts for ads.txt, app-ads.txt, and sellers.json relationships.

![web](image/alg_I.png) [OpenSincera](https://open.sincera.io/) - Publisher ad-experience metrics and an API for supply-quality analysis; API access requires registration.

![github](image/alg_R.png) [python-sellers-json-validator](https://github.com/adops-tool/python-sellers-json-validator) - Async Python tool for probing and validating sellers.json endpoints in bulk.

![github](image/alg_R.png) [SPO sellers.json crawler](https://github.com/adops-tool/SPO-sellers-json-crawler) - Discovers and checks sellers.json endpoints using seller domains and ads.txt relationships.

![github](image/alg_R.png) [AdVerify ads.txt crawler](https://github.com/adops-tool/AdVerify-adstxt-appadstxt-Crawler) - Async Python crawler for checking ads.txt and app-ads.txt availability across domains.

![github](image/alg_R.png) [ads_txt_scraper](https://github.com/willlightningstrike/ads_txt_scraper) - Cross-checks a publisher's ads.txt seller IDs against sellers.json records.

![github](image/alg_R.png) [SPO Auditor](https://github.com/scumunna/spo-auditor) - Audits supplied bid logs against ads.txt, sellers.json, and OpenRTB supply-chain objects.

![github](image/alg_R.png) [Lines Checker](https://github.com/Chrome-Extensions-labs/Lines-Checker-ads.txt-app-ads.txt-sellers.json) - Chrome extension for checking ads.txt and app-ads.txt entries against sellers.json.

![github](image/alg_R.png) [Inventory Auth Auditor](https://github.com/Chrome-Extensions-labs/Inventory-Auth-Auditor) - Chrome extension for checking ads.txt and app-ads.txt declarations against a reference set.

![github](image/alg_R.png) [Sellers.json Inspector](https://github.com/Chrome-Extensions-labs/Sellers.json-Inspector) - Chrome extension for parsing and inspecting sellers.json files.

### Consent signals and measurement

![github](image/alg_R.png) [iabtcf-es](https://github.com/InteractiveAdvertisingBureau/iabtcf-es) - IAB implementation tools for encoding and decoding Transparency and Consent Framework signals.

![github](image/alg_R.png) [iabgpp-es](https://github.com/IABTechLab/iabgpp-es) - JavaScript implementation for encoding and decoding Global Privacy Protocol signals.

![github](image/alg_R.png) [iabgpp-java](https://github.com/IABTechLab/iabgpp-java) - Java implementation of the Global Privacy Protocol signal format.

![github](image/alg_R.png) [php-iab-tcf](https://github.com/flenczewski/php-iab-tcf) - PHP library for encoding and decoding IAB TCF consent strings.

![github](image/alg_R.png) [Open Measurement JavaScript clients](https://github.com/InteractiveAdvertisingBureau/Open-Measurement-JSClients) - IAB client libraries for Open Measurement integrations in JavaScript.

![web](image/alg_I.png) [Global Privacy Protocol](https://iabtechlab.com/gpp/) - IAB Tech Lab's GPP specification and implementation resources for transmitting privacy signals.

![web](image/alg_I.png) [IAB Tech Lab](https://iabtechlab.com/) - Standards and specifications for VAST, OpenRTB, measurement, and programmatic supply chains.

---

## Data Pipelines & ETL for Ad Data

*Extract advertising data and transform it into warehouse-ready reporting models.*

### Extractors and connectors

![github](image/alg_R.png) [airbyte](https://github.com/airbytehq/airbyte) - ELT platform with connectors for sources including Google Ads, Meta Marketing, and TikTok Marketing.

![web](image/alg_I.png) [Airbyte source catalog](https://docs.airbyte.com/integrations/sources) - Connector documentation and availability for advertising and other data sources.

![web](image/alg_I.png) [Fivetran Google Ad Manager connector](https://fivetran.com/docs/connectors/applications/google-ad-manager) - Managed connector for syncing GAM metadata and custom reports to a destination.

![github](image/alg_R.png) [dlt](https://github.com/dlt-hub/dlt) - Python library for extracting and loading data into warehouses and other destinations.

![github](image/alg_R.png) [dlt verified sources](https://github.com/dlt-hub/verified-sources) - Example dlt pipelines including Google Ads and Facebook Ads; the Google Ads source is not regularly tested.

![github](image/alg_R.png) [Meltano](https://github.com/meltano/meltano) - Code-first data integration framework for running Singer taps and targets.

![github](image/alg_R.png) [tap-googleads (Matatika)](https://github.com/Matatika/tap-googleads) - Meltano/Singer tap that extracts Google Ads data for ELT pipelines.

![github](image/alg_R.png) [tap-google-ads (Singer)](https://github.com/singer-io/tap-google-ads) - Singer tap for Google Ads accounts, campaigns, and performance reports.

![github](image/alg_R.png) [tap-facebook (Singer)](https://github.com/singer-io/tap-facebook) - Singer tap for Facebook Marketing campaigns, ads, and insights.

![web](image/alg_I.png) [BigQuery Google Ads transfer](https://docs.cloud.google.com/bigquery/docs/google-ads-transfer) - Schedule transfers of Google Ads data into BigQuery.

![web](image/alg_I.png) [BigQuery Campaign Manager transfer](https://docs.cloud.google.com/bigquery/docs/doubleclick-campaign-transfer) - Load Campaign Manager 360 data into BigQuery and query it using sample SQL.

![web](image/alg_I.png) [BigQuery Display & Video 360 transfer](https://docs.cloud.google.com/bigquery/docs/display-video-transfer) - Load DV360 Data Transfer files and supported configuration data into BigQuery.

![web](image/alg_I.png) [BigQuery Search Ads 360 transfer](https://docs.cloud.google.com/bigquery/docs/search-ads-transfer) - Schedule Search Ads 360 reporting data transfers into BigQuery.

### dbt transformations and models

*The Fivetran packages below model data loaded using their corresponding connector schemas; check each package's supported inputs and warehouse requirements.*

![github](image/alg_R.png) [dbt_google_ads](https://github.com/fivetran/dbt_google_ads) - Models Google Ads campaign and performance data for reporting.

![github](image/alg_R.png) [dbt_facebook_ads](https://github.com/fivetran/dbt_facebook_ads) - Transforms Meta Ads data into reporting-ready tables.

![github](image/alg_R.png) [dbt_amazon_ads](https://github.com/fivetran/dbt_amazon_ads) - Models Amazon Ads data for advertising performance reports.

![github](image/alg_R.png) [dbt_linkedin](https://github.com/fivetran/dbt_linkedin) - Models LinkedIn Ads campaign and performance data.

![github](image/alg_R.png) [dbt_microsoft_ads](https://github.com/fivetran/dbt_microsoft_ads) - Models Microsoft Advertising data for reporting.

![github](image/alg_R.png) [dbt_tiktok_ads](https://github.com/fivetran/dbt_tiktok_ads) - Models TikTok Ads spend, impressions, clicks, and conversions.

![github](image/alg_R.png) [dbt_pinterest](https://github.com/fivetran/dbt_pinterest) - Models Pinterest Ads campaign and ad group performance data.

![github](image/alg_R.png) [dbt_reddit_ads](https://github.com/fivetran/dbt_reddit_ads) - Models Reddit Ads data into reporting tables.

![github](image/alg_R.png) [dbt_snapchat_ads](https://github.com/fivetran/dbt_snapchat_ads) - Models Snapchat Ads data for campaign reporting.

![github](image/alg_R.png) [dbt_apple_search_ads](https://github.com/fivetran/dbt_apple_search_ads) - Models Apple Search Ads account, campaign, keyword, and ad performance.

![github](image/alg_R.png) [dbt_twitter](https://github.com/fivetran/dbt_twitter) - Models X/Twitter Ads data for performance reporting.

![github](image/alg_R.png) [dbt_ad_reporting](https://github.com/fivetran/dbt_ad_reporting) - Combines supported advertising platform packages into a cross-channel reporting model.

![github](image/alg_R.png) [dbt-bigquery](https://github.com/dbt-labs/dbt-adapters/tree/main/dbt-bigquery) - Official dbt adapter for running transformations on BigQuery, including custom advertising models.

---

## Reporting, SQL & BI Templates

*Report fetchers, SQL utilities, and dashboarding platforms for advertising data.*

![github](image/alg_R.png) [ads-api-report-fetcher](https://github.com/google/ads-api-report-fetcher) - Google's gaarf tool runs GAQL queries against Google Ads and exports results to destinations such as BigQuery, Sheets, and CSV.

![github](image/alg_R.png) [bigquery-utils](https://github.com/GoogleCloudPlatform/bigquery-utils) - Google Cloud's reusable SQL scripts, UDFs, and views for BigQuery operations.

![github](image/alg_R.png) [grafana](https://github.com/grafana/grafana) - Dashboarding platform for visualizing metrics such as delivery, pacing, and spend from connected data sources.

![github](image/alg_R.png) [Apache Superset](https://github.com/apache/superset) - BI platform for building SQL-backed charts and dashboards over warehouse data.

![github](image/alg_R.png) [Metabase](https://github.com/metabase/metabase) - BI tool for querying and visualizing connected advertising data.

![web](image/alg_I.png) [Load Google Ad Manager data into BigQuery](https://docs.cloud.google.com/bigquery/docs/doubleclick-publisher-transfer) - Google guide and sample SQL for analyzing Ad Manager data transferred into BigQuery.

![web](image/alg_I.png) [Google Data Studio connectors](https://docs.cloud.google.com/data-studio/available-connectors) - Catalog of BI connectors for Google advertising products, warehouses, and other data sources; formerly Looker Studio.

---

## Workflow Orchestration & No-Code/Low-Code

*Schedulers and low-code tools for chaining advertising API calls, data pipelines, and reports.*

![github](image/alg_R.png) [airflow](https://github.com/apache/airflow) - Workflow orchestration platform for scheduling ad data extraction, QA, and reporting DAGs.

![github](image/alg_R.png) [apache-airflow-client-python](https://github.com/apache/airflow-client-python) - Official Python client for triggering and managing Airflow workflows through its REST API.

![github](image/alg_R.png) [Prefect](https://github.com/PrefectHQ/prefect) - Python workflow orchestration framework for scheduling and monitoring data pipelines.

![github](image/alg_R.png) [Dagster](https://github.com/dagster-io/dagster) - Data orchestration platform for defining and observing warehouse assets and pipelines.

![github](image/alg_R.png) [Kestra](https://github.com/kestra-io/kestra) - Workflow orchestrator for scheduled and event-driven data integration jobs.

![github](image/alg_R.png) [n8n](https://github.com/n8n-io/n8n) - Fair-code, self-hostable workflow automation tool with HTTP and webhook nodes for connecting APIs.

![github](image/alg_R.png) [apps-script-samples](https://github.com/googleworkspace/apps-script-samples) - Google's Apps Script samples for building spreadsheet-driven workflows and integrations.

---

## Learning Resources & Communities

*Further reading, curated collections, and communities for AdOps practitioners.*

![github](image/alg_R.png) [Awesome AdOps Site](https://github.com/adops-tool/awesome-adops-site) - Broader directory of publisher AdOps and ad tech resources.

![github](image/alg_R.png) [Awesome Header Bidding](https://github.com/adops-tool/awesome-header-bidding) - Curated collection of Prebid, header bidding, and debugging resources.

![github](image/alg_R.png) [Awesome Privacy AdTech](https://github.com/adops-tool/awesome-privacy-adtech) - Collection of privacy, consent, and identity resources for advertising technology.

![github](image/alg_R.png) [Awesome Agentic Advertising](https://github.com/jshorwitz/awesome-agentic-advertising) - Collection of agent protocols, MCP servers, and AI tools for advertising workflows.

![web](image/alg_I.png) [r/adops](https://www.reddit.com/r/adops/) - Reddit community discussing ad operations, programmatic workflows, and tooling.

![web](image/alg_I.png) [AdMonsters](https://www.admonsters.com/) - Publisher ad operations coverage and resources.

![web](image/alg_I.png) [AdExchanger](https://www.adexchanger.com/) - News and analysis on programmatic advertising and ad technology.

![web](image/alg_I.png) [Google Ads Developer Blog](https://ads-developers.googleblog.com/) - Google's developer updates on Ads and Ad Manager APIs and automation.

---


## Public Data APIs (Apify)

- [Google Ads Transparency Scraper](https://apify.com/publicrecords/google-ads-transparency-scraper) - Google ads a competitor runs, from the Ads Transparency Center, with first and last shown dates (Apify Actor, API + MCP).
- [Company Social Profile Finder](https://apify.com/publicrecords/company-social-profile-finder) - Company domain or name to its LinkedIn, X, YouTube, Instagram and Facebook links, with confidence scores (Apify Actor, API + MCP).
- [Etsy Search Scraper](https://apify.com/publicrecords/etsy-search-scraper) - Etsy search results by keyword: price, rating, reviews, Bestseller badge, ad flag, rank (Apify Actor, API + MCP).
- [Etsy Shop Daily Sales](https://apify.com/publicrecords/etsy-shop-velocity) - Daily, 7-day and 28-day sales for Etsy shops from each shop's public sales counter (Apify Actor, API + MCP).
- [Spotify Play Count Scraper](https://apify.com/publicrecords/spotify-play-count-scraper) - Play counts for every track on a Spotify track, album, artist or playlist link, plus monthly listeners (Apify Actor, API + MCP).

## Contributing

Contributions are welcome. Start with [CONTRIBUTING.md](CONTRIBUTING.md), which has the full guide. Before opening a pull request:

1. Confirm the resource is real, relevant, actively maintained, and not already listed.
2. Use the required list format: `![github](image/alg_R.png) [Resource Name](url) - Concise 1-sentence description of what it automates.` (or the `web` icon for websites).
3. Add the entry to the most relevant section, keeping alphabetical or logical grouping within that section.
4. Keep descriptions factual and focused on the automation value, not marketing language.
5. Run the local checker: `python3 scripts/check_readme.py`.

## License

Released under [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/). To the extent possible under law, the author(s) have waived all copyright and related rights to this work.

[![CC0](https://img.shields.io/badge/CC0-1.0-lightgrey?style=flat-square)](LICENSE)
