### Hi, I'm Ahmed

I'm a Software Engineer based in Munich, working on backend and DevOps: I write the NestJS services, integrations and full-stack apps, and I run the production Kubernetes they live on, on AWS, Scaleway and bare metal. Most of my work revolves around GitOps, observability, and making sure things don't go down when they shouldn't.

---

### What I actually do

Day to day, I spend most of my time:

- Running production Kubernetes on managed clouds (Amazon EKS, Scaleway Kubernetes Kapsule) and on my own bare-metal cluster (kubeadm, Cilium with eBPF, Envoy Gateway on Gateway API)

- Building GitOps and CI/CD workflows with ArgoCD, GitHub Actions and GitLab CI (ApplicationSets, Kustomize, Helm, sync waves, PreSync DB migrations)

- Maintaining observability stacks: Prometheus, Grafana, Loki, Tempo, Alertmanager, OpenTelemetry, Hubble

- Keeping secrets out of Git: HashiCorp Vault with External Secrets Operator, SOPS/age, cert-manager, plus general container hardening

- Writing backends in NestJS and PostgreSQL with queues (Bull, BullMQ, Kafka), and integrating third-party and government APIs (Stripe, DocuSign, ANTAI)

- Using AI tools (mostly Claude Code) to speed up repetitive platform work (manifests, debugging, scripting)

---

### Currently

- Co-founder of [KITTS](https://kitts.io), a SaaS for vehicle rental and fleet management, which I still maintain

- Software engineer on [Qasqad](https://qasqad.com) (formerly FPS Navigator), a B2B parking-fines platform KITTS acquired: I own its backend, its Stripe billing and its Scaleway Kubernetes platform (4,400+ fines processed for 8 client companies), ran its v2 launch in November 2026, and I'm building its ANTAI traffic-fines module

- Running my own bare-metal cluster for side projects, e-commerce and home services (full GitOps, monitoring, Renovate)

- Learning German (A1, working toward B2)

- **Open to full-time DevOps / Backend / Platform roles in Munich and across Germany**

---

### Stack

I tend to prefer self-hosted, open-source, and boring tools.

**Containers & GitOps**
Kubernetes, ArgoCD, Helm, Kustomize, Harbor, Renovate, Trivy

**CI/CD**
GitHub Actions, GitLab CI

**Networking**
Cilium (eBPF), Envoy Gateway, Gateway API, Traefik, Cloudflare

**Observability**
Prometheus, Grafana, Loki, Tempo, Alertmanager, OpenTelemetry, Hubble

**Security**
HashiCorp Vault, External Secrets Operator, SOPS/age, cert-manager

**IaC & Cloud**
Terraform, Ansible, AWS (EKS, RDS, S3, IAM), Scaleway (Kapsule, Object Storage), GCP, Cloudflare R2

**Backend**
Node.js, NestJS, TypeScript, Bull/BullMQ, Kafka, Stripe, Firebase

**Languages**
TypeScript, Bash, Python, Go, SQL

**Data**
PostgreSQL (Amazon RDS, CloudNativePG), MySQL/MariaDB, Redis/Valkey, Longhorn

---

### Things I've built

- **KITTS platform**: the rental SaaS I co-founded, built in Node.js and TypeScript (Strapi and NestJS) on PostgreSQL, with Stripe and DocuSign. It has handled 79k+ bookings across 11k+ vehicles. I moved it from Heroku to Amazon EKS with Terraform (62% cheaper, 99.9% uptime), then in 2025 to a self-managed Kubernetes cluster on dedicated servers, taking hosting from €600 a month on Heroku to €50.

- **Qasqad backend**: Stripe billing for SEPA direct debit and card, with an idempotency key on every payment so no client has ever been charged twice, and an OCR pipeline (Mistral AI since June 2026) that has read 3,700+ paper fine notices. For the v2 launch I migrated 99k+ vehicle assignments and every API key to per-organisation accounts, after catching a migration bug that would have sent live API keys to the wrong customer. 168 Playwright end-to-end tests cover every fine flow.

- **ANTAI traffic-fines module (Qasqad, work in progress)**: takes fines in hourly from the French State's fleet API, routes them, designates the driver on a click, in a batch or automatically, and tracks statuses and receipts. NestJS, PostgreSQL, Bull queues.

- **Qasqad platform**: Helm-deployed services on Scaleway Kubernetes Kapsule with SOPS-encrypted secrets, Traefik and cert-manager, separate staging and production environments, a deploy guard that refuses any release able to reach production by mistake, and the rehearsed cut-over runbook I used to launch v2.

- **WynnAspects** ([wynnaspects.com](https://wynnaspects.com)): an event-driven microservices platform running on my bare-metal cluster. NestJS APIs, an Angular SSR frontend, real-time WebSocket and SSE services, Kafka and BullMQ behind a transactional outbox, Valkey caching, and OpenTelemetry tracing into Grafana Tempo. Shipped with ArgoCD GitOps, Harbor and CloudNativePG.

- **Personal Kubernetes cluster**: a 3-node bare-metal cluster (1 control plane + 2 workers, kubeadm) running WynnAspects, e-commerce (PrestaShop + MariaDB), automation (n8n) and Discord bots. Managed with ArgoCD ApplicationSets and Renovate, with CloudNativePG backups whose restore is tested, not just configured.

- **GraphICE**: C# / .NET desktop app for visualizing graph algorithms (Dijkstra, Bellman-Ford, Floyd-Warshall). Built during my student years but still useful for teaching.

---

### How I think about infrastructure

I try to keep everything in Git, self-host where it actually matters (cost, control, data), and rely on managed services where it doesn't.
When something breaks, I focus on fixing the root cause and making sure it doesn't happen again.

---

### GitHub stats

<table>
<tr>
<td>
  <img alt="Ahmed's GitHub Stats"
       src="https://github-readme-stats.vercel.app/api?username=IceBreaker8&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&rank_icon=github" />
</td>
<td>
  <img alt="GitHub Streak"
       src="https://streak-stats.demolab.com/?user=IceBreaker8&hide_border=true" />
</td>
</tr>
</table>

---

### Reach me

[LinkedIn](https://www.linkedin.com/in/ahmed-frikha-kitts/) · ahmadfrikha11@gmail.com
