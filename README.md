# Ecommerce Robot Shop : Helm chart 

Welcome to the **Robot Shop** Helm chart repository — a microservices ecommerce application infrastructure deployed on Kubernetes using a three-tier architecture.

---

## Overview

Robot Shop is a simple example ecommerce microservices application showcasing a modern technology stack deployed and managed via Helm charts on Kubernetes. It demonstrates how to build and operate a scalable, modular ecommerce platform with separate frontend, backend, and database layers.

---

## Architecture

This project follows a **three-tier architecture**:

- **Presentation Layer (Frontend):** AngularJS (1.x) served via Nginx
- **Application Layer (Backend):** NodeJS and Python microservices
- **Data Layer (Databases and Messaging):** MongoDB, MySQL, Redis, and RabbitMQ

Each tier is containerized and deployed as independent microservices, orchestrated with Kubernetes and managed through Helm charts for easy deployment, scaling, and upgrades.

---

## Technology Stack

- **Frontend:** AngularJS (1.x), Nginx
- **Backend:** NodeJS, Python
- **Databases:** MongoDB, MySQL, Redis
- **Messaging:** RabbitMQ
- **Infrastructure:** Kubernetes, Helm
- **Monitoring:** Instana for automatic detection, tracing, and monitoring of services and requests

---

## Features

- Modular microservices architecture enabling independent development and scaling
- Kubernetes-native deployment with Helm charts for infrastructure automation
- End-to-end distributed tracing and monitoring with Instana
- Support for multiple databases and messaging queues for robust data handling
- Easy customization and extension for real-world ecommerce scenarios

---

## Getting Started

### Prerequisites

- Kubernetes cluster (local or cloud-based)
- Helm 3 installed
- kubectl configured to access your cluster

### Installation

1. Clone this repository:
```
git clone https://github.com/manupanand-freelance-developer/ecomm-helm-k8s-infra-prjt-10-2025.git
cd ecomm-helm-k8s-infra-prjt-10-2025
```


2. Deploy the Helm chart:
```
helm install robot-shop ./helm-chart

```

3. Verify the deployment:
```
kubectl get pods

```

4. Access the frontend service via the exposed LoadBalancer or NodePort.

---

## Additional Resources

- Visit the [Ecommerce Site](https://www.manupanand.com/) to learn more.
- Frontend source code is available on [Github](https://github.com/manupanand-freelance-developer/ecomm-frontend.git).

---

## License

This project is licensed under the MIT License.


