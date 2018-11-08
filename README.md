# Kubernetes Engine Starter

:beetle: A boilerplate for Kubernetes, Packer, Terraform, Drone, Traefik, Nodemon, PM2, and Babel.

[![Dependency Status](https://david-dm.org/Shyam-Chen/Kubernetes-Engine-Starter.svg)](https://david-dm.org/Shyam-Chen/Kubernetes-Engine-Starter)
[![devDependency Status](https://david-dm.org/Shyam-Chen/Kubernetes-Engine-Starter/dev-status.svg)](https://david-dm.org/Shyam-Chen/Kubernetes-Engine-Starter?type=dev)

## Getting Started

1. Clone this Boilerplate

```bash
$ git clone --depth 1 https://github.com/Shyam-Chen/Kubernetes-Engine-Starter.git <PROJECT_NAME>
$ cd <PROJECT_NAME>
```

2. Apply a config to a resource

```bash
$ kubectl apply -f k8s
```

3. Display Resources

```bash
$ kubectl get services
```

```bash
$ kubectl get deployments
```

```bash
$ kubectl get pods
```

4. Open the Dashboard

```bash
$ minikube dashboard
```

5. Access the Service

```bash
$ minikube service Kubernetes-Engine-Starter
```

## Projects

```bash
$ kubectl create namespace development
$ kubectl create namespace staging
$ kubectl create namespace production
```
