# Kubernetes GitOps DevOps Project

A production-grade Kubernetes infrastructure built with GitOps principles,
automated deployments, and full observability stack.

## Architecture Overview

Git Push → ArgoCD → Kubernetes Cluster → Prometheus → Grafana

## Features

- GitOps Pipeline — ArgoCD watches Git and auto-deploys on every push
- Local Git Server — Gitea running inside the cluster
- Kubernetes Deployment — Multi-replica Node.js app with self-healing
- Horizontal Pod Autoscaler — CPU-based auto-scaling
- Helm Chart Packaging — Production-ready chart structure
- Full Monitoring Stack — Prometheus + Grafana with 15+ pre-built dashboards
- Metrics Server — Real-time resource metrics

## Tech Stack

- Kubernetes — Container orchestration
- ArgoCD — GitOps continuous delivery
- Gitea — In-cluster Git server
- Helm — Kubernetes package manager
- Prometheus — Metrics collection
- Grafana — Monitoring dashboards
- Docker Desktop — Local cluster

## What I Learned

- Container orchestration and self-healing systems
- GitOps deployment methodology
- Infrastructure observability and alerting
- Helm chart packaging for production
- Kubernetes networking and scaling

## Author

Georges El-Khoury — Systems and Network Engineering Student