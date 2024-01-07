# kubernetes

# History
 echo -n 'root' | base64
echo -n 'example' | base64
 kubectl apply -f secrets-mongodb.yml 
 kubectl get secret 
 kubectl apply -f mongodb-deployment.yml  
 kubectl get pods
   31  kubectl get pods --watch 
   32  kubectl apply -f mongodb-service.yml 
   33  kubectl describe svc mongodb-service
   34  kubectl get svc 
   35  kubectl get pods -o wide
   36  kubectl apply -f mongoexp-configmap.yml 
   37  kubectl apply -f mongoexp-deployment.yml 
   38  kubectl get pods 
   39  kubectl logs mongoexp-pod-6dc95684bb-rvhhj
   40  kubectl apply -f mongoexp-service.yml 
   41  kubectl logs mongoexp-pod-6dc95684bb-rvhhj
   42  kubectl describe svc mongoexp-service
   43  kubectl get pods -o wide
   44  kubectl get pods 
   45  kubectl log -f mongoexp-pod-6dc95684bb-rvhhj
   46  kubectl logs -f mongoexp-pod-6dc95684bb-rvhhj
