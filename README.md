# Run
```sh
ansible-playbook -i inventory.yaml playbook.yaml
```


# MicroCeph
* https://microk8s.io/docs/how-to-ceph
* https://www.virtualizationhowto.com/2023/08/kubernetes-persistent-volume-setup-with-microk8s-rook-and-ceph/

# TODO
* Split into multiple playbooks since the current one is dealing with both installing k8s and fish shell etc.
* Multi node cluster would require rook-ceph and single node would use hostpath-storage
* One playbook for master nodes and another for worker nodes?
