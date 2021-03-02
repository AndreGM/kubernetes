<h1 align="center">Welcome to Kubernetes 👋 A Kubernetes POC project</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
</p>

> Semana kubeDev 2.0

### 🏠 [Homepage](https://kubedev.io/semana/)

## Install

```sh
k3d cluster create meucluster -p "8080:30000@loadbalancer" --servers 1 --agents 2
```

```sh
kubectl apply -f ./k8s/mongodb/
```

```sh
kubectl apply -f ./k8s/api/
```

## Useful commands

#### Status info

```sh
kubectl get all
```
#### Removing

```sh
k3d cluster delete meucluster
```


## Author

👤 **Fabricio Veronez**


## Student

👤 **Andre Gomes**


## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/AndreGM/kubernetes/issues).

