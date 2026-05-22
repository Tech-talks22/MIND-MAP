1️⃣ Kubernetes Basics

What is Kubernetes (K8s)

Why Kubernetes?

Containers vs VMs

Kubernetes Architecture

Cluster

Node

Control Plane

Worker Node

2️⃣ Kubernetes Architecture
Control Plane Components

API Server

etcd

Scheduler

Controller Manager

Cloud Controller Manager

Worker Node Components

kubelet

kube-proxy

Container Runtime (Docker, containerd, CRI-O)

3️⃣ Core Objects

Pod

Single-container pod

Multi-container pod

ReplicaSet

Deployment

StatefulSet

DaemonSet

Job

CronJob

4️⃣ Pod Concepts

Pod lifecycle

Pod phases

Init Containers

Sidecar Containers

Pod Restart Policy

Pod vs Container

5️⃣ Networking

Kubernetes Networking Model

Pod-to-Pod communication

Node-to-Pod communication

Service-to-Pod communication

Services

ClusterIP

NodePort

LoadBalancer

ExternalName

Headless Service

Ingress

Ingress Controller

Ingress Rules

Path-based routing

Host-based routing

6️⃣ CNI (Container Network Interface)

What is CNI?

Why CNI is required?

Popular CNI plugins:

Calico

Flannel

Weave

Cilium

How CNI works internally

7️⃣ Storage
Volumes

emptyDir

hostPath

configMap

secret

Persistent Storage

PersistentVolume (PV)

PersistentVolumeClaim (PVC)

StorageClass

Dynamic Provisioning

8️⃣ Configuration Management

ConfigMaps

Secrets

Environment Variables

Mounting ConfigMaps & Secrets
9️⃣ Scheduling

Scheduler

Labels & Selectors

Node Selector

Node Affinity

Pod Affinity & Anti-Affinity

Taints & Tolerations

🔟 Resource Management

CPU & Memory Requests

CPU & Memory Limits

Quality of Service (QoS)

Guaranteed

Burstable

BestEffort

1️⃣1️⃣ Scaling

Manual Scaling

Horizontal Pod Autoscaler (HPA)

Vertical Pod Autoscaler (VPA)

Cluster Autoscaler

1️⃣2️⃣ Health Checks

Liveness Probe

Readiness Probe

Startup Probe

1️⃣3️⃣ Security

RBAC

Service Accounts

Roles & ClusterRoles

RoleBinding & ClusterRoleBinding

Network Policies

Pod Security Standards (PSS)

1️⃣4️⃣ Observability

Logs

Metrics

Monitoring (Prometheus)

Visualization (Grafana)

Events

1️⃣5️⃣ Controllers & Operators

Controllers

Operator Pattern

Custom Resource Definition (CRD)

Custom Controllers

1️⃣6️⃣ Kubernetes YAML

YAML structure

apiVersion

kind

metadata

spec

status

1️⃣7️⃣ kubectl Commands

kubectl get

kubectl describe

kubectl apply

kubectl delete

kubectl logs

kubectl exec

kubectl scale

1️⃣8️⃣ Deployment Strategies

Rolling Update

Recreate

Blue-Green Deployment

Canary Deployment

1️⃣9️⃣ Kubernetes vs Docker Swarm

Architecture

Networking

Scaling

Load Balancing

Production readiness

2️⃣0️⃣ Real-Time Use Cases

Microservices deployment

CI/CD with Kubernetes

Zero downtime deployment

Auto scaling production apps

Multi-cloud deployments
