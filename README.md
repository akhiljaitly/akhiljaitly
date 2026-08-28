# Akhil Jaitly

**Senior Director, Operations** — AWS, network, datacenter, and systems teams at enterprise scale.
**Independent builder** — AI agent tooling, contract intelligence, and personal-data platforms, shipped to production.

Source is private. The work below is deployed and running. Live demos and architecture walkthroughs on request.

---

### Selected work

| Project | What it does | Status | Stack |
|---|---|---|---|
| **Verdict** | LLM agent observability — captures trajectories, embeds and clusters them, replays runs deterministically to catch regressions. | 🟢 Live · Patent-pending | FastAPI · Next.js · Postgres · SDK (py/ts) |
| **ClauseWatch** | AI contract intelligence — extracts license terms with every value pinned to its source span and verbatim quote, confidence-gated to human review. | 🔵 In build | FastAPI · Claude · SQLAlchemy · Next.js |
| **FamilyVault** | Family document vault — identity, medical, legal, financial records with expiry alerts and member sharing. | 🟢 Live | FastAPI · R2 · Logto SSO · Resend |
| **PropertyVault** | Property management — maintenance, expenses, income, documents, vendors, reminders. | 🟢 Live | FastAPI · Next.js · Postgres |
| **FinanceHub** | Personal finance — accounts, transactions, budgets, bills, savings goals with AI insights. | 🟢 Live | FastAPI · Claude · Next.js |
| **ARIA** | Enterprise risk intelligence — unified anomaly, capacity, and vendor-risk scoring. | 🟡 Patent POC | FastAPI · Postgres 16 · Redis |

*6 products shipped · 4 live in production · 2 patent-pending · 100% self-built and deployed.*

---

### Infrastructure & automation

Ansible and Terraform automation for systems and network operations. Private and sanitized; patterns and walkthroughs on request.

| Area | What it automates | Stack |
|---|---|---|
| **System Builds** | VM provisioning on VMware vSphere (template → OS config), standardized idempotent server builds across tiers. | Ansible · vSphere · Jinja2 |
| **Network Patching** | Staged device patching with automatic config backup before change and validation after. | Ansible · Backup · Validation |
| **Network Health Checks** | Scheduled probes across the fleet, drift and failure detection, rolled into readable reports. | Ansible · Jinja2 · Reporting |
| **Network Inventory** | Live, accurate device inventory collected from the fleet as a single source of truth. | Ansible · Fact-gathering |
| **AWS Terraform Labs** | Reproducible VPC / compute / storage / IAM scenarios as code, mapped to the AWS Solutions Architect Associate domains. *(in build)* | Terraform · AWS · HCL |

---

### How I build

- **Ship to production** — real infra, custom domains, SSO, CI. Not demos.
- **Provenance first** — extracted data carries its source; confidence gates route the uncertain to human review.
- **Ops discipline** — secrets as refs, tenant isolation, fail-loud error handling, rollback plans.
- **AI where it earns it** — Claude for extraction, insight, and agent tooling, with deterministic validation around the model.

---

📄 **[Full portfolio → portfolio.jaitly.dev](https://portfolio.jaitly.dev)**
✉️ akhiljaitly@gmail.com

> Repositories are private. Live links, architecture, and outcomes shared openly; source available on request under NDA.

<!-- profile -->
