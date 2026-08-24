# OpenDomainHub

**Realistic industry data, openly available.**

OpenDomainHub is an open-source initiative for realistic industry and domain data. We publish reusable data models, synthetic datasets, business rules, use cases, and reference architectures so teams can build, learn, and demonstrate solutions without production data.

This repository is the **organization hub**. Each industry domain lives in its **own repository**.

---

## Overview

OpenDomainHub is a growing library of domain foundations. Each domain captures how a real industry works: entities, relationships, operational rules, metrics, and the architectures used to analyze them.

Use it to prototype pipelines, train models, design analytics, and teach or demo industry solutions—without waiting for access to sensitive systems.

## Purpose

Give practitioners a complete, realistic starting point for industry data work.

Typical projects stall on the same gaps: production data is restricted, public datasets are incomplete, and demo data rarely encodes real business behavior. OpenDomainHub reduces that setup cost so you can start from a coherent domain instead of an empty schema.

## Motivation

Technology is easy to sample. Realistic domain context is not.

A banking demo needs more than a customer list. It needs accounts, cards, transactions, loans, merchants, branches, and the rules that bind them. The same is true in healthcare, retail, manufacturing, telecom, and every other industry we cover.

OpenDomainHub exists to close the gap between sample files and operational domain solutions.

## Mission

Make realistic domain data and business knowledge accessible to everyone building data, analytics, and AI solutions.

## Vision

A community-maintained library where each domain is a practical path from industry context to working solutions—data you can generate, rules you can trust, use cases you can run, and architectures you can reuse.

---

## How it works

Every domain follows the same path:

**Domain → Data Model → Synthetic Data → Business Rules → Use Cases → Analytics → AI → Reference Architecture**

| Stage | What you get |
| --- | --- |
| **Domain** | Industry context, processes, personas, and terminology |
| **Data model** | Schemas and entity relationships |
| **Synthetic data** | Generators for realistic, scalable, non-sensitive datasets |
| **Business rules** | Constraints and behaviors that keep data operationally plausible |
| **Use cases** | Problems organizations actually solve with the data |
| **Analytics** | KPIs, metrics, and analytical questions |
| **AI** | ML, RAG, agents, and other applied examples |
| **Reference architecture** | How data moves from sources through storage, transformation, analytics, and AI |

Each domain repository is intended to include **synthetic data generators**, **schemas**, **business use cases**, **KPIs**, **analytics**, **AI/ML examples**, and **reference architectures**. Coverage grows over time; not every artifact is present on day one.

---

## Domains

Each domain has (or will have) a **separate repository**. This hub links them together.

| Domain | Focus |
| --- | --- |
| [Banking](https://github.com/OpenDomainHub/banking) | Customers, accounts, cards, payments, lending |
| [Insurance](https://github.com/OpenDomainHub/insurance) | Policies, claims, underwriting, risk |
| [Healthcare](https://github.com/OpenDomainHub/healthcare) | Patients, encounters, providers, clinical operations |
| [Pharma](https://github.com/OpenDomainHub/pharma) | Trials, manufacturing, commercial, regulatory |
| [Retail](https://github.com/OpenDomainHub/retail) | Stores, assortment, inventory, merchandising |
| [E-commerce](https://github.com/OpenDomainHub/ecommerce) | Catalog, orders, fulfillment, digital commerce |
| [Manufacturing](https://github.com/OpenDomainHub/manufacturing) | Plants, production, quality, maintenance |
| [Automotive](https://github.com/OpenDomainHub/automotive) | Vehicles, dealers, parts, aftersales |
| [Telecom](https://github.com/OpenDomainHub/telecom) | Subscribers, networks, usage, billing |
| [Energy](https://github.com/OpenDomainHub/energy) | Generation, grid, metering, utilities |
| [Logistics](https://github.com/OpenDomainHub/logistics) | Shipments, carriers, routes, warehouses |
| [Supply Chain](https://github.com/OpenDomainHub/supply-chain) | Planning, procurement, inventory, distribution |
| [SaaS](https://github.com/OpenDomainHub/saas) | Tenants, subscriptions, product usage, billing |
| [Technology](https://github.com/OpenDomainHub/technology) | Platforms, IT operations, software delivery |

Repositories are created as domains are published. If a link 404s, that domain is not live yet.

---

## Contributing

OpenDomainHub is community-driven. Useful contributions include:

- New or improved **domain repositories**
- **Schemas** and data models
- **Synthetic data generators** and business rules
- **Use cases**, **KPIs**, and analytics examples
- **AI/ML** examples and **reference architectures**
- Documentation, tests, and data-quality checks

Open an issue or pull request on this hub, or on the relevant domain repository. Prefer focused changes, realistic domain fidelity, and artifacts others can run and reuse.

---

OpenDomainHub is where **domain knowledge meets data engineering, analytics, and AI.**
