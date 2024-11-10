
# Kubernetes Setup Instructions with Minikube

1. **Start Minikube**:
   ```
   minikube start
   ```
   This will create a local Kubernetes cluster on your machine.

2. **Verify Cluster is Running**:
   ```
   kubectl cluster-info
   ```

3. **Deploying a Sample Application**:
   ```
   kubectl create deployment hello-node --image=k8s.gcr.io/echoserver:1.4
   kubectl expose deployment hello-node --type=LoadBalancer --port=8080
   minikube service hello-node
   ```

4. **Stopping Minikube**:
   ```
   minikube stop
   ```
