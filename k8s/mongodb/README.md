```bash
kubectl apply -f ./setup -f ./
kubectl get all -n mongodb-system
```

```bash
kubectl delete --ignore-not-found=true -f ./ -f ./setup
kubectl get all -n mongodb-system
```
