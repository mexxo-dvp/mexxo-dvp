# 🌐 Welcome! 🇺🇦🇪🇺

> Practical DevOps/Platform engineer focused on Kubernetes, GitOps, Observability, and security. I move fast and keep things tidy.

---

## TL;DR — how I add value

* 🚀 **Standardize & harden K8s** across GKE/k3s with GitOps (Flux/Argo CD).
* 📈 **Make systems measurable**: SLOs, Logs↔Traces, fast incident loops.
* 🔐 **Secure-by-default**: SOPS‑KMS, Workload Identity, least‑privilege RBAC.
* 🛠️ **Automated delivery**: Helm/OCI, multi‑arch builds, GHCR, GitHub Actions.

---

## Strengths

* 🧠 Systems thinking from IaC to monitoring and cost.
* 🔄 GitOps discipline: clean history, branch rules, reproducible envs.
* 🔭 Observability-first mindset; derived fields & correlation workflows.
* 🗣️ Clear comms: concise trade‑offs, PR leadership, docs & dashboards.

---

## Skills (condensed)

**Core stack:** Kubernetes • GitOps (Flux/Argo) • Terraform/OpenTofu • Helm/OCI • GHCR • GitHub Actions • Observability (GMP/Loki/Tempo/Grafana/OTel) • Fluent Bit • SOPS‑KMS • Workload Identity • RBAC • Go/Bash/YAML • basic Python.

---

## Key Projects

### 1) **sentinel‑bot** — ChatOps/EdgeOps bot (Go) with full observability

* 📦 Distroless multi‑arch image → **GHCR**; 🧰 Helm/OCI + **Flux HelmRelease**.
* 🗝️ Secrets via **SOPS‑KMS**; 🔭 OTEL metrics/traces; Logs→**Loki**, Traces→**Tempo**, Metrics→**GMP**; Grafana 12 derived `trace_id`.
* ⚡ Tight debug loop in Grafana Explore.

[sen­tinel‑bot](https://github.com/mexxo-dvp/sentinel-bot)

### 2) **Observability Foundation** — opinionated, production‑ready stack

* 🧩 GMP, Loki, Tempo, Grafana, OpenTelemetry Operator + Collector, Fluent Bit (cluster‑wide), all GitOps‑managed.

### 3) **gke‑iac / gke‑iac‑standard** — IaC for GKE + GitOps bootstrap

* 🧱 Terraform/OpenTofu for Autopilot & Standard; 🔑 Workload Identity; Flux bootstrap.

[gke‑iac‑standard](https://github.com/mexxo-dvp/gke-iac-standard) • [gke‑iac‑autopilot](https://github.com/mexxo-dvp/gke-iac-autopilot)

### 4) **AsciiArtify** (R&D)

* 🧪 K8s preview envs, GitOps flow (Helm/Argo CD), lightweight ML; demo for GitOps & observability.

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

* 🎯 End‑to‑end **Logs↔Traces** correlation in Grafana (v12) with derived `trace_id`.
* 🔁 Unified Grafana **data source syncing** via token/UID under GitOps.
* 🔗 Full GitOps cycle: IaC clusters → automated app/observability releases.

---

## Certifications & Learning

* 🎓 Prometheus DevOps Intensive (2025) — in progress.
* 🧬 Hackathon: Intelligent Kubernetes Autoscaler Challenge — co‑lead (GitOps/Observability).

---

## How I work (workflow)

1. 🧭 Discovery → IaC (Terraform/OpenTofu).
2. 🚀 GitOps bootstrap (Flux/Argo); secrets via **SOPS‑KMS**.
3. 🔭 Observability baseline (GMP/Loki/Tempo/Grafana/OTel).
4. 🔁 CI/CD (Actions), Helm/OCI releases, multi‑arch builds.
5. 📑 SLO/SLI, alerts, cost review, clear status reports.

---

## Contacts

* 📍 Lviv, Ukraine / Bratislava, Slovakia
* 🔗 GitHub: [github.com/mexxo-dvp](https://github.com/mexxo-dvp)
* ✉️ Email: [mmexxoo@gmail.com](mailto:mmexxoo@gmail.com)
* 🔗 LinkedIn: [volodymyr-dobrydnev](https://www.linkedin.com/in/volodymyr-dobrydnev-2a8615387/)

---

## Languages

* Ukrainian — Native
* English — B1
