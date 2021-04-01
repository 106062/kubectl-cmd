# kubectl-cmd

指令備忘錄

``` bash
# 取得 cluster Name
kubectl config get-contexts

# 切換 cluster
kubectl config use-context ${name}

# get namespace
kubectl get ns/namespace

# get service
kubectl get service/svc

# get storage cluster
kubectl get storage cluster/sc

# log/describe svc
kubectl describe/logs ${svc}/${name} -n ${namespace}
```

- [kube.io](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands)
