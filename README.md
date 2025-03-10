### Kubernetes 101

- DockerHub
- Kubernetes Docs

What is used?

- homebrew
- mongo-express image from dockerhub
- docker
- kubectl
- minikube

Terminologies to understand

- Kubectl - A CLI tool that allows interaction with the Kubernetes API server (control plane) to manage the cluster (worker-nodes).
- Control Plane - The central component of Kubernetes that manages the cluster, schedules workloads, and maintains desired states across multiple worker nodes.
- Worker-node - A physical or virtual machine where containerized applications run. Each node hosts pods, which contain application workloads.
  Example:
  MongoDB – Runs as a Deployment and is exposed via a Service.
  Web App – Runs as a Deployment and is exposed via a Service.
- Global Variables - (Secrets and config)
- Secrets - Used for storing sensitive information like passwords, API keys, and environment variables securely.
- ConfigMap - Used for storing non-sensitive configuration data like application settings and environment-specific variables.

- in secrets: for mongo, username and password are base64 encoded.
