# Kubernetes

## Lab 9: Introduction to Kubernetes

## Task 1: Kubernetes Setup and Basic Deployment

In this task, I:

- installed `kubectl` and `minikube` for managing Kubernetes:
  ![which_kubectl_minikube.png](screenshots/which_kubectl_minikube.png)
- created a  `moscow-time-app` `Deployment` for `app_python`
  with `nshlyakhtin/devops:lab8-app-python-amd64` Docker image from Docker Hub:
  ![kubectl_created_deployment.png](screenshots/kubectl_created_deployment.png)
- created a `Service` to access application from outside k8s cluster network:
  ![kubectl_created_service.png](screenshots/kubectl_created_service.png)
  ![minikube_service_moscow_time_app.png](screenshots/minikube_service_moscow_time_app.png)
  ![moscow_time_app.png](screenshots/moscow_time_app.png)
- removed the created `Deployment` and `Service` resources:
  ![remove_resources.png](screenshots/remove_resources.png)

## Task 2: Declarative Kubernetes Manifests

In this task I created a `Deployement` and `Service` with manifest files:

![create_deployment_and_service_with_manifest.png](screenshots/create_deployment_and_service_with_manifest.png)
![minikube_tunnel.png](screenshots/minikube_tunnel.png)
![minikube_tunnel_output.png](screenshots/minikube_tunnel_output.png)
