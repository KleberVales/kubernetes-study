# kubernetes-study

## [Introduction to Kubernetes](https://github.com/KleberVales/kubernetes-study/wiki/01-Introduction-to-Kubernetes)

- What is Kubernetes?
- Docker

## Kubernetes Architecture

- Cluster
- Control Plane & Worker Nodes

## Kubernetes Components

- Application in the cluster
- Control Plane Components
- Worker Node Components

## Kubernetes Networking

- Service
- Ingress
- Ingress Controller (Nginx, Traefik)
- DNS no Kubernetes
- Comunicação entre Pods

## Configuration and Secrets

- ConfigMap
- Secret
- Environment Variables
- Externalize settings (12-factor app)

## Storage

- Volumes
- PersistentVolume (PV)
- PersistentVolumeClaim (PVC)
- StorageClass
- Stateful apps (PostgreSQL, Kafka, etc.)

## Scalability and High Availability

- Horizontal Pod Autoscaler (HPA)
- Vertical Pod Autoscaler (VPA)
- Auto-scaling baseado em CPU/memória
- Rolling Update
- Rollback
- Self-healing (restart, reschedule)

## Observability and Monitoring

- Liveness Probe
- Readiness Probe
- Startup Probe
- Logs de Pods
- Metrics Server
- Prometheus
- Grafana

## Security in Kubernetes

- RBAC
- ServiceAccount
- Namespace
- Network Policies
- Secrets vs Vault
- Pod Security Standards

## Deployment and Automation

- Manifests YAML
- Helm (charts, values)
- Kustomize
- GitOps (ArgoCD / Flux)
- Deploy de microserviços Spring Boot

## Kubernetes for Java Backend / Microservices

- Spring Boot Deployment on Kubernetes
- Profile Configuration
- Health Checks (Actuator)
- Kafka on Kubernetes
- Synchronous vs. Asynchronous Communication
- Circuit Breaker + Retries

## Basic Commands
