<p align="center">
  <img src="assets/hero.svg" alt="Arman Nouromid — Data &amp; BI Engineer, building AI automation that ships" width="100%" />
</p>

<p align="center">
  <a href="https://armannouromid.com"><img src="assets/badges.svg" height="32" alt="Data Vault 2.0 · Business Intelligence · AI Agents · Automation" /></a>
</p>

<p align="center">
  <a href="https://armannouromid.com"><img src="https://img.shields.io/badge/Portfolio-armannouromid.com-1F6684?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/arman-nouromid"><img src="https://img.shields.io/badge/LinkedIn-arman--nouromid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nouromidarman@gmail.com"><img src="https://img.shields.io/badge/Email-nouromidarman-4A5463?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="assets/glance.svg" width="100%" alt="At a glance: data warehouse (Data Vault 2.0, SQL Server, SSIS, BIML), business intelligence (Power BI, DAX, Azure Fabric and Synapse), AI agents (multi-agent Claude Code, MCP, Obsidian vault as memory), automation with kill switches and risk caps" />
</p>

# Arman Nouromid · Data, BI & AI automation

Data & BI engineer by trade: Data Vault 2.0, SQL Server, SSIS/BIML, Power BI, Azure Fabric & Synapse. Outside that, I build AI automation end to end: multi-agent Claude Code systems, a self-maintaining Obsidian "second brain" that several of my own agents read and write to, and finance/trading and content-automation agents with real safety layers (kill switches, position/risk caps) rather than letting a model act unchecked. Case studies are on the [portfolio site](https://armannouromid.com), evidence-linked to real projects rather than just a skills list.

<details>
<summary><strong>Start here</strong></summary>

> [!TIP]
> **Hiring for data warehousing or BI?** The [portfolio](https://armannouromid.com) has the case studies, each linked to its evidence.

> [!TIP]
> **Lost a Claude Code session?** [ResumerAgent](https://github.com/Arman-no/ResumerAgent) lists every session on your machine, including the dead ones, and resumes any of them in one click.

> [!TIP]
> **Page blocked by a bot wall?** [web-scraping-toolkit](https://github.com/Arman-no/web-scraping-toolkit) fetches it as markdown through a stealth browser, and doubles as a Claude Code skill.

</details>

> **October 2026:** ResumerAgent gained a cost / context / limit table, a portable statusline sidecar (`npm run setup-statusline`) and safety hardening. Upstream, I root-caused and fixed a bug in [obsidian-second-brain](https://github.com/eugeniughelbur/obsidian-second-brain): its SessionStart hook never loaded the vault's operating rules ([PR #288](https://github.com/eugeniughelbur/obsidian-second-brain/pull/288)).

<p align="center">
  <a href="#what-i-do">What I do</a> ·
  <a href="#recent-contribution">Recent contribution</a> ·
  <a href="#projects">Projects</a> ·
  <a href="#stack">Stack</a>
</p>

## What I do

<img src="assets/journey.svg" width="100%" alt="Warehouse, then BI, then AI automation: store it properly, make it visible, let agents act on it" />

| Layer | In practice |
| :--- | :--- |
| **Store** | Data Vault 2.0, SQL Server, SSIS/BIML, T-SQL |
| **See** | Power BI, DAX, Azure Fabric & Synapse |
| **Act** | Multi-agent Claude Code systems, an Obsidian vault as shared memory, agents with kill switches and position/risk caps |

## Recent contribution

Filed and fixed a real bug in [obsidian-second-brain](https://github.com/eugeniughelbur/obsidian-second-brain) (a Claude Code skill with 1,000+ stars for giving agents persistent memory via an Obsidian vault): its SessionStart hook silently never loaded the vault's own operating rules, because it only checked an environment variable that a standard install never actually sets. Root-caused, fixed, and opened as [PR #288](https://github.com/eugeniughelbur/obsidian-second-brain/pull/288).

## Projects

<img src="assets/header-projects.svg" width="100%" alt="Things I've shipped: developer tools, a live shop and the portfolio" />

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Arman-no/ResumerAgent"><img src="assets/project-resumeragent.svg" width="400" alt="ResumerAgent: finds every Claude Code session, even the dead ones, and resumes any in one click. Explore the repository." /></a><br />
<a href="https://github.com/Arman-no/ResumerAgent"><img src="https://img.shields.io/github/stars/Arman-no/ResumerAgent?style=flat-square&color=0d9488" alt="GitHub stars of ResumerAgent" /></a>
<a href="https://github.com/Arman-no/ResumerAgent/commits"><img src="https://img.shields.io/github/last-commit/Arman-no/ResumerAgent?style=flat-square&color=0d9488" alt="Last commit to ResumerAgent" /></a>
<a href="https://resumeragent.armannouromid.com">site</a>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Arman-no/web-scraping-toolkit"><img src="assets/project-web-scraping-toolkit.svg" width="400" alt="web-scraping-toolkit: stealth-browser fetch to markdown for bot-walled pages, and local Instagram-reel transcripts. Explore the repository." /></a><br />
<a href="https://github.com/Arman-no/web-scraping-toolkit/commits"><img src="https://img.shields.io/github/last-commit/Arman-no/web-scraping-toolkit?style=flat-square&color=d97706" alt="Last commit to web-scraping-toolkit" /></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://moonshinejewellery.de"><img src="assets/project-moonshine.svg" width="400" alt="Moonshine Jewellery: own checkout for a handmade jewellery business, synced with its Etsy shop. Visit the shop." /></a><br />
<a href="https://moonshinejewellery.de"><img src="https://img.shields.io/website?url=https%3A%2F%2Fmoonshinejewellery.de&style=flat-square&label=moonshinejewellery.de" alt="Live status of moonshinejewellery.de" /></a>
</td>
<td width="50%" valign="top">
<a href="https://armannouromid.com"><img src="assets/project-portfolio.svg" width="400" alt="armannouromid.com: case studies from the data-warehouse work and side projects, evidence-linked. Visit the portfolio." /></a><br />
<a href="https://armannouromid.com"><img src="https://img.shields.io/website?url=https%3A%2F%2Farmannouromid.com&style=flat-square&label=armannouromid.com" alt="Live status of armannouromid.com" /></a>
</td>
</tr>
</table>

## Stack

<p align="center">
  <a href="https://armannouromid.com" title="Data warehousing"><img src="assets/icon-warehouse.svg" width="56" height="56" alt="Data warehousing" /></a>
  <a href="https://armannouromid.com" title="Business intelligence"><img src="assets/icon-bi.svg" width="56" height="56" alt="Business intelligence" /></a>
  <a href="https://github.com/Arman-no/ResumerAgent" title="Agent tooling"><img src="assets/icon-agents.svg" width="56" height="56" alt="Agent tooling" /></a>
  <a href="https://github.com/Arman-no/web-scraping-toolkit" title="Web data"><img src="assets/icon-web.svg" width="56" height="56" alt="Web data" /></a>
  <a href="https://moonshinejewellery.de" title="Commerce"><img src="assets/icon-commerce.svg" width="56" height="56" alt="Commerce" /></a>
</p>

`SQL Server` `T-SQL` `SSIS` `BIML` `Power BI` `DAX` `Azure Fabric & Synapse` — `Python` `TypeScript` `Claude Code` `Obsidian` `MCP`

<details>
<summary><strong>Projects in plain text</strong></summary>

| | |
|---|---|
| [**ResumerAgent**](https://github.com/Arman-no/ResumerAgent) · [site](https://resumeragent.armannouromid.com) | Local dashboard that finds every Claude Code session, including the dead ones `claude agents` can't list, and resumes any of them in one click. Node.js, zero runtime dependencies, CI on Windows/macOS/Linux, MIT. |
| [**web-scraping-toolkit**](https://github.com/Arman-no/web-scraping-toolkit) | Two self-contained Python CLIs for pages a plain request can't read: a stealth-browser fetcher (Scrapling) returning markdown from bot-walled and JS-rendered pages, and a local Instagram-reel transcriber (faster-whisper, CPU only). Registered as a Claude Code skill. |
| [**Moonshine Jewellery**](https://moonshinejewellery.de) | E-commerce platform moving a handmade jewellery business off a marketplace onto its own checkout: Medusa v2 backend, Next.js storefront, Postgres, Redis, Stripe, Etsy sync. Live. |
| [**armannouromid.com**](https://armannouromid.com) | Portfolio with evidence-linked case studies from the data-warehouse work and the side projects above. |

</details>
