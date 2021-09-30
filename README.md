## [kubernetes-samples](#kubernetes-sample)
We wll be exploring various Kubernetes objects in order to understand what they’re used for and the different options they offer you. 
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
kubectl get pods
kubectl describe pod <podName>
kubectl logs -f <podName>
kubectl delete pod <podName>

```

## [References](#references)

- [kubectl cheatsheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)