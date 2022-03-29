```bash
kubectl apply -f ./setup -f ./
kubectl get all -n mysql-system
```

```bash
kubectl delete --ignore-not-found=true -f ./ -f ./setup
kubectl get all -n mysql-system
```
