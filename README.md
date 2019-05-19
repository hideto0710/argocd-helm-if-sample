# argocd-helm-if-sample

## Install
```bash
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v1.0.0/manifests/install.yaml

kubectl create ns ifsample
kubectl apply -f application.yaml
```
