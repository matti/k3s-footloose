# k3s-footloose

[footloose](https://github.com/weaveworks/footloose) [k3s](https://github.com/rancher/k3s) cluster

```
bin/k3s-footloose
export KUBECONFIG=./k3s.yaml
kubectl get node -o wide
kubectl get pod --all-namespaces

curl localhost
# --> default backend 404
```
