# Testing
```bash
kubectl apply \
    -f egress-configmap.yaml \
    -f egress-deployment.yaml \
    -f egress-service.yaml \
    -f snapt-deployment.yaml \
    -f snapt-service.yaml
```