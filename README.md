# kubernetes-app
Simple Kubernetes App

# Kubernetes Test Application - Cookies
https://coreos.com/tectonic/docs/latest/tutorials/sandbox/first-app.html#simple-deployment

# Create the deployment

```
kubectl create -f simple-deployment.yaml
```

# Create the service

```
kubectl create -f simple-service.yaml
```

# Create the ingress
Let op Tony: host moet je aanpassen voor de wildcard dns (quattro).
Eerst host goed zetten in de yml en dan aanmaken in Kubernetes.

```
kubectl create -f simple-ingress.yaml
```
