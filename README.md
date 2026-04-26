 ### Hi, I'm Ahmed

  DevOps / Platform Engineer. I take production Kubernetes from "it works on
  the lead's laptop" to "the on-call rotation actually sleeps" — bare-metal,
  GitOps, OpenTelemetry, and zero-downtime everything.

  ---

  #### A few things I've shipped

  - **99.9% uptime** on a bare-metal Kubernetes cluster (kubeadm, Cilium, Envoy
    Gateway) running production multi-tenant SaaS — 70k+ bookings, 11k+ vehicles
  - **92% infrastructure cost reduction** migrating workloads off Heroku into
    self-managed K8s with full GitOps automation
  - **Eliminated 413ms rollout downtime** by moving WebSocket/SSE traffic from
    Cilium's built-in Gateway API to standalone Envoy Gateway
  - **Owned the Datadog → self-managed observability migration** — Prometheus,
    Grafana, Loki, Alertmanager, OpenTelemetry — for cost control and full
    data ownership
  - **Three-layer GitOps architecture** with ArgoCD ApplicationSets
    (Bootstrap → Infrastructure → Applications), Kustomize overlays, sync waves,
    PreSync hooks for automated database migrations

  #### What I do day-to-day

  - Architect and operate self-hosted Kubernetes — kubeadm, Cilium (eBPF
    kube-proxy replacement, Hubble L7 observability), Envoy Gateway on
    Gateway API v1.4.1
  - Build full GitOps platforms with ArgoCD ApplicationSets, Kustomize, sync
    waves, and automated DB migrations via PreSync hooks
  - Run self-managed observability stacks instead of paying vendors —
    Prometheus, Grafana, Loki, Alertmanager, OpenTelemetry, Hubble
  - Secure the cluster: HashiCorp Vault KV v2, External Secrets Operator,
    cert-manager Let's Encrypt automation, container hardening
    (runAsNonRoot, seccompProfile, dropped capabilities), PodDisruptionBudgets
  - Apply agentic-AI tooling (Claude Code) to platform tasks — manifest
    generation, GitOps debugging, operational scripting
  - Automate the things that should be automated; document the rest

  #### Currently

  - Wrapping up 3.5 years as Former Platform Engineer / Co-founder at **KITTS**
    (Sep 2022 – Apr 2026)
  - Operating a personal bare-metal Kubernetes cluster for side projects,
    e-commerce, and home services — full GitOps, Renovate, monitoring stack
  - Learning German (A1 certified, working toward B1)
  - **Open to DevOps / Platform / SRE roles** — reach out via LinkedIn

  #### Stack

  I prefer self-hosted, open-source, and boring. Tools I reach for:

  **Containers & GitOps:** Kubernetes, ArgoCD, Helm, Kustomize, Harbor, Renovate, Trivy
  **Networking:** Cilium (eBPF), Envoy Gateway, Gateway API, Cloudflare
  **Observability:** Prometheus, Grafana, Loki, Alertmanager, OpenTelemetry, Hubble
  **Security:** HashiCorp Vault, External Secrets Operator, cert-manager
  **IaC & Cloud:** Terraform, Ansible, AWS, GCP, Cloudflare R2
  **Languages:** Bash, Python, Go, TypeScript, SQL
  **Data:** PostgreSQL (CloudNativePG), MySQL/MariaDB, Redis/Valkey, Longhorn

  #### Selected work

  - **[WynnAspects](https://wynnaspects.com)** — production microservices
    platform serving 2,000+ active users and 2M+ monthly API requests on
    bare-metal Kubernetes. ArgoCD GitOps, Harbor private registry,
    CloudNativePG PostgreSQL, Longhorn distributed storage, Cloudflare-backed
    edge. Application services instrumented with OpenTelemetry for traces and
    metrics.

  - **Personal Kubernetes infrastructure** — self-managed bare-metal cluster
    (2 nodes) running e-commerce (PrestaShop + MariaDB), workflow automation
    (n8n), and Discord bot workloads. Full ArgoCD ApplicationSets,
    Renovate-driven dependency updates, monitoring stack — for hands-on
    reliability engineering.

  - **[GraphICE](https://icebreaker8.github.io/graphICE-website/)** — C# / .NET
    desktop app for graph algorithm visualization (Dijkstra, Bellman-Ford,
    Floyd-Warshall). Student-era project, kept pinned because it's genuinely
    useful for teaching.

  #### How I think about infrastructure

  > Boring infra is good infra. The most interesting thing in production should
  > be the application — not the platform breathing fire underneath it.

  GitOps everything. Self-host where it matters (cost, control, data ownership);
  pay vendors where it doesn't (DNS, edge caching, off-site backups). Document
  the *why*, not the *what*. When something breaks, build the system that
  prevents it from happening again — and write the post-mortem.

  #### GitHub stats

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

  #### Reach me

  [LinkedIn](https://www.linkedin.com/in/ahmed-frikha-kitts/)
