# Microservices-Net5
.NET Microservice project which include two microservices using REST API pattern. Created synchronous (HTTP &amp; gRPC) and asynchronous (RabbitMQ) messaging between services using a Event Bus. Services have been deployed to the Kubernetes cluster.

## Architecture
![microservices_net5](https://user-images.githubusercontent.com/60652185/150120639-6a86cfe2-9da7-47b2-973f-1e05b22ffb88.png)

## Usage
You must use yaml files in the K8S folder. 
For deploying pods and services to the Kubernetes, you can use apply command.
```
kubectl apply -f <filename.yaml>
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.1.0/deploy/static/provider/aws/deploy.yaml
```
After apply the all yaml files you will able to use services. You can check the Docker Desktop and see the pods and containers.

If all pods and containers are work currectly, you can try to use services with programs like Postman or Insomnia.
