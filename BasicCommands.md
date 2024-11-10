
# Kubernetes Basic Commands

## Cluster Management
- `minikube start`: Start a Minikube cluster.
- `minikube stop`: Stop a running Minikube cluster.
- `kubectl cluster-info`: View cluster information.

## Pod Management
- `kubectl get pods`: List all pods in the current namespace.
- `kubectl describe pod <pod-name>`: Detailed information on a specific pod.
- `kubectl delete pod <pod-name>`: Delete a pod.

## Deployment Management
- `kubectl create deployment <name> --image=<image>`: Create a deployment.
- `kubectl get deployments`: List all deployments.
- `kubectl scale deployment <name> --replicas=<number>`: Scale deployment.

## Service Management
- `kubectl expose deployment <name> --type=<type> --port=<port>`: Expose a deployment as a service.
- `kubectl get services`: List all services.
