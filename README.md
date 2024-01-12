### Deployment, Service, Ingress

```
minikube addons enable ingress
```

```
kubectl apply -f .
```

```
curl http://arch.homework/health 
```

```
kubectl delete deploy test-docker-service-deployment
```

```
kubectl delete service test-docker-service-service
```

```
kubectl delete ingress test-docker-service-ingress
```