## GitOps / Platform Engineer

### Summary

<small><small>
DevOps/Platform engineer focused on Kubernetes, GitOps, and Observability. Built reproducible GitOps flows (Flux/Helm/OCI),
SOPS‑KMS secrets, and Logs↔Traces correlation in Grafana v12 with OpenTelemetry. Practical, documentation‑first, fast incident loops. </small></small>

### Core Skills

<small><small>
**Kubernetes & GitOps:** GKE (Autopilot/Standard), k3s • FluxCD (HelmRelease, Kustomize) • Argo CD/Rollouts • Helm/OCI
**Observability:** GMP/Prometheus, Loki, Tempo, Grafana 12 • OpenTelemetry Collector/SDK • Fluent Bit (DaemonSet)
**CI/CD & Supply Chain:** GitHub Actions • GHCR (multi‑arch, distroless) • release automation
**IaC & Cloud:** Terraform/OpenTofu • Workload Identity (GCP)
**Security & Policy:** SOPS‑KMS • RBAC • (ready for) OPA/Kyverno guardrails
**Languages:** Go • Bash • YAML • basic Python </small></small>

### GitOps Strengths

<small><small>
Declarative‑first PR flow • Clean repo hygiene (protected branches, conventional commits) • Multi‑env layout (clusters/apps) •
Secrets via SOPS‑KMS + Workload Identity • Health checks & drift control • Progressive delivery & quick rollback •
Clear runbooks/dashboards and ownership‑based alerts </small></small>

### Selected Projects

### sentinel‑bot — ChatOps/EdgeOps bot (Go)

<small><small>
**Repo:** [https://github.com/mexxo-dvp/sentinel-bot](https://github.com/mexxo-dvp/sentinel-bot)
Flux HelmRelease + Helm/OCI; multi‑arch distroless image to GHCR; rollout strategies.
OTel traces/metrics → Tempo/Prom; logs → Loki; Grafana Explore with derived `trace_id` for fast debugging. </small></small>

### Observability Foundation — production‑ready stack (GitOps)

<small><small>
GMP (Prometheus), Loki, Tempo, Grafana 12, OpenTelemetry Operator + Collector, Fluent Bit cluster‑wide — all managed with Flux.
Datasource sync via token/UID; SLOs/alerts/runbooks; Logs↔Traces correlation for app teams. </small></small>

### gke‑iac / gke‑iac‑standard — IaC for GKE + GitOps bootstrap

<small><small>
**Repos:** [https://github.com/mexxo-dvp/gke-iac-standard](https://github.com/mexxo-dvp/gke-iac-standard) • [https://github.com/mexxo-dvp/gke-iac-autopilot](https://github.com/mexxo-dvp/gke-iac-autopilot)
Terraform/OpenTofu for Autopilot & Standard clusters; Workload Identity; Flux bootstrap; standardized namespaces/quotas guardrails. </small></small>

### AsciiArtify (R&D) — preview envs & observability demo

<small><small>
K8s preview environments, GitOps flow (Helm/Argo CD), lightweight ML; demo dashboards and Logs↔Traces correlations. </small></small>

### Education & Learning

<small><small>
Prometheus DevOps Intensive — in progress (2025)
Hackathon: Intelligent Kubernetes Autoscaler Challenge — co‑lead (GitOps/Observability), 2025 </small></small>

### Additional

<small><small>
Languages: Ukrainian — Native; English — B1
Public repos: GHCR packages, Helm charts, Flux manifests (pinned on GitHub)
Volodymyr Dobrydnyev — 
Bratislava, SK • [mmexxoo@gmail.com](mailto:mmexxoo@gmail.com) • [https://github.com/mexxo-dvp](https://github.com/mexxo-dvp) • [https://www.linkedin.com/in/volodymyr-dobrydnev-2a8615387/](https://www.linkedin.com/in/volodymyr-dobrydnev-2a8615387/)
</small></small>
