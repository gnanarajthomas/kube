# Install Kubernetes cluster

Cluster: 1 Master Node and 2 Worker Nodes

OS: Ubuntu 18.04
Ansible Version: 2.5.1
kubeadm Version: 1.20.4-00 Kubernetes Cluster Bootstrapping Tool                                       
kubectl Version: 1.20.4-00 Kubernetes Command Line Tool
kubelet Version: 1.20.4-00 Kubernetes Node Agent


Run the playbooks in the below order
Playbook Order:
-- kube-initial.yml
-- kube-prepare.yml
-- kube-master.yml
-- kube-worker.yml

