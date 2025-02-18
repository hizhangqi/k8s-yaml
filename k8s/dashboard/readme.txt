kubectl apply -f /opt/k8s/k8s-yaml/k8s/dashboard/rbac.yaml
kubectl apply -f /opt/k8s/k8s-yaml/k8s/dashboard/recommend.yaml


kubectl -n kubernetes-dashboard create token dashboard-admin --duration=87600h
