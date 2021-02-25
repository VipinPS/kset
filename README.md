# kset
A Kubernetes plugin to access kubernetes node and switch kubernetes Namespaces.

# Installation

To install kset you can just run this command:
```
curl https://raw.githubusercontent.com/VipinPS/kset/main/kset -o /usr/local/bin/kubectl-kset && chmod +x $_
```
To switch namespace use command and then enter the namespace name:
```
$ kubectl kset ns
```
To access Kubernetes nodes use command and then enter the node name which you want to access:
```
$ kubectl kset node 
```
