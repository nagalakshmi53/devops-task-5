# Task 5 - Kubernetes Cluster with Minikube (Theory-Based Submission)

## 📝 Overview

This task is part of the DevOps Internship and focuses on understanding how to deploy and manage applications using Kubernetes and Minikube. Due to tool limitations, I have not executed the commands but have prepared all the required configuration files and included theoretical explanations.

## 📦 What This Repo Contains

- `deployment.yaml`: A sample Deployment file for running an Nginx container.
- `service.yaml`: A Service file to expose the Nginx app using NodePort.
- `README.md`: Explanation of the task and setup.
- `interview_questions.md`: Answers to commonly asked Kubernetes interview questions (optional if you want to add).

## 🔧 What Would Be Done (If Tools Were Available)

1. **Install Minikube** and start the cluster:
   - `minikube start`

2. **Deploy an app using YAML**:
   - `kubectl apply -f deployment.yaml`

3. **Expose the app with a Service**:
   - `kubectl apply -f service.yaml`

4. **Verify the pods**:
   - `kubectl get pods`

5. **Scale the deployment**:
   - `kubectl scale deployment nginx-deployment --replicas=3`

6. **View logs and descriptions**:
   - `kubectl describe pod <pod-name>`
   - `kubectl logs <pod-name>`

## ❓ Kubernetes Interview Questions

- What is Kubernetes?
- What is the role of kubelet?
- Explain Pods, Deployments, and Services.
- How do you scale in Kubernetes?
- What is a Namespace?
- Difference between ClusterIP, NodePort, LoadBalancer.
- What are ConfigMaps?
- How do you perform rolling updates?

.

