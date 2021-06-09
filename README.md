# K8S
 Play around with the kubernetes: Reference : https://kubernetes.io/docs/tasks/tools/
 
Prerequesite: (K8S in windows)
1. Docker installed in your windows machine
2. Kubectl (Get it from here >>> https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/)
3. Minikube (Get it from here >>> https://minikube.sigs.k8s.io/docs/start/)

Step- 1: Start the docker in your windows machine 

Step- 2: Start the minikube by running the following command: "minikube start"

Note: minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes.

Step- 3: run "minikube status", to get the running status.

Step- 4: run "kubectl get nodes", to get the information about the running nodes (minikube). 

Note:  kubectl, allows you to run commands against Kubernetes clusters. You can use kubectl to deploy applications, inspect and manage cluster resources, and view logs.

Step- 5: run the deploy.yaml file to start the sample "Selenium-hub" which is specified in the yaml file.

Step- 6: run the service.yaml file to start the services the kubernetes port service.

Step- 7: run the rep.yaml file to start the chrome nodes for the selenium grid.

