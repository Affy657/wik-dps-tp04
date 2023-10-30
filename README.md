kubectl delete -f minikube.yaml 
kubectl apply -f minikube.yaml
kubectl get pods -n ad
kubectl port-forward  pods/tp04-1 -n ad 3000:8080
kubectl get pods tp04-1