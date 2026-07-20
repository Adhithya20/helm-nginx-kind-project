# Helm Nginx Kind Project

## Project Overview

This project demonstrates how to deploy an Nginx application on Kubernetes using Helm and Kind.

## Technologies Used

- Helm 3
- Kubernetes
- Kind
- Docker Desktop
- Git
- GitHub
- Git Bash
- Windows 11

## Project Structure

```
helm-nginx-project/
│
├── README.md
└── my-nginx-chart/
    ├── Chart.yaml
    ├── values.yaml
    ├── templates/
    ├── charts/
    └── .helmignore
```

## Prerequisites

- Docker Desktop
- Kind
- kubectl
- Helm
- Git

## Installation

Clone the repository:

```bash
git clone https://github.com/Adhithya20/helm-nginx-kind-project.git
```

Go to the chart:

```bash
cd helm-nginx-kind-project/my-nginx-chart
```

Install:

```bash
helm install my-nginx .
```

Upgrade:

```bash
helm upgrade my-nginx .
```

Check:

```bash
helm list
kubectl get all
```

Access:

```bash
kubectl port-forward service/my-nginx-my-nginx-chart 9090:80
```

Open:

```
http://localhost:9090
```

## Author

Adhithya P S