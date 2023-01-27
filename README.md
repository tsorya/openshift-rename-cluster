# Usage
The playbook will update your kubeconfig with the new cluster name. It will also update the kubeconfig with the new certificate authority data.

```
export KUBECONFIG=~/path/to/kubeconfig
ansible-playbook rename-playbook.yaml -e "domain=<new_cluster_name.domain.com>"
```
