# weasel-k8s-manifests
weasel-kubernetes-manifests

## 파일 구조

```
.
├── README.md
└── weasel
    ├── argocd
    │   └── argocd-ingress.yaml
    ├── backend
    │   ├── weasel-backend-deployment.yaml
    │   ├── weasel-backend-hpa.yaml
    │   └── weasel-backend-service.yaml
    ├── grafana
    │   ├── grafana-deployment.yaml
    │   ├── grafana-ingress.yaml
    │   ├── grafana-pvc.yaml
    │   └── grafana.service.yaml
    ├── karpenter
    │   ├── controller-policy.json
    │   ├── controller-trust-policy.json
    │   ├── karpenter.yaml
    │   └── nodepool.yaml
    ├── prometheus
    │   └── prometheus-ingress.yaml
    ├── weasel-ingress.yaml
    └── weasel-ns.yaml
```