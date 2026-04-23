# K3s GitOps Observability 🚀

Production K3s HA cluster (3-nodes) + GitOps ArgoCD + full observability.

**Cluster Live:** ceph-0, dev1, ops1 (K3s v1.35.3)

## 📦 Deployed
- ✅ **Harbor** Private Registry: harbor.okfe.net
- 🔄 **ArgoCD** GitOps Controller

## 🚀 Quick Start
```bash
git clone https://github.com/matahariku/k3s-gitops-observability
kubectl apply -f apps/harbor/staging/ -n argocd
```

**CKA Certified** | [Badge](https://www.credly.com/badges/bd619a68-ce90-4a48-978c-e3bcefa0858c)
