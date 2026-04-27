# 🚢 Kubernetes Deployment Generator Prompt

Generate production-ready Kubernetes manifests including Deployments, Services, and Ingress.

## Prompt

```text
Act as a Site Reliability Engineer (SRE). Generate Kubernetes manifests for [APP NAME].

Container Image: [e.g., my-app:latest]
Replicas: [NUMBER]
Port: [NUMBER]
Config: [e.g., Requires env vars for DB_URL and API_KEY]

Include:
1. Deployment with resource limits and liveness/readiness probes.
2. ClusterIP or LoadBalancer Service.
3. Ingress resource with TLS configuration.
4. HorizontalPodAutoscaler (HPA) definition.
```
