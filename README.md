# ConnectSphere

## Introduction
ConnectSphere is a LinkedIn-inspired, event-driven microservices platform built using Spring Boot and cloud-native design principles.
The system consists of independently deployable services such as User, Post, Connections, and Notification, managed through an API Gateway and service discovery.It leverages Kafka for asynchronous communication, Resilience4J for fault tolerance, and integrates observability using Zipkin and ELK stack.All services are containerized with Docker and orchestrated using Kubernetes to ensure scalability, high availability, and production-grade resilience.

## Architecture

The application follows a microservices architecture pattern with the following components:

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/72cb1f0f-fbc3-4e44-b7a5-1b5bed6e5930" />


