# minikube
https://quarkus-seminar.github.io/2024-lab-minikube/#_start_minikube

## Troubleshooting

After
```bash
minikube addons enable metrics-server
minikube addons enable dashboard
```
you have to:
```bash
minikube stop
minikube start
```

