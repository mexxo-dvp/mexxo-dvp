# Volodymyr Dobrydnev — DevOps / Platform Engineer

> Practical DevOps/Platform engineer focused on Kubernetes, GitOps, Observability, and security. I move fast, keep things tidy.

---

## TL;DR — how I add value

* 🚀 **Standarize & harden Kubernetes infra** (GKE Autopilot/Standard, k3s/k3d) with GitOps (Flux/Argo CD).
* 📈 **Full observability stack**: Prometheus (GMP), Loki, Tempo, Grafana 12, OpenTelemetry Collector; Logs↔Traces correlation.
* 🔐 **Secure‑by‑default**: SOPS‑KMS, Workload Identity, gitleaks, distroless images, least‑privilege RBAC.
* 🛠️ **Hands‑off CI/CD**: Helm/OCI, multi‑arch Docker, GHCR, GitHub Actions, release flows with quality gates.

---

## Strengths

* 🧠 **Systems thinking**: from IaC to monitoring and cost.
* 🔄 **GitOps discipline**: clean history, branch rules, secrets via KMS/SOPS.
* 🔭 **Observability**: metrics/logs/traces in one place, derived fields, correlations, Grafana Explore workflows.
* 🗣️ **Communication**: concise explanations and trade‑offs; lead via PR reviews, READMEs, dashboards.

---

## Skills

**Kubernetes / GitOps:** FluxCD, Argo CD, Helm/HelmRelease, Kustomize; Namespaces/NetworkPolicies; HPA; Gateway API (basic).

**Observability:** Prometheus (incl. **Google Managed Prometheus — GMP**), Grafana 12.x, Loki, Tempo, Fluent Bit (incl. Lua enrich), OpenTelemetry Collector/Operator; Logs↔Traces correlation; Grafana Explore.

**CI/CD & Containers:** Docker (multi‑arch), GHCR (images & OCI charts), Makefile, GitHub Actions; release pipelines, semantic tags.

**Cloud & IaC:** GKE, GCP IAM/Workload Identity, budgets; Terraform/OpenTofu; SOPS‑KMS for secrets.

**DevSecOps:** gitleaks, KMS encryption, distroless images, fine‑grained PAT scopes.

**Languages:** Go (bot/CLI), Bash, YAML/Helm; basic Python for tooling/scripts.

---

## Key Projects

### 1) **sentinel‑bot** — ChatOps/EdgeOps bot (Go) with full Observability

* 📦 **Container:** multi‑arch build, distroless; published to **GHCR**.
* 🧰 **Helm/OCI:** chart packaged & delivered via GHCR; deployed through **Flux HelmRelease**.
* 🗝️ **Secrets:** TELE_TOKEN encrypted with **SOPS‑KMS** (GCP KMS), delivered via GitOps.
* 🔭 **Observability:** OTEL SDK for metrics/traces; **Fluent Bit** DaemonSet → **Loki**; **Tempo** for traces; **GMP** for metrics; **Grafana 12** with derived field `trace_id` and Logs↔Traces.
* ⚡ **Outcome:** transparent telemetry from Telegram message to service events; tight debug loop in Grafana Explore.

### 2) **Observability Foundation** — opinionated, production‑ready stack

* 🧩 **Components:** GMP (Prometheus), Loki, Tempo, Grafana, OpenTelemetry Operator + Collector, Fluent Bit (cluster‑wide).
* 🏷️ **Features:** logs↔traces correlation (derived fields), data source UID control, service & infra dashboards.
* 📐 **Infra:** Flux‑managed, HelmRelease objects, secret sync; standardized repo structure.

### 3) **gke‑iac / gke‑iac‑standard** — IaC for GKE + GitOps bootstrap

* 🧱 **Terraform/OpenTofu** for **Autopilot** and **Standard** clusters.
* 🔑 **Security:** **Workload Identity**, SOPS‑KMS, least‑privilege access.
* 🔁 **GitOps:** Flux bootstrap, clear split between `clusters/gke/flux-system` and `clusters/gke/apps`.
* 📈 **Value:** fast environment creation, repeatability, cost control.



### 4) **AsciiArtify** (R&D)

* 🧪 Preview environments in Kubernetes, GitOps flow (Helm/Argo CD), lightweight ML components; great for GitOps & observability demos.

[sen­tinel-bot](https://github.com/mexxo-dvp/sentinel-bot)
[gke-iac-standard](https://github.com/mexxo-dvp/gke-iac-standard]
[gke-iac-autopilot](https://github.com/mexxo-dvp/gke-iac-autopilot]
---

## GitOps layout

```
clusters/
  gke/
    flux-system/        # Flux bootstrap, controllers, rules
    apps/
      your-app/         # HR, values, secrets (SOPS)
      observability/    # Grafana, Loki, Tempo, OTel, FB
charts/                 # Helm charts (also as OCI in GHCR)
.github/workflows/      # CI/CD: build, push, release, SOPS
```

---

## Achievements

* 🎯 End‑to‑end **Logs↔Traces** correlation in Grafana (v12), derived fields (`trace_id`) for Loki.
* 🔁 Unified **data source syncing** in Grafana via token/UID and GitOps control.
* 🔗 Full GitOps cycle: from IaC cluster creation to automated app & observability releases.

---

## Certifications & Learning

* 🎓 **Prometheus DevOps Intensive (Prometheus, 2025)** — in progress (tests/assignments/hackathon).
* 🧬 **Hackathon: Intelligent Kubernetes Autoscaler Challenge** — co‑lead, responsible for GitOps/Observability track.

---

## How I work (workflow)

1. 🧭 **Discovery → IaC:** requirements → Terraform/OpenTofu modules.
2. 🚀 **GitOps bootstrap:** Flux/Argo, secrets via **SOPS‑KMS**.
3. 🔭 **Observability baseline:** GMP, Prometheus, Loki, Tempo, OTel, Grafana, dashboards.
4. 🔁 **CI/CD:** GitHub Actions, multi‑arch builds, Helm/OCI releases.
5. 📑 **Operations:** SLO/SLI charts, alerts, cost review, regular tech reports.

---

## Contacts
* 📍 Lviv, Ukraine / Bratislava, Slovakia
* 🔗 GitHub: `github.com/mexxo-dvp`
* ✉️ Email: mmexxoo@gmail.com
 
[linkedin](https://www.linkedin.com/in/volodymyr-dobrydnev-2a8615387/)

---

## Languages

* Ukrainian — Native
* English — B1
