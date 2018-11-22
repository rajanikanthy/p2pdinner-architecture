# P2PDinner Architecture and Documents

## Architecture Overview of P2PDinner Application

![Image of P2PDinner Architecture](https://github.com/rajanikanthy/p2pdinner-architecture/blob/master/P2PDinner-Highlevel-Design.jpg)

## Tech Stack

The application is built to support multi-cloud deployments. This application utilizes Spring Boot and Netflix OSS stack for building microservices.

- All Microservices are built using Spring Boot
- OAuth2 security uses Okta
- Container Engine - Kubernetes
- Data Storage - Postgres (GCP - Cloud SQL)
- Messaging (Rabbit MQ, Pub/Sub on GCP)
- Object Storage (AWS S3)
- Push Notifications (Apple and Android)

## Microservice - related tech stack

- API Gateway (Zuul)
- Service Registry (Eureka)
- Client side load balancing (Ribbon, Feign)
- Circuit Breaker (Hystrix)
- Messaging (Rabbit MQ, Pub/Sub)
- Security (Okta)
- UI (Angular 4)
