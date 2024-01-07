# kubernetes


# Mongodb
1) https://hub.docker.com/_/mongo
2) https://hub.docker.com/_/mongo-express

# History
1) echo -n 'root' | base64
2) echo -n 'example' | base64
3) kubectl apply -f secrets-mongodb.yml
4) kubectl get secret
5) kubectl apply -f mongodb-deployment.yml
6) kubectl get pods
7) kubectl get pods --watch
8) kubectl apply -f mongodb-service.yml
9) kubectl describe svc mongodb-service
10)  kubectl get svc
11)  kubectl get pods -o wide
12)  kubectl apply -f mongoexp-configmap.yml
13)  kubectl apply -f mongoexp-deployment.yml
14)  kubectl get pods
15)  kubectl logs mongoexp-pod-6dc95684bb-rvhhj
16)  kubectl apply -f mongoexp-service.yml
17)  kubectl logs mongoexp-pod-6dc95684bb-rvhhj
18)  kubectl describe svc mongoexp-service
19)  kubectl get pods -o wide
20)  kubectl get pods
21)   kubectl log -f mongoexp-pod-6dc95684bb-rvhhj

  
 
