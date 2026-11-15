# Awesome Open Source & Public API Workspaces [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of top Open Source and Public API Workspace platforms — featuring SaaS & hosted commercial hubs, developer portals, API testing clients, and self-hosted open-source alternatives for publishing, discovering, testing, and collaborating on APIs and developer ecosystems.

[![Track Awesome List](https://img.shields.io/badge/Track-Awesome--List-blue.svg?style=flat-square)](https://github.com/ishandutta2007/Awesome-Open-Source-Public-API-Workspaces)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)

---

## 📋 Table of Contents

- [Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [Open-Source Software](#-open-source-software)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📈 Sector Overview & Market Dynamics

The global API management and developer platform market is estimated between **$8.8 billion and $10.5 billion**, rapidly compounding at a 16% to 34% CAGR driven by enterprise cloud migrations, API-first architecture, and AI/agentic integration. The sector is **moderately fragmented**: hyper-scale infrastructure and code hosting exhibit concentrated oligopolies with high switching costs (e.g., Microsoft GitHub, GitLab), while the API testing, developer workspace, and portal layer remains highly fragmented with intense competition between dedicated SaaS vendors and extensible open-source developer platforms.

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Open Source and Public API Workspace platforms. These are not open-source but represent benchmark developer hubs for API publishing, discovery, and collaboration. Ranked by company valuation and scale (descending).

| Platform | Company Valuation / Revenue | Starting Paid Tier Price | Free Tier Limit | Primary Capabilities & Best For |
|:---|:---|:---|:---|:---|
| **[GitHub Organizations](https://github.com)** | **$7.5B+ acquisition valuation** (Wholly-owned subsidiary of Microsoft; ~$3.2T market cap; GitHub ARR >$1B+) | **$4/user/month** (Team plan) | **Free forever**: Unlimited public/private repos, unlimited collaborators, 2,000 GitHub Actions CI/CD mins/month, 500 MB GitHub Packages storage, automated security alerts & Dependabot | Public profile READMEs, organizational code hosting, social discovery, and global developer reach |
| **[GitLab Public Groups](https://gitlab.com)** | **~$7.8B public market cap** (NASDAQ: GTLB; ~$1.06B TTM revenue) | **$29/user/month** (Premium plan, billed annually) | **Free forever**: Cap of 5 users per top-level private group (unlimited users on public groups), 400 CI/CD compute minutes/month, 10 GiB storage/project, 5,000 API requests/hour | Hierarchical public groups, nested project visibility, built-in CI/CD pipelines, and unified DevSecOps |
| **[Postman API Network](https://www.postman.com)** | **$5.6B private valuation** (~$170M–$310M estimated ARR) | **$19/user/month** (Team plan, billed annually) or **$9/month** (Solo plan) | **Free forever**: Strictly limited to 1 user (no team workspace collaboration); includes unlimited collection runs & mock server calls, 10,000 Postman API requests/month, 5 integrations, and 50 monthly AI credits | Dedicated public API discovery network, interactive collection forks, API documentation, and testing workspaces |
| **[Hugging Face Hub](https://huggingface.co)** | **$4.5B valuation** (Acquisition agreement up to $12.9B; ~$150M ARR) | **$9/month** (PRO plan) | **Free forever**: Unlimited public model/dataset repositories, up to 100 GB private storage, ~3.5 min/day ZeroGPU community compute, ~1,000 API requests/5 mins, community model hosting | Specialized public hub for machine learning models, datasets, spaces, and AI-driven API endpoints |

---

## 🟩 Open-Source Software

Self-hosted, community-driven Open Source and Public API Workspace tools, developer portals, and collaborative API platforms. Sorted by GitHub / repository star count (descending).

### [Hoppscotch](https://hoppscotch.com) [![GitHub Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers)
- **Repository:** [hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch)
- **Stack:** Vue.js, TypeScript, Node.js | **License:** MIT
- **Overview:** An open-source, lightweight, and fast API development ecosystem and web workspace. Built from the ground up as a transparent alternative to Postman, Hoppscotch supports REST, GraphQL, and WebSocket protocols with team workspaces, environment management, and self-hosted deployments.

### [Kong](https://konghq.com) [![GitHub Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers)
- **Repository:** [Kong/kong](https://github.com/Kong/kong)
- **Stack:** Lua, OpenResty, Nginx, C | **License:** Apache-2.0
- **Overview:** The world's most popular open-source cloud-native API gateway and platform service broker. Kong acts as the high-performance runtime engine connecting public workspaces, microservices, and developer portals with traffic control, rate-limiting, authentication, and plugin extensibility.

### [Directus](https://directus.io) [![GitHub Stars](https://img.shields.io/github/stars/directus/directus?style=social&color=white)](https://github.com/directus/directus/stargazers)
- **Repository:** [directus/directus](https://github.com/directus/directus)
- **Stack:** TypeScript, Node.js, Vue.js | **License:** BSL-1.1 / GPL-3.0
- **Overview:** An open-source data engine and instant API backend that wraps any SQL database with real-time GraphQL and REST APIs alongside an intuitive no-code data studio and collaborative workspace.

### [Backstage](https://backstage.io) [![GitHub Stars](https://img.shields.io/github/stars/backstage/backstage?style=social&color=white)](https://github.com/backstage/backstage/stargazers)
- **Repository:** [backstage/backstage](https://github.com/backstage/backstage)
- **Stack:** TypeScript, React, Node.js | **License:** Apache-2.0
- **Overview:** An open platform for building developer portals created by Spotify and donated to the CNCF. Backstage unifies software catalogs, API documentation, templates, and service metadata into a centralized developer portal and collaborative organization hub.

### [Swagger UI](https://swagger.io/tools/swagger-ui/) [![GitHub Stars](https://img.shields.io/github/stars/swagger-api/swagger-ui?style=social&color=white)](https://github.com/swagger-api/swagger-ui/stargazers)
- **Repository:** [swagger-api/swagger-ui](https://github.com/swagger-api/swagger-ui)
- **Stack:** JavaScript, React | **License:** Apache-2.0
- **Overview:** The ubiquitous open-source API documentation and exploration interface for OpenAPI (Swagger) specifications. Swagger UI generates interactive public documentation that allows developers to test endpoints directly from the browser.

### [Bruno](https://www.usebruno.com) [![GitHub Stars](https://img.shields.io/github/stars/usebruno/bruno?style=social&color=white)](https://github.com/usebruno/bruno/stargazers)
- **Repository:** [usebruno/bruno](https://github.com/usebruno/bruno)
- **Stack:** JavaScript, Electron, React | **License:** MIT
- **Overview:** An open-source, offline-first, git-friendly API client and workspace. Bruno stores API collections directly as plain text files in a folder on your filesystem, allowing teams to use Git for collaboration, version control, and public workspace sharing without cloud lock-in.

### [Yaak](https://yaak.app) [![GitHub Stars](https://img.shields.io/github/stars/mountain-loop/yaak?style=social&color=white)](https://github.com/mountain-loop/yaak/stargazers)
- **Repository:** [mountain-loop/yaak](https://github.com/mountain-loop/yaak)
- **Stack:** Rust, Tauri, React, TypeScript | **License:** MIT
- **Overview:** A desktop-first, open-source REST, GraphQL, and gRPC client built with Rust and Tauri. Offers fast workspace navigation, environment management, and native performance for testing and sharing API requests.

### [Scalar](https://scalar.com) [![GitHub Stars](https://img.shields.io/github/stars/scalar/scalar?style=social&color=white)](https://github.com/scalar/scalar/stargazers)
- **Repository:** [scalar/scalar](https://github.com/scalar/scalar)
- **Stack:** Vue.js, TypeScript | **License:** MIT
- **Overview:** Modern, open-source interactive API documentation, client, and developer portal generator for OpenAPI/Swagger specs. Provides beautiful public API references with an embedded interactive test client.

### [Docker Distribution (Registry)](https://github.com/distribution/distribution) [![GitHub Stars](https://img.shields.io/github/stars/distribution/distribution?style=social&color=white)](https://github.com/distribution/distribution/stargazers)
- **Repository:** [distribution/distribution](https://github.com/distribution/distribution)
- **Stack:** Go | **License:** Apache-2.0
- **Overview:** The open-source OCI and container image registry implementation that powers Docker Hub and private registries worldwide. Provides the API and storage foundation for public container distribution and image discovery.

### [Forgejo (Codeberg)](https://forgejo.org) [![Codeberg Stars](https://img.shields.io/gitea/stars/forgejo/forgejo?gitea_url=https%3A%2F%2Fcodeberg.org&logo=codeberg&style=social&color=white)](https://codeberg.org/forgejo/forgejo/stars)
- **Repository:** [forgejo/forgejo](https://codeberg.org/forgejo/forgejo)
- **Stack:** Go | **License:** GPL-3.0
- **Overview:** A community-governed, lightweight self-hosted Git forge that powers Codeberg. Provides full organization workspaces, repository hosting, issue tracking, container package registries, and Forgejo Actions CI/CD with complete data sovereignty.

### [Open Source Collective](https://opencollective.com/opensource) [![GitHub Stars](https://img.shields.io/github/stars/opencollective/opencollective?style=social&color=white)](https://github.com/opencollective/opencollective/stargazers)
- **Repository:** [opencollective/opencollective](https://github.com/opencollective/opencollective)
- **Stack:** JavaScript, TypeScript, Next.js, GraphQL | **License:** MIT
- **Overview:** A transparent platform providing fiscal hosting, open financial accounting, and community governance for open-source initiatives, giving developer projects a public workspace for budgets, expenses, and contributor funding.

---

## 📊 Comparison at a Glance

| Platform / Tool | Type | License | Self-Hostable | Primary Focus | Best For |
|:---|:---|:---|:---:|:---|:---|
| **GitHub Organizations** | SaaS Hub | Proprietary | ❌ | Code & project collaboration | Open-source project landing pages & source code |
| **GitLab Public Groups** | SaaS / Self-Managed | Proprietary | ✅ | DevSecOps & repositories | Organizations needing hierarchical project visibility |
| **Postman API Network** | SaaS Hub | Proprietary | ❌ | API collections & workflows | API consumers and commercial API publishers |
| **Hugging Face Hub** | SaaS Hub | Proprietary | ❌ | ML models, datasets & Spaces | AI/ML model publishing & interactive demos |
| **Hoppscotch** | Open Source | MIT | ✅ | Web-based API workspace | Collaborative API testing and cloud/self-hosted teams |
| **Kong** | Open Source | Apache-2.0 | ✅ | API gateway & service mesh | Enterprise API traffic routing and service control |
| **Directus** | Open Source | BSL-1.1 / GPL-3.0 | ✅ | Database-driven API workspace | Instant REST/GraphQL APIs and data collaboration |
| **Backstage** | Open Source | Apache-2.0 | ✅ | Developer portal & catalog | Enterprise internal and public developer portals |
| **Swagger UI** | Open Source | Apache-2.0 | ✅ | OpenAPI documentation | Interactive browser-based API testing & docs |
| **Bruno** | Open Source | MIT | ✅ | Git-native local API client | Developers wanting version-controlled collections via Git |
| **Yaak** | Open Source | MIT | ✅ | Fast desktop REST/gRPC client | Lightweight, native desktop API exploration |
| **Scalar** | Open Source | MIT | ✅ | Modern API reference & docs | Beautiful interactive OpenAPI documentation sites |
| **Docker Distribution** | Open Source | Apache-2.0 | ✅ | Container image registry | Self-hosted artifact and image repository workspaces |
| **Forgejo** | Open Source | GPL-3.0 | ✅ | Sovereign Git forge | Self-hosted community organization and repository hubs |
| **Open Source Collective** | Open Source | MIT | ✅ | Fiscal hosting & public ledger | Transparent open-source funding and financial management |

---

## 🤝 Contributing

Contributions are welcome! If you know of an awesome open-source API workspace, developer portal, or public collaboration tool:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature/new-tool`).
3. Add the project with details, badges, stack, and direct repository links.
4. Ensure entries are sorted appropriately by stars or company scale.
5. Open a Pull Request.

---

## 📄 License

This collection is published under the [Creative Commons Zero v1.0 Universal](LICENSE) (CC0 1.0) Public Domain Dedication. Individual software projects retain their respective proprietary or open-source licenses.

---

⭐ **Found this guide helpful? Give it a star to support open-source developer tooling!** ⭐
