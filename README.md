# k8s
# Task in kubernetes

* Dockarize our last two assignment bitcoint  and ynet applications

*  Create Kubernetes manifests (Deployment and service)

*  Enable Ingress Controller on my cluster

*  Create an ingress that directs the traffic to the correct service

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
# Result 
Each App have her own path running on the local host
for bitcoin app 

http://localhost/bitcoin
![bitcoin](https://user-images.githubusercontent.com/57920502/205525283-c5c176a3-533e-40a8-8353-155b7da1ed72.jpeg)

for ynet app

http://localhost/ynet
![ynet](https://user-images.githubusercontent.com/57920502/205525285-a5e96b04-3c32-4130-b805-49029c17f4f6.jpeg)


# Dockerimage/containers on DockerHub
![dockerhub](https://user-images.githubusercontent.com/57920502/205525297-f8289dd5-99a0-4db0-8aba-0df25c8195e5.png)




  
