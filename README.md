# Quick start

Update the inventory with your server details

```sh
ansible-playbook -i inventory.yaml main.yaml --ask-become-pass
```

# MicroK8s

* https://microk8s.io/docs/clustering

# MicroCeph

* https://microk8s.io/docs/how-to-ceph
* https://www.virtualizationhowto.com/2023/08/kubernetes-persistent-volume-setup-with-microk8s-rook-and-ceph/

# TODO

* The playbook currently only support one master node. It should be possible to deploy with multiple master nodes
* Remove sudo without password capabilities as a final step
* Make Ceph cluster deployment idempotent
