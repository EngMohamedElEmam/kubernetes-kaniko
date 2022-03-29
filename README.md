# kubernetes kaniko Examples With jenkins

Builiding Docker images using kaniko on Kubernetes pods

Full Documenation: https://devopscube.com/build-docker-image-kubernetes-pod/

## Tech: Github + Dockerhub + Kubernetes

### Create Kube Secret
```
kubectl create secret \
    docker-registry regcred \
    --docker-server=https://aks.azurecr.io \
    --docker-username=$REGISTRY_USER \
    --docker-password=$REGISTRY_PASS \
    --docker-email=$REGISTRY_EMAIL
```






