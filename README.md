# Ansible_Kubernetes_Deploy  / Ubuntu 22
Deploy Kube with Ansible (using flannel)

1. ansible-playbook -i hosts users.yml
2. ansible-playbook -i hosts install-k8s.yml
3. ansible-playbook -i hosts master.yml (debug piece needs some fixin for join part.)
4. ansible-playbook -i hosts join-workers.yml
5. https://github.com/kubernetes-sigs/metrics-server
6. https://github.com/kubernetes/dashboard
7. https://kubernetes.io/docs/tasks/job/automated-tasks-with-cron-jobs/ (apiVersion: batch/v1beta1)


Ref: https://buildvirtual.net/deploy-a-kubernetes-cluster-using-ansible/
