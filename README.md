### Hi, I'm Ahmed

I'm a Software Engineer based in Munich, working across DevOps and backend: I run production Kubernetes on AWS, Scaleway and bare metal, and I write the NestJS services, integrations and full-stack apps that run on top of it. Most of my work revolves around GitOps, observability, and making sure things don't go down when they shouldn't.

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
- Leading engineering on FPS Navigator (now Qasqad), a B2B parking-penalty platform KITTS acquired: its Scaleway Kubernetes platform, the ANTAI traffic-fines module, and the OCR and billing pipeline
- Running my own bare-metal cluster for side projects, e-commerce and home services (full GitOps, monitoring, Renovate)
- Learning German (A2, working toward B1)
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

- **ANTAI traffic-fines module (FPS Navigator)**: receives fines from the French State's fleet API, routes them, designates the driver on a click, in a batch or automatically, and tracks statuses and receipts. NestJS, PostgreSQL, Bull queues, browser-driven Playwright end-to-end tests.

- **FPS Navigator platform**: Helm-deployed services on Scaleway Kubernetes Kapsule with SOPS-encrypted secrets, Traefik and cert-manager, separate staging and v2 environments, and a deploy guard that refuses any release able to reach production by mistake.

- **WynnAspects** ([wynnaspects.com](https://wynnaspects.com)): an event-driven microservices platform running on my bare-metal cluster. NestJS APIs, an Angular SSR frontend, real-time WebSocket and SSE services, Kafka and BullMQ behind a transactional outbox, Valkey caching, and OpenTelemetry tracing into Grafana Tempo. Shipped with ArgoCD GitOps, Harbor and CloudNativePG.

- **Personal Kubernetes cluster**: a 3-node bare-metal cluster (1 control plane + 2 workers, kubeadm) running WynnAspects, e-commerce (PrestaShop + MariaDB), automation (n8n) and Discord bots. Managed with ArgoCD ApplicationSets and Renovate, with CloudNativePG backups whose restore is tested, not just configured. [Repo](https://github.com/IceBreaker8/icedev-argocd-cluster)

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
