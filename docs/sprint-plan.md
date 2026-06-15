# Sprint Plan

## Sprint 0 - Project Setup
Prepare local workstation, tools, Git repository, folder structure, and naming standards.

## Sprint 1 - Terraform Remote Backend
Create Azure Storage Account and Blob Container for Terraform remote state.

## Sprint 2 - Azure Infrastructure
Provision AKS, ACR, networking, Key Vault, Log Analytics using Terraform.

## Sprint 3 - Kubernetes Base Setup
Create namespaces, base RBAC, and cluster structure.

## Sprint 4 - Demo Application
Build and deploy order-api with metrics and failure endpoints.

## Sprint 5 - Custom Exporter
Build custom business metric exporter.

## Sprint 6 - Monitoring Stack
Install Prometheus, Grafana, and Alertmanager.

## Sprint 7 - Golden Signals Dashboard
Create dashboard for latency, traffic, errors, and saturation.

## Sprint 8 - SLO and Error Budget Dashboard
Create SLI/SLO and burn-rate dashboard.

## Sprint 9 - Alertmanager Rules
Configure PrometheusRule and Alertmanager routing.

## Sprint 10 - Auto-Remediation Webhook
Build Python webhook that receives alerts and remediates failures.

## Sprint 11 - RBAC Hardening
Apply least-privilege permissions for remediation service.

## Sprint 12 - Loki Logging
Install Loki and Promtail for log aggregation.

## Sprint 13 - Failure Testing
Trigger failures and prove auto-healing.

## Sprint 14 - MTTR Measurement
Measure before/after recovery time.

## Sprint 15 - Enterprise Hardening
Add cooldown, audit logs, security token, runbook, and demo documentation.
