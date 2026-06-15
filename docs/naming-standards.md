# Naming Standards

## Project

Project short name: sreobs  
Environment: dev  
Primary Azure region: eastus  

## Azure Resources

| Resource | Naming Format | Example |
|---|---|---|
| Resource Group | rg-<project>-<env> | rg-sreobs-dev |
| AKS Cluster | aks-<project>-<env> | aks-sreobs-dev |
| ACR | acr<project><env>001 | acrsreobsdev001 |
| Key Vault | kv-<project>-<env> | kv-sreobs-dev |
| Log Analytics | log-<project>-<env> | log-sreobs-dev |
| VNet | vnet-<project>-<env> | vnet-sreobs-dev |
| Subnet | snet-<purpose>-<env> | snet-aks-dev |
| Storage Account | st<project><purpose><env>001 | stsreobstfdev001 |

## Kubernetes Namespaces

| Namespace | Purpose |
|---|---|
| apps | Application workloads |
| monitoring | Prometheus, Grafana, Alertmanager |
| logging | Loki and Promtail |
| remediation | Auto-healing service |
