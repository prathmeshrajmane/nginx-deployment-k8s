# nginx-deployment-k8s
Creating a Kubernetes deployment


kubectl apply -f nginx-deployment.yaml --record


-------------------------------

kubectl get all


-------------------------------------

kubectl describe deployment nginx-deployment

----------------------------------

kubectl expose deployment nginx-deployment --type=LoadBalancer --name=nginx-web-server

-------------------------------------

kubectl get services
