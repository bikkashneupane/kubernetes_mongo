### Kubernetes 101

- DockerHub
- Kubernetes Docs

What is used?

- mongo-express image from dockerhub
- kubectl
- minikube

Terminologies to understand

- Kubectl - which helps us to work with control plane.
- Control Plane - which is the mastermind which helps us to interact with lots of worker nodes.
- Worker-node - (physical or virtual) machines which run containerized applications, hosting the pods that form the application workloads. You could have multiple dockerised applications and each have (deployment and services).
  - e.g: mongo - (deployment and service), web-app - (deployment and service)
- Global Variables - (Secrets and config)
- Secrets - sensitive informations like environment variables
- config - non-sensative informations
