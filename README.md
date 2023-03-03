# Usage
This playbook will change the domain alias of a cluster. This includes the API and Ingress.

The playbook will also update your kubeconfig with the new cluster name, and update the kubeconfig with the new certificate authority data.

```
export KUBECONFIG=~/path/to/kubeconfig
ansible-playbook rename-playbook.yaml -e "domain=new_cluster_name.domain.com"
```
