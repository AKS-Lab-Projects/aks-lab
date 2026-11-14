# AKS Lab

Practice lab: AKS + Defender for Containers + Foundry, built end-to-end as code.

| Folder | Purpose |
|---|---|
| `infra/` | Bicep infrastructure |
| `app/` | Application and container image |
| `k8s/` | Kubernetes manifests |
| `.github/workflows/` | CI/CD pipelines |

Principles: everything in Git, PR-only changes to `main`, no stored secrets (OIDC / workload identity).
