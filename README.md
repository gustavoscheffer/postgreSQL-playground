# postgreSQL-playground

A repository for experimenting with PostgreSQL configurations and deployments using Docker, Kubernetes, and Helm.

## Install PostgreSQL

Installing PostgreSQL as a container can be tricky, especially when you need PgAdmin alongside it for database management. This repository provides two setup options:

* [kubegres](./kubegres/README.md) - Docker + Kubernetes + Traefik
* [helm](./helm/README.md) - Docker + Helm Chart + Kubernetes + Traefik

**Note:** Rancher Desktop provides a complete suite for both scenarios.

## Getting Started

Choose one of the installation methods above and follow the corresponding README guide for detailed setup instructions.

## Tech Stack

- Docker
- Kubernetes
- PostgreSQL
- PgAdmin
- Traefik (Ingress Controller)
- Helm
- Kubegres

## License

This repository is provided as-is for learning and experimentation purposes.
