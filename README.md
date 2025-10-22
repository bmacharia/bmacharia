
# Hi, I’m Babu 👋
I build cloud-native platforms with Kubernetes, GitOps, and automation—focused on reliability, developer velocity, and AI/LLM workload readiness.

## 🔧 Tech Stack
AWS · Kubernetes (K3s/K3d) · Docker · Terraform · FluxCD · GitHub Actions · Prometheus/Grafana/Loki · Python/Go/Bash

## 🚀 Featured Projects
### Production Kubernetes Cluster (pi-cluster)
- GitOps with FluxCD and Kustomize; 100% environment consistency
- Observability with Prometheus/Grafana; MTTR improvement
- Edge-ready with Raspberry Pi and K3s; AI/LLM inference readiness
Repo: https://github.com/bmacharia/pi-cluster

### CI/CD Pipeline Automation (devops-study-app)
- End-to-end GitHub Actions: lint (Ruff), test (PyTest), scan (Trivy), release (Release Please)
- DevContainers for standardized developer environments
- K3d deployment validation with zero-downtime rollout patterns
Repo: https://github.com/bmacharia/devops-study-app

## 🧭 Architecture (ASCII)
Users → Ingress → Kubernetes (K3s) → Deployments/Services → FluxCD (reconcile)
                              ↘ Observability: Prometheus/Grafana
CI → GitHub Actions → Build → Test → Scan(Trivy) → Push → Deploy via GitOps
