# Run
```sh
ansible-playbook -i inventory.yaml playbook.yaml
```

# TODO
* Split into multiple playbooks since the current one is dealing with both installing k8s and fish shell etc.
* Multi node cluster would require rook-ceph and single node would use hostpath-storage
* One playbook for master nodes and another for worker nodes?
