# Ansible_Kubernetes_Deploy  / Ubuntu 22
Deploy Kube with Ansible (using flannel)

1. ansible-playbook -i hosts users.yml
2. ansible-playbook -i hosts install-k8s.yml
3. ansible-playbook -i hosts master.yml (debug piece needs some fixin for join part.)
4. ansible-playbook -i hosts join-workers.yml
5. https://github.com/kubernetes/dashboard

Ref: https://buildvirtual.net/deploy-a-kubernetes-cluster-using-ansible/
