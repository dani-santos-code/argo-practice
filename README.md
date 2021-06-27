# K8s deployment practice

This project is to practice K8s deployment following a CI/CD approach

## Technologies used:

- **Docker** for containerizing applications
- **Github Actions** for CI: build images (based on the Dockerfile) and pushing them to Docker Registry
- **Helm** to manage Kubernetes: define, install, and upgrade apps
- **K3s**: lightweight cluster run in a VM instance (using vagrant)
- **Argo** for Continuous Delivery. On pushes to the `main` branch, deployments to Kubernetes are triggered following the specifications in the helm folder
