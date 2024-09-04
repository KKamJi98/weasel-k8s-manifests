# weasel-k8s-manifests

[Weasel-link](https://github.com/Team-S5T1)

## 파일 구조

```
.
├── README.md
└── weasel
    ├── al2
    │   └── al2.yaml
    ├── backend
    │   ├── weasel-backend-deployment.yaml
    │   ├── weasel-backend-hpa.yaml
    │   ├── weasel-backend-service.yaml
    │   └── weasel-backend-spc.yaml
    ├── efk
    │   ├── elasticsearch.yaml
    │   └── kibana.yaml
    ├── grafana
    │   ├── grafana-deployment.yaml
    │   ├── grafana-pvc.yaml
    │   └── grafana.service.yaml
    ├── ingress
    │   ├── application
    │   │   ├── argocd-ingress.yaml
    │   │   └── weasel-ingress.yaml
    │   └── monitoring
    │       ├── log
    │       │   ├── elasticsearch-ingress.yaml
    │       │   └── kibana-ingress.yaml
    │       └── resource
    │           ├── grafana-ingress.yaml
    │           └── prometheus-ingress.yaml
    ├── karpenter
    │   ├── controller-policy.json
    │   ├── controller-trust-policy.json
    │   ├── karpenter.yaml
    │   └── nodepool.yaml
    └── namespaces
        └── weasel-ns.yaml
```
