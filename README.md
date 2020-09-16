# 1.Kubectl basic commands:

## General:

```bash
kubectl --help
kubectl get nodes
kubectl get cluster-info

```

## RUN:

```bash
kubectl run nginx --image=nginx
```

## PODS:

```bash
kubectl get pods
kubectl get pods -o wide
kubectl describe pods <podname>
kubectl create -f pod-definition.yaml
```

# 2.YAML file kind and version values

|    kind    | version |
| :--------: | :-----: |
|    POD     |   v1    |
|  Service   |   v1    |
| ReplicaSet | apps/v1 |
| Deployment | apps/v1 |
