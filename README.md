# Kubernetes Project with Go

This project is a simple Go application deployed in a Kubernetes cluster, using Docker to build the image and `docker-compose` for easy local development. The application exposes an HTTP endpoint that responds with "Hello World."

## Project Structure

- **Dockerfile**: Defines the build steps for the Docker image of the Go application.
- **docker-compose.yaml**: Configuration for `docker-compose` to facilitate local development.
- **deployment.yaml**: Kubernetes manifest for the Deployment of the application.
- **service.yaml**: Kubernetes manifest for the Service that exposes the application.

## Prerequisites

- Docker and Docker Compose installed
- Kind (optional, for creating local Kubernetes clusters)
- kubectl (to manage resources in Kubernetes)
