# Ansible_Kubernetes_Deploy
Deploy Kube with Ansible (using flannel)

1. ansible-playbook -i hosts users.yml
2. ansible-playbook -i hosts install-k8s.yml
3. ansible-playbook -i hosts master.yml (debug piece needs some fixin for join part.)
4. ansible-playbook -i hosts join-workers.yml

Ref: https://buildvirtual.net/deploy-a-kubernetes-cluster-using-ansible/
