# kubernetes-deployment
Create a Kubernetes deployment configuration file (in YAML) for a web application. The deployment should have 3 replicas, use the nginx:latest image, and expose port 80. The configuration should also include a liveness probe and a readiness probe, also it should have guaranteed QOS for deployments.


In this i have used this command to ensures that the state of your Kubernetes cluster matches the desired state described in the configuration file.
kubectl apply -f nginx-deployment.yaml

to check the pods are running or not
kubectl get pods
