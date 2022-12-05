# k8s
# Task in kubernetes

1.Dockarize our last two assignment bitcoint  and ynet applications
2.Create Kubernetes manifests (Deployment and service)
3.Enable Ingress Controller on my cluster
4.Create an ingress that directs the traffic to the correct service

## Run Locally

Clone the project

```bash
  git clone https://github.com/medhasm/k8s.git
```

Go to the project directory

```bash
  cd k8s
```

Run (Open CLI)

```bash
 1. minikube start
```


```bash
 2. kubectl apply -f . 
  ```
  ```bash
 3. minikube addons enable ingress
```
  ```bash
  4.minikube tunnel
```


  
