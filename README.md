# Helm Kubernetes Lab 🚀

Basic Helm practice tasks performed on Kubernetes using Minikube and Linux Mint.

## What I Learned

- Creating Helm charts
- Using `values.yaml`
- Editing Helm templates
- Working with `_helpers.tpl`
- Creating Kubernetes Deployments and Services
- Using ConfigMaps and environment variables
- Helm upgrades and rollbacks
- Helm lint and dry-run validation

---

## Helm Commands Used

```bash
helm create mywebapp
helm install myrelease .
helm upgrade myrelease .
helm rollback myrelease 1
helm history myrelease
helm lint .
```

---

## Kubernetes Commands Used

```bash
kubectl get pods
kubectl get svc
kubectl get configmap
kubectl get pods --show-labels
minikube service myrelease
```

---

## Kubernetes Concepts Practiced

- Pods
- Deployments
- Services
- ConfigMaps
- Labels & Selectors
- Replica Scaling
- Environment Variables

---

## Tech Used

- Kubernetes
- Helm
- Minikube
- Docker
- Linux Mint
- YAML
