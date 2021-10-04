<img src="img/header.png" width="350" height="200">

## [kubernetes-examples](#kubernetes-examples)
We will be exploring various Kubernetes objects in order to understand what they’re used for and the different options they offer you. 
We will also look at some examples of how to create these objects. 

## [Prerequisite](#prerequisite)
* Docker and kubernetes cluster (Docker desktop)
* kubectl

## [Scratch Pad](#scratch-pad)
```

kubectl api-resources
kubectl get nodes
kubectl describe node docker-desktop
kubectl apply -f <ymlfile>
#Namespaces
kubectl get pods
kubectl describe pod <podName>
kubectl logs -f <podName>
kubectl delete pod <podName>
#Namespaces
kubectl get namespaces
kubectl create namespace <nameSpace>
kubectl get pods -n <nameSpace>
kubectl describe pod <podName> -n <nameSpace>
kubectl delete namespace <nameSpace>
kubectl get pods --all-namespaces
#ConfigMaps
kubectl get configmap
kubectl delete configmap <configmapName>
```

## [References](#references)

- [kubectl cheatsheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

