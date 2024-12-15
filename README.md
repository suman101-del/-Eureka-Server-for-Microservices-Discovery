# -Eureka-Server-for-Microservices-Discovery
# Eureka Server for Microservices Discovery

This project implements a **Spring Cloud Eureka Server** to enable service registration and discovery in a microservices architecture.

## Tech Stack
- **Java** (Spring Boot)
- **Spring Cloud Eureka**
- **Maven**

## Features
- Service Registration and Discovery
- Easy integration for client microservices
- Dynamic scaling for distributed systems

## Run the Server
1. Clone this repository.
2. Run the `EurekaServerApplication.java` file.
3. Access the Eureka Server dashboard at [http://localhost:8761](http://localhost:8761).

## Configure Eureka Clients
Clients can register themselves with the Eureka Server using the following properties:

```yaml
eureka:
  client:
    service-url:
      defaultZone: http://localhost:8761/eureka/
