kubectl apply -f /opt/k8s/k8s-yaml/k8s/ingress/deploy.yaml
kubectl apply -f /opt/k8s/k8s-yaml/k8s/ingress/nginx.yaml

kubectl delete -f /opt/k8s/k8s-yaml/k8s/ingress/nginx.yaml --force --wait=false

