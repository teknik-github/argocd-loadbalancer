# argocd loadbalancer
```bash
kubectl get svc -n argocd # untuk melihat ip external pada service argocd
kubectl exec pod -- argocd admin initial-password # untuk mengetahui password admin argocd
```