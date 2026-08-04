# Awesome-Core-Banking-Platform

## Similar Projects to Core Banking Platforms

**Core Banking Platforms** form the central system of record for banks and fintechs — managing customer accounts, deposits, loans, payments, ledgers, interest calculation, and product configuration. Leading commercial platforms include Temenos (Transact), Infosys Finacle, Mambu, Thought Machine (Vault Core), FIS Profile, Oracle FLEXCUBE, Finastra Essence, 10x Banking, Nymbus, Tuum, and SDK.finance.

Below is a **curated list** of notable platforms and their open-source equivalents. Mature, production-grade open-source core banking systems exist and are actively used, especially by microfinance institutions, digital lenders, cooperatives, and fintechs that need full code ownership.

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier / Limit | Valuation / Size |
|---|---|---|---|---|
| **[Oracle FLEXCUBE](https://www.oracle.com/industries/financial-services/flexcube/)** | Established enterprise core banking suite. | Enterprise AUM/module-based (Millions) | No free tier | $300B+ (Oracle) |
| **[Infosys Finacle](https://www.infosys.com/finacle/)** | Enterprise core banking solution used by large banks worldwide. | Multi-year contracts, module-based ($500k+) | No free tier | $70B+ (Infosys) |
| **[Temenos](https://www.temenos.com/)** (Temenos Transact) | One of the most widely deployed core banking platforms globally, covering retail, corporate, and private banking. | Enterprise licensing, high TCO | No free tier | $7B+ Market Cap |
| **[Finastra Essence](https://www.finastra.com/)** | Core banking platform within Finastra’s broader banking technology portfolio. | Custom SaaS pricing based on user base | No free tier | $5B+ Valuation |
| **[Mambu](https://www.mambu.com/)** | Cloud-native, composable core banking platform popular with neobanks, fintechs, and digital lenders. | Usage-based on active accounts (~$50k+/yr) | Dev sandbox available, no free tier | $3B+ Valuation |
| **[Thought Machine](https://www.thoughtmachine.net/)** (Vault Core) | Cloud-native core built around smart contracts for highly configurable product logic. | Usage-based with high enterprise minimums | Restricted sandbox, no free tier | $2.7B Valuation |
| **[10x Banking](https://www.10xbanking.com/)** | Cloud-native “SuperCore” platform designed for tier-1 scale and real-time operations. | Enterprise SaaS licensing (Tier-1 banks) | No free tier | ~$700M Valuation |
| **[Nymbus](https://www.nymbus.com/)** | Modern cores and banking platforms used by digital banks, fintechs, and embedded finance providers. | Custom SaaS pricing (Core vs Digital) | No free tier | ~$500M Valuation |
| **[Tuum](https://tuum.com/)** | Modern cores and banking platforms used by digital banks, fintechs, and embedded finance providers. | Modular pricing (~€5k-€10k/month base) | Dev sandbox on request, no free tier | ~$150M Valuation |
| **[SDK.finance](https://sdk.finance/)** | Modern cores and banking platforms used by digital banks, fintechs, and embedded finance providers (also offers source-code licensing options). | Starts at $900/month (SaaS) or ~$35k source | Live demo available, no free tier | ~$20M Valuation |

## 🔓 Open-Source Software

### Leading Open-Source Core Banking Systems
- **[Apache Fineract](https://fineract.apache.org/)** — The most established open-source core banking platform. Designed for digital financial services, microfinance, and inclusive banking. Supports loans, savings, shares, accounting, KYC workflows, and is actively maintained by the Apache Software Foundation. Widely deployed in production by financial institutions around the world.
- **[FinAegis](https://finaegis.org/)** / [core-banking-prototype-laravel](https://github.com/FinAegis/core-banking-prototype-laravel) — Modern open-source core banking infrastructure built with Laravel, domain-driven design, event sourcing, and CQRS. Includes dozens of bounded contexts covering accounts, payments, lending, compliance, multi-asset support, and more.
- **[OpenCBS / OpenCBS-Cloud](https://github.com/OpenCBS)** — Open-source core banking system historically popular with microfinance institutions and smaller banks. Offers client, loan, savings, and accounting management with a focus on usability and faster deployment.
- **CrystalBank** — Event-sourced open-source core banking platform emphasizing immutable audit trails, compliance workflows, and modern payment rails.

### Related Open-Source Banking & Ledger Projects
- **Project Mercury** (open-accelerators) — Reference implementation exploring modular digital bank modernization using open standards (BIAN) and open-source components.
- Open-source ledger and accounting engines (double-entry, multi-currency, event-sourced) that serve as the foundation for custom core banking builds.
- Community projects focused on deposit accounts, PSD2-style open banking interfaces, and lightweight core services.

### Typical Open-Source Approach
1. **Core system of record** — Apache Fineract or FinAegis
2. **Product configuration & APIs** — Extend via the platform’s plugin/API model or custom microservices
3. **Payments & compliance** — Integrate open-source or commercial payment rails and RegTech modules
4. **Frontend / channels** — Build or adopt open digital banking frontends on top of the core APIs
5. **Hosting** — Self-managed cloud or on-premise infrastructure for full regulatory and data control

These platforms give institutions complete ownership of the codebase, eliminate vendor lock-in on the core ledger, and are particularly attractive for microfinance, digital lenders, cooperatives, and fintechs that need transparency and customization.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to core banking, digital financial services, ledgers, or banking-as-a-service infrastructure.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open core banking infrastructure helps democratize access to modern financial technology! 🏦
