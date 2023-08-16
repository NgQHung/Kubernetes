# Kubernetes

// create a pod
kubectl apply -f https://k8s.io/examples/controllers/nginx-deployment.yaml
kubectl get all
// scale deployment to 5
kubectl scale deployment nginx-deployment -- replicas 5
// delete a pod or deployment
kubectl delete deployment/pod namespace
