# Kubernetes Roboshop Project

This repository showcases a complete deployment of the Roboshop microservices application on Kubernetes, designed to simulate a real-world e-commerce platform using modern DevOps practices.
The project demonstrates how to deploy, manage, and scale multiple interconnected services in a Kubernetes cluster using YAML manifests.

# Project Overview
Roboshop is a microservices-based e-commerce application consisting of multiple independent services such as frontend, backend services, databases, and messaging systems.
Each component is containerized and deployed into Kubernetes as separate workloads.
Typical services included in Roboshop:

1. Frontend (Nginx-based UI)
2. Catalogue Service
3. User Service
4. Cart Service
5. Payment Service
6. Shipping Service
7. Databases (MongoDB, MySQL, Redis)
8. Messaging Queue (RabbitMQ)

# Kubernetes Components Used
This project uses core Kubernetes resources:

1. Deployments – Manage stateless services
2. StatefulSets – Manage databases
3. Services (ClusterIP / NodePort) – Enable communication
4. ConfigMaps & Secrets – Manage configuration
5. Persistent Volumes (PV & PVC) – Store data reliably
6. Namespaces – Logical separation of resources
