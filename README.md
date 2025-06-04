# ☸️ k8s-troubleshooting

Welcome to the Kubernetes Troubleshooting repository! This repository is dedicated to exploring and providing solutions for common issues encountered when deploying and managing applications on Kubernetes. Whether you're a beginner or an experienced user, understanding these concepts is crucial for maintaining healthy and resilient Kubernetes clusters.

## 📚 Concepts Covered

This guide delves into the specifics of several key troubleshooting areas and fundamental Kubernetes concepts:

### 1. ImagePullBackOff

Learn why your pods might be stuck in an ImagePullBackOff state. This section covers common causes such as incorrect image names, private registry authentication issues, network problems, and misconfigured imagePullSecrets.

### 2. CrashLoopBackOff

Understand the dreaded CrashLoopBackOff status, indicating that a container in your pod is repeatedly starting, crashing, and restarting. We explore debugging techniques for application errors, misconfigurations, resource constraints, and startup probes.

### 3. Node Affinity

Discover how to strategically schedule your pods to specific nodes based on labels. Node Affinity offers more flexible and expressive rules than nodeSelector, allowing for both required and preferred scheduling constraints. This is essential for performance, cost optimization, and adherence to licensing requirements.

### 4. Node Selector

Get familiar with Node Selector, a straightforward method for constraining a pod to run on nodes with a specific label. While simpler than Node Affinity, it's a fundamental tool for basic node-specific scheduling.

### 5. StatefulSet with Persistent Volume

Explore the intricacies of managing stateful applications in Kubernetes using a StatefulSet. This section highlights how StatefulSets provide stable, unique network identifiers and ordered deployment/scaling for pods, and crucially, how they integrate with Persistent Volumes (PVs) and Persistent Volume Claims (PVCs) to ensure data persistence across pod restarts and rescheduling.

## 🚀 Getting Started

Each concept includes practical examples and scenarios to help you understand and troubleshoot effectively. Clone this repository to explore the examples and apply the kubectl commands.

```bash
            git clone https://github.com/DarylAdrien/k8s-troubleshooting.git
            cd k8s-troubleshooting
```

Navigate into the respective directories to find YAML manifests and troubleshooting steps for each concept.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to open a pull request or an issue if you have suggestions, improvements, or discover new troubleshooting techniques.

Happy troubleshooting!