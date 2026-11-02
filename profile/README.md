<p align="center">
  <a href="https://github.com/SoCloseSociety">
    <img src="https://raw.githubusercontent.com/SoCloseSociety/.github/main/assets/org-banner.svg" alt="SoClose Society banner -- Digital Innovation Through Automation and AI: free open-source tools for automation, live data, AI agents and markets" width="900">
  </a>
</p>

<p align="center">
  <strong>Free, open-source tools for live public data, automation, markets and developers.</strong>
  <br>
  <sub>Every tool on this page was cloned, installed and checked on 2 November 2026 -- the status next to each one says exactly what was verified.</sub>
</p>

<p align="center">
  <a href="https://soclose.co">Website</a> &bull;
  <a href="https://github.com/SoCloseSociety">GitHub</a> &bull;
  <a href="https://x.com/socloseagency">X / Twitter</a> &bull;
  <a href="https://www.youtube.com/@socloseagency/">YouTube</a> &bull;
  <a href="mailto:contact@soclose.co">Contact</a>
</p>

<p align="center">
  <a href="https://github.com/SoCloseSociety"><img src="https://img.shields.io/github/followers/SoCloseSociety?style=flat-square&color=ec4899&labelColor=0D0D0D&logo=github&logoColor=white&label=Followers" alt="GitHub organization followers"></a>
  <a href="https://github.com/orgs/SoCloseSociety/repositories?q=sort%3Astars"><img src="https://img.shields.io/github/stars/SoCloseSociety?style=flat-square&color=ec4899&labelColor=0D0D0D&logo=github&logoColor=white&label=Total%20Stars" alt="Total GitHub stars across all SoClose Society repositories"></a>
  <a href="#all-tools"><img src="https://img.shields.io/badge/Open--Source_Tools-26-ec4899?style=flat-square&labelColor=0D0D0D" alt="26 free open-source tools"></a>
  <a href="#verified-working"><img src="https://img.shields.io/badge/Live_demos-3-ec4899?style=flat-square&labelColor=0D0D0D" alt="3 live public demos"></a>
  <a href="https://github.com/orgs/SoCloseSociety/repositories"><img src="https://img.shields.io/badge/License-MIT-ec4899?style=flat-square&labelColor=0D0D0D" alt="MIT license"></a>
  <img src="https://komarev.com/ghpvc/?username=SoCloseSociety&color=ec4899&style=flat-square&label=Profile+Views" alt="Profile views counter">
</p>

<br>

<p align="center">
  <a href="https://github.com/orgs/SoCloseSociety/repositories?q=sort%3Astars">
    <img src="https://raw.githubusercontent.com/SoCloseSociety/.github/main/assets/cta-star.svg" alt="Star our repositories -- every star helps these free tools reach more people" height="56">
  </a>
  &nbsp;
  <a href="https://github.com/SoCloseSociety">
    <img src="https://raw.githubusercontent.com/SoCloseSociety/.github/main/assets/cta-follow.svg" alt="Follow SoClose Society on GitHub to get new tools first" height="56">
  </a>
  &nbsp;
  <a href="https://github.com/search?q=org%3ASoCloseSociety+is%3Aissue+is%3Aopen&type=issues">
    <img src="https://raw.githubusercontent.com/SoCloseSociety/.github/main/assets/cta-contribute.svg" alt="Contribute -- fork a repo, open a pull request" height="56">
  </a>
</p>

<p align="center">
  <sub>⭐ <strong>Everything here is free.</strong> If a tool saves you time, a star is the best way to say thanks -- it helps others find it too.</sub>
</p>

---

### What we build

Open-source tools that save hours of manual work, in Python and TypeScript, MIT-licensed, self-hostable.

- 🌍 **Live public data** -- earthquakes, tsunamis and disasters from official agencies, El Nino / ENSO, public cameras
- 📺 **Self-hosted apps** -- free live TV and radio, media ingestion, a Mac cleaner and monitor, FPV drone tooling
- 📈 **Markets & crypto** -- a Bloomberg-style trading terminal, Solana anti-rug and whale trackers
- 🕷️ **Data extraction** -- Google Maps, LinkedIn, Meta Ads and more, to CSV / Excel
- 📣 **Social automation & AI agents** -- Pinterest, Instagram, X, Facebook, Telegram, and an LLM growth agent

**How to read the status column** -- we would rather tell you than let you find out:

| | Status | What it means |
|---|---|---|
| 🌐 | **Live** | A public demo answers today -- try it before you clone. |
| ✅ | **Tested** | Its own test suite or build passes on a fresh clone. |
| 🔌 | **Your account** | Installs and compiles cleanly, then runs against a site, API key or bot token of yours. We can't test that part for you, and sites change their pages: selector fixes are the most welcome PRs. |

---

<a id="verified-working"></a>

### ✅ Verified working

<table>
<tr>
<td width="100%" align="center">

**[SOSForge](https://github.com/SoCloseSociety/SOSForge)** -- **Real-time earthquake, tsunami & disaster tracker -- 33 official sources in one live feed** &nbsp; 🌐 ✅

[![GitHub stars for SOSForge](https://img.shields.io/github/stars/SoCloseSociety/SOSForge?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/SOSForge)
[![Live site](https://img.shields.io/badge/live-sosforge.soclose.co-ec4899?style=flat-square&labelColor=0D0D0D)](https://sosforge.soclose.co)
[![No API key](https://img.shields.io/badge/API_keys-none_needed-ec4899?style=flat-square&labelColor=0D0D0D)](https://github.com/SoCloseSociety/SOSForge)

<a href="https://sosforge.soclose.co"><img src="https://raw.githubusercontent.com/SoCloseSociety/SOSForge/main/docs/screenshot.png" alt="SOSForge live map: earthquakes, heat and storm alerts worldwide, with the health of every source along the bottom" width="720"></a>

Thirty-three official feeds -- EMSC, USGS, NOAA, GDACS, JMA, BMKG, GeoNet, INGV, AFAD, GEOFON, NASA EONET, Meteoalarm, WMO and more -- merged into **one normalized stream** pushed to the browser over a websocket with a one-second heartbeat. Includes **Japan's earthquake early warning** and draws the **P and S wave fronts** live on the map. Built on one rule: **the feed never lies about its own freshness** -- every source shows its real health, and a partial outage degrades instead of going dark.

**33 sources** · **5 languages** · **Websocket live feed** · **P/S wave propagation** · **Cross-source dedup** · **1,900+ tests** · **Zero API keys**

**[Open the live map →](https://sosforge.soclose.co)** · **[View the repo →](https://github.com/SoCloseSociety/SOSForge)** · **[⭐ Star it](https://github.com/SoCloseSociety/SOSForge)**

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" align="center">

**[elnino-watch](https://github.com/SoCloseSociety/elnino-watch)** -- **Live El Nino (ENSO) tracker with an explainable risk watch for Koh Samui -- 85 free public sources** &nbsp; 🌐 ✅

[![GitHub stars for elnino-watch](https://img.shields.io/github/stars/SoCloseSociety/elnino-watch?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/elnino-watch)
[![Live site](https://img.shields.io/badge/live-elnino.soclose.co-ec4899?style=flat-square&labelColor=0D0D0D)](https://elnino.soclose.co)
[![No API key](https://img.shields.io/badge/API_keys-none_needed-ec4899?style=flat-square&labelColor=0D0D0D)](https://github.com/SoCloseSociety/elnino-watch)

<a href="https://elnino.soclose.co"><img src="https://raw.githubusercontent.com/SoCloseSociety/elnino-watch/main/docs/screenshots/overview.png" alt="El Nino Watch overview: live briefing, official NOAA CPC status, ONI and weekly Nino 3.4 with dates and sources" width="720"></a>

Follows the 2026-27 El Nino live from **NOAA, NASA, BoM, JMA, IRI, WMO, Copernicus, Open-Meteo, GDACS and the Thai agencies**, draws 22 satellite layers on a MapLibre map, and turns the local signals into a **five-level risk watch for Koh Samui** where every factor shows its value, threshold, source and explanation. Built on one rule: **never fabricate data** -- a stale or missing source is shown as such, and the level becomes "unknown", never "safe".

**85 sources** · **22 satellite layers** · **5-level explainable risk engine** · **240 help topics** · **470+ tests** · **Zero API keys**

**[Open the live site →](https://elnino.soclose.co)** · **[View the repo →](https://github.com/SoCloseSociety/elnino-watch)** · **[⭐ Star it](https://github.com/SoCloseSociety/elnino-watch)**

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" align="center" valign="top">

**[neowatch](https://github.com/SoCloseSociety/neowatch)** &nbsp; 🌐 ✅

[![GitHub stars for neowatch](https://img.shields.io/github/stars/SoCloseSociety/neowatch?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/neowatch)
[![Live demo](https://img.shields.io/badge/live-neowatch.soclose.co-ec4899?style=flat-square&labelColor=0D0D0D)](https://neowatch.soclose.co)

📺 About **12,000 freely published live TV channels**, internet radio and public-domain films in one fast player: 9-screen mosaic, TV guide, D-pad remote UX. React PWA + Node, hosts no content, self-hostable.

**[Try it live →](https://neowatch.soclose.co)**

</td>
<td width="50%" align="center" valign="top">

**[AegisForge](https://github.com/SoCloseSociety/AegisForge)** &nbsp; ✅

[![GitHub stars for AegisForge](https://img.shields.io/github/stars/SoCloseSociety/AegisForge?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/AegisForge)
[![Tests](https://img.shields.io/badge/tests-775_passing-ec4899?style=flat-square&labelColor=0D0D0D)](https://github.com/SoCloseSociety/AegisForge)

🛡️ A free, private **Mac cleaner & system monitor for developers** -- live TUI, node_modules / Docker / cache cleanup, security scan. macOS-first, 100% local, zero telemetry. One command to try it:

`uvx --from git+https://github.com/SoCloseSociety/AegisForge aegis gc --scan`

</td>
</tr>
</table>

| Tool | What it does | Status | |
|------|--------------|:---:|---|
| **[camforge](https://github.com/SoCloseSociety/camforge)** | Self-hosted world map of 7,000+ public traffic, weather and webcam feeds, relayed through your own media server, with a local AI vision relay (Ollama) | ✅ | [![GitHub stars for camforge](https://img.shields.io/github/stars/SoCloseSociety/camforge?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/camforge) |
| **[meta-ads-extractor](https://github.com/SoCloseSociety/meta-ads-extractor)** | Export your Meta Ads campaigns, insights, creatives and leads to Excel through the official Graph API | ✅ | [![GitHub stars for meta-ads-extractor](https://img.shields.io/github/stars/SoCloseSociety/meta-ads-extractor?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/meta-ads-extractor) |
| **[radiomaster](https://github.com/SoCloseSociety/radiomaster)** | FPV dashboard -- auto-detect and configure RadioMaster radios, Betaflight flight controllers and ELRS | ✅ | [![GitHub stars for radiomaster](https://img.shields.io/github/stars/SoCloseSociety/radiomaster?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/radiomaster) |
| **[kontentmanager](https://github.com/SoCloseSociety/kontentmanager)** | Local-first media ingestion for macOS -- offload SD / USB / SSD cards cleanly, no cloud | ✅ | [![GitHub stars for kontentmanager](https://img.shields.io/github/stars/SoCloseSociety/kontentmanager?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/kontentmanager) |
| **[ClickGenerator](https://github.com/SoCloseSociety/ClickGenerator)** | Load testing, synthetic monitoring, SEO and accessibility audits, Playwright-powered | ✅ | [![GitHub stars for ClickGenerator](https://img.shields.io/github/stars/SoCloseSociety/ClickGenerator?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/ClickGenerator) |

---

### 🏆 Most popular -- what the community stars and visits the most

<p align="center"><sub>Ranked by stars, then by unique visitors over the last 14 days. <strong>Use one? Star it ⭐</strong></sub></p>

| # | Project | Why people use it | Status | ⭐ |
|---|---------|-------------------|:---:|---|
| 🥇 | **[MiloAgent](https://github.com/SoCloseSociety/MiloAgent)** | Self-learning AI growth agent for Reddit, X & Telegram -- needs your own Reddit API app | 🔌 | [![GitHub stars for MiloAgent](https://img.shields.io/github/stars/SoCloseSociety/MiloAgent?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/MiloAgent) |
| 🥈 | **[PinterestBulkPostBot](https://github.com/SoCloseSociety/PinterestBulkPostBot)** | Bulk-post to Pinterest: schedule pins, manage boards, CSV import | 🔌 | [![GitHub stars for PinterestBulkPostBot](https://img.shields.io/github/stars/SoCloseSociety/PinterestBulkPostBot?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/PinterestBulkPostBot) |
| 🥉 | **[TradeBobbyTerminal](https://github.com/SoCloseSociety/TradeBobbyTerminal)** | Self-hosted Bloomberg-style ICT/SMC trading terminal -- 41 panels on free market data | 🔌 | [![GitHub stars for TradeBobbyTerminal](https://img.shields.io/github/stars/SoCloseSociety/TradeBobbyTerminal?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/TradeBobbyTerminal) |
| 4 | **[GoogleMapScraper](https://github.com/SoCloseSociety/GoogleMapScraper)** | Business leads from Google Maps -- names, phones, websites, hours | 🔌 | [![GitHub stars for GoogleMapScraper](https://img.shields.io/github/stars/SoCloseSociety/GoogleMapScraper?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/GoogleMapScraper) |
| 5 | **[InstagramMpBulkSender](https://github.com/SoCloseSociety/InstagramMpBulkSender)** | Bulk Instagram DMs with progress tracking and human-like delays | 🔌 | [![GitHub stars for InstagramMpBulkSender](https://img.shields.io/github/stars/SoCloseSociety/InstagramMpBulkSender?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/InstagramMpBulkSender) |
| 6 | **[camforge](https://github.com/SoCloseSociety/camforge)** | Live world map of public cameras with a local AI vision relay | ✅ | [![GitHub stars for camforge](https://img.shields.io/github/stars/SoCloseSociety/camforge?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/camforge) |
| 7 | **[neowatch](https://github.com/SoCloseSociety/neowatch)** | Free live TV, radio and films in one self-hosted app | 🌐 ✅ | [![GitHub stars for neowatch](https://img.shields.io/github/stars/SoCloseSociety/neowatch?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/neowatch) |
| 8 | **[FacebookInviteFriendToGroup](https://github.com/SoCloseSociety/FacebookInviteFriendToGroup)** | Bulk-invite Facebook friends to a group with smart delays | 🔌 | [![GitHub stars for FacebookInviteFriendToGroup](https://img.shields.io/github/stars/SoCloseSociety/FacebookInviteFriendToGroup?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/FacebookInviteFriendToGroup) |

---

<a id="all-tools"></a>

### All tools

<p align="center"><sub>26 free, open-source tools -- <strong>star the ones you use</strong> so more people discover them ⭐</sub></p>

#### 🌍 Live public data & self-hosted apps

| Tool | Description | Status | |
|------|-------------|:---:|---|
| **[SOSForge](https://github.com/SoCloseSociety/SOSForge)** | Real-time earthquake, tsunami & disaster tracker -- 33 official sources, websocket feed, P/S wave fronts, [live map](https://sosforge.soclose.co) | 🌐 ✅ | [![GitHub stars for SOSForge](https://img.shields.io/github/stars/SoCloseSociety/SOSForge?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/SOSForge) |
| **[elnino-watch](https://github.com/SoCloseSociety/elnino-watch)** | Live El Nino / ENSO tracker with an explainable risk watch -- 85 free sources, 22 satellite layers, [live site](https://elnino.soclose.co) | 🌐 ✅ | [![GitHub stars for elnino-watch](https://img.shields.io/github/stars/SoCloseSociety/elnino-watch?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/elnino-watch) |
| **[neowatch](https://github.com/SoCloseSociety/neowatch)** | Self-hostable free live TV, radio & film aggregator -- React PWA, HLS, EPG, TV UX, [live demo](https://neowatch.soclose.co) | 🌐 ✅ | [![GitHub stars for neowatch](https://img.shields.io/github/stars/SoCloseSociety/neowatch?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/neowatch) |
| **[camforge](https://github.com/SoCloseSociety/camforge)** | Self-hosted global map of public cameras with live relay and a local AI vision relay | ✅ | [![GitHub stars for camforge](https://img.shields.io/github/stars/SoCloseSociety/camforge?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/camforge) |
| **[kontentmanager](https://github.com/SoCloseSociety/kontentmanager)** | Local-first media ingestion for macOS -- offload SD / USB / SSD cards cleanly, no cloud | ✅ | [![GitHub stars for kontentmanager](https://img.shields.io/github/stars/SoCloseSociety/kontentmanager?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/kontentmanager) |

#### 🖥️ Developer tools

| Tool | Description | Status | |
|------|-------------|:---:|---|
| **[AegisForge](https://github.com/SoCloseSociety/AegisForge)** | Mac cleaner & system monitor CLI for developers -- live TUI, cache / Docker / node_modules cleanup, 100% local | ✅ | [![GitHub stars for AegisForge](https://img.shields.io/github/stars/SoCloseSociety/AegisForge?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/AegisForge) |
| **[ClickGenerator](https://github.com/SoCloseSociety/ClickGenerator)** | Load testing, synthetic monitoring, SEO & accessibility audits -- Playwright-powered | ✅ | [![GitHub stars for ClickGenerator](https://img.shields.io/github/stars/SoCloseSociety/ClickGenerator?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/ClickGenerator) |
| **[radiomaster](https://github.com/SoCloseSociety/radiomaster)** | FPV drone dashboard -- auto-detect, configure and manage RadioMaster radios, Betaflight FCs and ELRS | ✅ | [![GitHub stars for radiomaster](https://img.shields.io/github/stars/SoCloseSociety/radiomaster?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/radiomaster) |
| **[claude-code-template](https://github.com/SoCloseSociety/claude-code-template)** | Claude Code project template for AI-assisted development | 📄 | [![GitHub stars for claude-code-template](https://img.shields.io/github/stars/SoCloseSociety/claude-code-template?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/claude-code-template) |

#### 📈 Markets & crypto

| Tool | Description | Status | |
|------|-------------|:---:|---|
| **[TradeBobbyTerminal](https://github.com/SoCloseSociety/TradeBobbyTerminal)** | Bloomberg-style ICT/SMC trading terminal -- 41 panels, 15+ free data sources, Pine V6 indicator | 🔌 | [![GitHub stars for TradeBobbyTerminal](https://img.shields.io/github/stars/SoCloseSociety/TradeBobbyTerminal?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/TradeBobbyTerminal) |
| **[RugscoreBotTG](https://github.com/SoCloseSociety/RugscoreBotTG)** | Solana anti-rug scanner -- 8-criteria scoring, Telegram bot, real-time on-chain data | 🔌 | [![GitHub stars for RugscoreBotTG](https://img.shields.io/github/stars/SoCloseSociety/RugscoreBotTG?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/RugscoreBotTG) |
| **[WhalegodTG](https://github.com/SoCloseSociety/WhalegodTG)** | On-chain whale tracker for Solana & Ethereum -- 14 categories, labeled wallets, Telegram alerts | 🔌 | [![GitHub stars for WhalegodTG](https://img.shields.io/github/stars/SoCloseSociety/WhalegodTG?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/WhalegodTG) |

#### 🕷️ Data extraction

| Tool | Description | Status | |
|------|-------------|:---:|---|
| **[meta-ads-extractor](https://github.com/SoCloseSociety/meta-ads-extractor)** | Export your Meta Ads campaigns, insights, creatives and leads to Excel -- official Graph API | ✅ | [![GitHub stars for meta-ads-extractor](https://img.shields.io/github/stars/SoCloseSociety/meta-ads-extractor?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/meta-ads-extractor) |
| **[GoogleMapScraper](https://github.com/SoCloseSociety/GoogleMapScraper)** | Extract business data from Google Maps | 🔌 | [![GitHub stars for GoogleMapScraper](https://img.shields.io/github/stars/SoCloseSociety/GoogleMapScraper?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/GoogleMapScraper) |
| **[LinkedinDataScraper](https://github.com/SoCloseSociety/LinkedinDataScraper)** | LinkedIn profile data at scale, Playwright + Streamlit UI | 🔌 | [![GitHub stars for LinkedinDataScraper](https://img.shields.io/github/stars/SoCloseSociety/LinkedinDataScraper?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/LinkedinDataScraper) |
| **[TwitterDataScraper](https://github.com/SoCloseSociety/TwitterDataScraper)** | Twitter / X profile data with dedup | 🔌 | [![GitHub stars for TwitterDataScraper](https://img.shields.io/github/stars/SoCloseSociety/TwitterDataScraper?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/TwitterDataScraper) |
| **[InstagramDataScraper](https://github.com/SoCloseSociety/InstagramDataScraper)** | Instagram profile URLs at scale -- auto-scroll, filtering, dedup | 🔌 | [![GitHub stars for InstagramDataScraper](https://img.shields.io/github/stars/SoCloseSociety/InstagramDataScraper?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/InstagramDataScraper) |
| **[FreeWorkDataScraper](https://github.com/SoCloseSociety/FreeWorkDataScraper)** | Freelancer profiles from Free-Work -- 18 fields, Streamlit UI, Excel export | 🔌 | [![GitHub stars for FreeWorkDataScraper](https://img.shields.io/github/stars/SoCloseSociety/FreeWorkDataScraper?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/FreeWorkDataScraper) |
| **[DoctolibDataScraper](https://github.com/SoCloseSociety/DoctolibDataScraper)** | Doctor listings from Doctolib.fr | 🔌 | [![GitHub stars for DoctolibDataScraper](https://img.shields.io/github/stars/SoCloseSociety/DoctolibDataScraper?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/DoctolibDataScraper) |

#### 📣 Social automation & AI agents

| Tool | Description | Status | |
|------|-------------|:---:|---|
| **[MiloAgent](https://github.com/SoCloseSociety/MiloAgent)** | Self-learning AI growth agent -- Reddit expert, expanding to X & Telegram; runs on your own Reddit API app | 🔌 | [![GitHub stars for MiloAgent](https://img.shields.io/github/stars/SoCloseSociety/MiloAgent?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/MiloAgent) |
| **[PinterestBulkPostBot](https://github.com/SoCloseSociety/PinterestBulkPostBot)** | Bulk posting on Pinterest | 🔌 | [![GitHub stars for PinterestBulkPostBot](https://img.shields.io/github/stars/SoCloseSociety/PinterestBulkPostBot?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/PinterestBulkPostBot) |
| **[InstagramMpBulkSender](https://github.com/SoCloseSociety/InstagramMpBulkSender)** | Bulk DMs on Instagram | 🔌 | [![GitHub stars for InstagramMpBulkSender](https://img.shields.io/github/stars/SoCloseSociety/InstagramMpBulkSender?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/InstagramMpBulkSender) |
| **[TwitterMpBulkSender](https://github.com/SoCloseSociety/TwitterMpBulkSender)** | Bulk DMs on X / Twitter with retry logic and rate limiting | 🔌 | [![GitHub stars for TwitterMpBulkSender](https://img.shields.io/github/stars/SoCloseSociety/TwitterMpBulkSender?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/TwitterMpBulkSender) |
| **[FacebookInviteFriendToGroup](https://github.com/SoCloseSociety/FacebookInviteFriendToGroup)** | Bulk-invite friends to Facebook groups | 🔌 | [![GitHub stars for FacebookInviteFriendToGroup](https://img.shields.io/github/stars/SoCloseSociety/FacebookInviteFriendToGroup?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/FacebookInviteFriendToGroup) |
| **[Telegram_ScrappingAdding_toGroup](https://github.com/SoCloseSociety/Telegram_ScrappingAdding_toGroup)** | Telegram group toolkit -- scrape a group's members and add them to yours with multi-account rotation | 🔌 | [![GitHub stars for Telegram_ScrappingAdding_toGroup](https://img.shields.io/github/stars/SoCloseSociety/Telegram_ScrappingAdding_toGroup?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/Telegram_ScrappingAdding_toGroup) |
| **[FrFollowForFollowBot](https://github.com/SoCloseSociety/FrFollowForFollowBot)** | Gamified Telegram follow-for-follow bot for Instagram (French) | 🔌 | [![GitHub stars for FrFollowForFollowBot](https://img.shields.io/github/stars/SoCloseSociety/FrFollowForFollowBot?style=flat-square&color=ec4899&labelColor=0D0D0D)](https://github.com/SoCloseSociety/FrFollowForFollowBot) |

<p align="center"><sub>Can't pick just one? <a href="https://github.com/orgs/SoCloseSociety/repositories?q=sort%3Astars"><strong>Browse them all sorted by stars →</strong></a></sub></p>

---

### 📈 Star History

<p align="center">
  <a href="https://star-history.com/#SoCloseSociety/MiloAgent&SoCloseSociety/PinterestBulkPostBot&SoCloseSociety/TradeBobbyTerminal&SoCloseSociety/GoogleMapScraper&SoCloseSociety/neowatch&SoCloseSociety/camforge&Date">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=SoCloseSociety/MiloAgent,SoCloseSociety/PinterestBulkPostBot,SoCloseSociety/TradeBobbyTerminal,SoCloseSociety/GoogleMapScraper,SoCloseSociety/neowatch,SoCloseSociety/camforge&type=Date&theme=dark">
      <img src="https://api.star-history.com/svg?repos=SoCloseSociety/MiloAgent,SoCloseSociety/PinterestBulkPostBot,SoCloseSociety/TradeBobbyTerminal,SoCloseSociety/GoogleMapScraper,SoCloseSociety/neowatch,SoCloseSociety/camforge&type=Date" alt="Star history chart of SoClose Society's most popular open-source repositories" width="720">
    </picture>
  </a>
</p>

<p align="center"><sub>Help the curves go up -- <a href="https://github.com/orgs/SoCloseSociety/repositories?q=sort%3Astars"><strong>⭐ star a repo</strong></a></sub></p>

---

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-ec4899?style=flat-square&logo=python&logoColor=white&labelColor=0D0D0D" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-ec4899?style=flat-square&logo=typescript&logoColor=white&labelColor=0D0D0D" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-ec4899?style=flat-square&logo=react&logoColor=white&labelColor=0D0D0D" alt="React">
  <img src="https://img.shields.io/badge/FastAPI-ec4899?style=flat-square&logo=fastapi&logoColor=white&labelColor=0D0D0D" alt="FastAPI">
  <img src="https://img.shields.io/badge/Next.js-ec4899?style=flat-square&logo=nextdotjs&logoColor=white&labelColor=0D0D0D" alt="Next.js">
  <img src="https://img.shields.io/badge/Playwright-ec4899?style=flat-square&labelColor=0D0D0D" alt="Playwright">
  <img src="https://img.shields.io/badge/Selenium-ec4899?style=flat-square&logo=selenium&logoColor=white&labelColor=0D0D0D" alt="Selenium">
  <img src="https://img.shields.io/badge/Streamlit-ec4899?style=flat-square&logo=streamlit&logoColor=white&labelColor=0D0D0D" alt="Streamlit">
  <img src="https://img.shields.io/badge/Telegram_Bot-ec4899?style=flat-square&logo=telegram&logoColor=white&labelColor=0D0D0D" alt="Telegram Bot">
  <img src="https://img.shields.io/badge/Docker-ec4899?style=flat-square&logo=docker&logoColor=white&labelColor=0D0D0D" alt="Docker">
  <img src="https://img.shields.io/badge/MapLibre-ec4899?style=flat-square&logo=maplibre&logoColor=white&labelColor=0D0D0D" alt="MapLibre GL">
  <img src="https://img.shields.io/badge/Ollama-ec4899?style=flat-square&logo=ollama&logoColor=white&labelColor=0D0D0D" alt="Ollama">
  <img src="https://img.shields.io/badge/Solana-ec4899?style=flat-square&logo=solana&logoColor=white&labelColor=0D0D0D" alt="Solana">
</p>

---

### 🤝 Contributing & Support

All our tools are MIT-licensed and welcome contributions. Check each repo's `CONTRIBUTING.md` for guidelines.

**Three ways to support us -- the first two take 10 seconds:**

1. **⭐ Star** the repos you use -- [browse them all](https://github.com/orgs/SoCloseSociety/repositories?q=sort%3Astars). Stars are how GitHub ranks projects: every single one makes these free tools visible to more people.
2. **👀 Follow [@SoCloseSociety](https://github.com/SoCloseSociety)** -- be the first to know when we ship a new tool (we ship often).
3. **🍴 Fork & contribute** -- the most useful PR is often the smallest: a 🔌 tool whose target site changed its pages needs a selector update, and you are the one who just saw it break. Pick an [open issue](https://github.com/search?q=org%3ASoCloseSociety+is%3Aissue+is%3Aopen&type=issues) or open one -- first PR? We're friendly reviewers.

Found a bug or want a feature? [Open an issue](https://github.com/search?q=org%3ASoCloseSociety+is%3Aissue+is%3Aopen&type=issues) on the relevant repo -- we read everything.

---

<p align="center">
  <a href="https://github.com/orgs/SoCloseSociety/repositories?q=sort%3Astars">
    <img src="https://raw.githubusercontent.com/SoCloseSociety/.github/main/assets/cta-star.svg" alt="Star our repositories on GitHub" height="56">
  </a>
</p>

<p align="center">
  <sub>Built with purpose by <strong>SoClose</strong> -- Digital Innovation Through Automation & AI</sub>
  <br>
  <sub><a href="https://soclose.co">soclose.co</a> · <a href="https://x.com/socloseagency">@socloseagency</a> · <a href="mailto:contact@soclose.co">contact@soclose.co</a></sub>
</p>
