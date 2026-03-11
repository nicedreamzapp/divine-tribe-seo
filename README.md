# Divine Tribe SEO Strategy & Blog Content

[![iNeedHemp](https://img.shields.io/website?url=https%3A%2F%2Fineedhemp.com&label=iNeedHemp.com)](https://ineedhemp.com)
[![NiceDreamz](https://img.shields.io/website?url=https%3A%2F%2Fnicedreamzwholesale.com&label=NiceDreamzWholesale.com)](https://nicedreamzwholesale.com)
[![TribeSeedBank](https://img.shields.io/website?url=https%3A%2F%2Ftribeseedbank.com&label=TribeSeedBank.com)](https://tribeseedbank.com)
[![MarijuanaUnion](https://img.shields.io/website?url=https%3A%2F%2Fmarijuanaunion.com&label=MarijuanaUnion.com)](https://marijuanaunion.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Documentation and tooling for the **Divine Tribe SEO strategy** — a coordinated content and link-building plan across four WordPress sites and two specialty web properties.

## Overview

This repository documents the SEO playbook behind the Divine Tribe brand's web presence. It covers keyword strategy, blog content calendars, internal cross-linking architecture, schema markup, and technical SEO tooling used to grow organic traffic across the entire property network.

### The Property Network

| # | Property | Platform | Focus |
|---|----------|----------|-------|
| 1 | [iNeedHemp.com](https://ineedhemp.com) | WooCommerce / WordPress | Flagship DTC store — vaporizers, atomizers, mods, accessories |
| 2 | [NiceDreamzWholesale.com](https://nicedreamzwholesale.com) | WooCommerce / WordPress | B2B wholesale portal and distribution |
| 3 | [TribeSeedBank.com](https://tribeseedbank.com) | WordPress | Cannabis genetics and seed sales |
| 4 | [MarijuanaUnion.com](https://marijuanaunion.com) | WordPress | Community content hub, news, advocacy |
| 5 | [Disclosure Day](https://disclosureday.nicedreamzwholesale.com) | Static / subdomain | Spielberg UFO film fan site — cultural content play |
| 6 | [The Farmstand 3D](https://marijuanaunion.com/marketplace/) | A-Frame WebXR | Immersive 3D virtual cannabis marketplace |

## SEO Strategy Pillars

### 1. Keyword Clustering

- **Transactional:** "buy divine tribe v5", "dtv5 atomizer", "divine tribe core 2.0"
- **Informational:** "how to use a dab pen", "e-rig buyer's guide", "best temperature for rosin"
- **Local/Niche:** "hemp vaporizer wholesale", "cannabis seed bank USA"
- **Brand:** "divine tribe", "ineedhemp", "nicedreamz"

### 2. Content Architecture

Each WordPress site publishes long-form blog content targeting specific keyword clusters:

| Site | Content Themes |
|------|---------------|
| iNeedHemp | Product guides, how-tos, comparisons, Ohm's law guides, cleaning/maintenance |
| NiceDreamzWholesale | Wholesale buyer guides, B2B hemp industry news |
| TribeSeedBank | Strain profiles, growing guides, seed selection |
| MarijuanaUnion | Cannabis news, legislation updates, community stories |

### 3. Internal Cross-Linking

Every blog post includes contextual links to at least 2 other properties in the network. The linking pattern follows a hub-and-spoke model with iNeedHemp.com as the primary hub.

### 4. Technical SEO

- JSON-LD structured data (Product, FAQPage, Article, Organization)
- Optimised meta titles and descriptions per page
- Canonical URLs and hreflang where needed
- XML sitemaps submitted to Google Search Console
- Core Web Vitals monitoring

### 5. Schema Markup

Custom scripts generate and deploy schema markup across all four WordPress sites:
- `Product` schema on all WooCommerce product pages
- `FAQPage` schema on FAQ sections
- `Article` / `BlogPosting` schema on all blog content
- `Organization` schema on homepages

## Blog Content Published

A sample of key blog posts deployed as part of this strategy:

- **E-Rig Buyer's Guide** — Comprehensive comparison of electronic rigs
- **Ball Vape Guide** — Deep dive into ball vaporizer technology
- **Concentrates Guide** — Types of concentrates and best consumption methods
- **Core 2.0 vs Puffco** — Head-to-head product comparison
- **Dab Pen vs E-Rig** — Format comparison for new users
- **E-Rig for Rosin** — Targeting the rosin enthusiast segment
- **Ohm's Law for Vapers** — Educational content for the DIY/rebuild community
- **UV Jars Guide** — Product-adjacent content for accessory sales
- **Wire Science & Rebuilding** — Technical deep-dive content
- **Ruby Insert / Twist** — Product-specific SEO content

## Tools & Scripts

This repo includes Python scripts used to manage SEO across the network:

| Script | Purpose |
|--------|---------|
| `check_all_seo_green.py` | Audit all sites for SEO completeness |
| `add_schema.py` | Deploy JSON-LD schema markup |
| `crosslink_and_ping.py` | Insert cross-links and ping search engines |
| `publish_blog_posts.py` | Push blog content to WordPress via REST API |
| `seo_audit.py` | Generate SEO audit reports |
| `pull_search_data.py` | Pull Google Search Console data |

## Screenshots

> _Dashboard screenshots and SERP ranking screenshots coming soon._

| View | Preview |
|------|---------|
| SEO Audit Dashboard | ![Audit](screenshots/audit.png) |
| Search Console Growth | ![Growth](screenshots/growth.png) |

## License

This project is released under the [MIT License](LICENSE).

---

*Maintained by the [Divine Tribe](https://ineedhemp.com) team — growing organic reach one keyword at a time.*
