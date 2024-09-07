# Build and Run the Docker Container
docker build -t computer-vision-app .
docker run -d -p 5000:5000 computer-vision-app

# Apply Kubernetes Configurations
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
