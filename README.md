# local-kube
Command to enable the load balancer
kubectl proxy

Command to get token to log into dashboard:
kubectl -n kubernetes-dashboard create token kubernetes-dashboard-admin-service-account
http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/#/workloads?namespace=default