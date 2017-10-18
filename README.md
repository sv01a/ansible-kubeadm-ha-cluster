# Ansible playbook for CentsOS 7 ONLY!

High available Kubdeadm(v.1.7.5) cluster ansible playbook. Inspired by [https://github.com/cookeem/kubeadm-ha]

Prerequests:
- CentOS 7+
- Docker 1.12+

HOWTO:
- rename inventory.example to inventory 
- set your cluster info in inventory file 
- run `ansilbe-playbook k8s-cluster.yml`

If in inventory set only 1 master, playbook will deploy standard kubeadm cluster.

# TODO:
- token generation
- e2e tests