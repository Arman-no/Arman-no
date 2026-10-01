<p align="center">
  <img src="https://raw.githubusercontent.com/Arman-no/Arman-no/main/banner.svg" alt="Arman Nouromid — Data &amp; BI Engineer, building AI automation that ships" width="100%" />
</p>

<p align="center">
  <a href="https://armannouromid.com"><img src="https://img.shields.io/badge/Portfolio-armannouromid.com-1F6684?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/arman-nouromid"><img src="https://img.shields.io/badge/LinkedIn-arman--nouromid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nouromidarman@gmail.com"><img src="https://img.shields.io/badge/Email-nouromidarman-4A5463?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### What I do

Data & BI engineer by trade — Data Vault 2.0, SQL Server, SSIS/BIML, Power BI, Azure Fabric & Synapse. Full case studies and work history are on the [portfolio site](https://armannouromid.com), evidence-linked to real projects rather than just a skills list.

Outside that, I build AI automation end to end: multi-agent Claude Code systems, a self-maintaining Obsidian "second brain" that several of my own agents read and write to, and finance/trading and content-automation agents with real safety layers (kill switches, position/risk caps) rather than letting a model act unchecked.

### Recent contribution

Filed and fixed a real bug in [obsidian-second-brain](https://github.com/eugeniughelbur/obsidian-second-brain) (a Claude Code skill with 1,000+ stars for giving agents persistent memory via an Obsidian vault): its SessionStart hook silently never loaded the vault's own operating rules, because it only checked an environment variable that a standard install never actually sets. Root-caused, fixed, and opened as [PR #288](https://github.com/eugeniughelbur/obsidian-second-brain/pull/288).

### Projects

| | |
|---|---|
| [**ResumerAgent**](https://github.com/Arman-no/ResumerAgent) · [site](https://resumeragent.armannouromid.com) | Local dashboard that finds every Claude Code session, including the dead ones `claude agents` can't list, and resumes any of them in one click. Node.js, zero runtime dependencies, CI on Windows/macOS/Linux, MIT. |
| [**web-scraping-toolkit**](https://github.com/Arman-no/web-scraping-toolkit) | Two self-contained Python CLIs for pages a plain request can't read: a stealth-browser fetcher (Scrapling) returning markdown from bot-walled and JS-rendered pages, and a local Instagram-reel transcriber (faster-whisper, CPU only). Registered as a Claude Code skill. |
| [**Moonshine Jewellery**](https://moonshinejewellery.de) | E-commerce platform moving a handmade jewellery business off a marketplace onto its own checkout: Medusa v2 backend, Next.js storefront, Postgres, Redis, Stripe, Etsy sync. Live. |
| [**armannouromid.com**](https://armannouromid.com) | Portfolio with evidence-linked case studies from the data-warehouse work and the side projects above. |

### Stack

`SQL Server` `T-SQL` `SSIS` `BIML` `Power BI` `DAX` `Azure Fabric & Synapse` — `Python` `TypeScript` `Claude Code` `Obsidian` `MCP`
