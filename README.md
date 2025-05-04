kubectl apply -f elk-stack.yml  
kubectl port-forward -n kube-system service/logstash-service 5044:5044   
