# pep-sockapp

Steps to Install sockapp on Kubernetes:

1. Create a namespace:
   ```bash
   kubectl create ns <namespace_name>

2. Install helm chart:
   ```bash
   helm install pep-app . -n <namespace_name>
