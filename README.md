# appTestKubernates

## commands
kubectl rollout status deployment/frontend-dp
kubectl describe deployment frontend-dp
kubectl get all
kubectl get pods
minikube start 
minikube stop
minikube delete (cluster remove)
kubectl create -f pods/pods.yaml
kubectl get replicasets
kubectl create -f replicasets/rs1.yaml
kubectl delete pod nginx
kubectl get replicationcontroller
kubectl create -f deployments/dp.yaml
kubectl create -f deployments/frontend.yaml --save-config
kubectl apply -f deployments/frontend.yaml
minikube ip
minikube service frontend-svc --url
kubectl create -f services/frontend-svc.yaml --save-config --record
kubectl create -f deployments/frontend-dp.yaml --save-config --record







