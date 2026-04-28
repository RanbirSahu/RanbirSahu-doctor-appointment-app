Doctor Appointment Application is a microservices-based backend system that allows patients to search doctors, book appointments, and make payments online.

The system is designed using Spring Boot and follows a distributed architecture where each service handles a specific responsibility.

Microservices:
- Doctor Service: Manages doctor details and availability
- Patient Service: Handles patient information
- Booking Service: Manages appointment booking between doctor and patient
- Payment Service: Handles online payment using Stripe
- Eureka Server: Service discovery for all microservices

Key Features:
- Search doctors based on location and availability
- Book appointments with available time slots
- Manage patient details
- Secure payment integration using Stripe
- Service-to-service communication using REST clients
- Centralized service registry using Eureka

Tech Stack:
- Java 8
- Spring Boot
- Spring Cloud (Eureka Server)
- REST APIs
- Hibernate / JPA
- MySQL
- Stripe Payment Gateway
- Maven

Project Highlights:
- Implemented microservices architecture for scalability
- Used Eureka for service discovery and load balancing
- Designed RESTful APIs for communication between services
- Integrated Stripe for secure payment processing
- Followed clean architecture and modular design

This project demonstrates real-world backend development skills including microservices, API design, distributed systems, and payment integration.
