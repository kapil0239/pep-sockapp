# pep-sockapp

Steps to Install sockapp on kubernetes:
1. Create a namespace:
kubectl create ns <namespace_name>

2. Install helm chart:
helm install pep-app . -n <namespace_name>
