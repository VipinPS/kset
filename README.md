# kset
Access kubernetes node and switch kubernetes Namespaces

Installation

To install kset you can just run this command:

$ curl https://raw.githubusercontent.com/VipinPS/kset/main/kset -o /usr/local/bin/kubectl-kset && chmod +x $_

To switch namespace use command and enter the Namespace name :

$ kubectl kset setns

To access AKS nodes use command and enter the Node name which you want to access:

$ kubectl kset setnode 
