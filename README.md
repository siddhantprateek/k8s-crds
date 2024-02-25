# k8s-crds

Requirements:
- `Kubernetes` (minikube)


## Setting up 

- Create custom resource defination 
```bash
kubectl apply -f definition/custom-definition.yml
```

- Create custom resource
```bash
kubectl apply -f resources/*
```