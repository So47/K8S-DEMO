## Description

Kubernetes YAML files to configure and depliy Mongo and web application pods.


**For getting all pods**

```
kubectl get pods
```
**For pod logs**

```
kubectl logs <webapp-pod-name>
```

**Get Service**

```
kubectl get service webapp-service
```

**Get the IP Address of Your Kubernetes Node**

```
minikube ip
```

**Get Nodes**

```
kubectl get nodes -o wide
```

**Update or add yaml file to k8s**

```
kubectl apply -f webapp.yaml
```

**Get URL to access the webapp**

```
kubectl apply -f webapp.yaml
```
