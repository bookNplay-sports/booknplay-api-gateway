API Gateway is an entry point for all client requests in the BookNPlay Sports Turf Booking Platform. It routes incoming requests to the appropriate microservices, such as User Service, Turf Service, Booking Service, Payment Service, and Notification Service. It uses Spring Cloud Gateway for request routing and Eureka Service Discovery to locate registered services. It helps centralize API access and simplifies communication between clients and backend microservices.

Technology Stack: Java 21, Spring Boot, Spring Cloud Gateway, Eureka Client, Maven, and Spring Security.

Configuration: Service Name: api-gateway | Port: 8080 | Eureka Server: http://localhost:8761

The API Gateway acts as a centralized routing layer for the BookNPlay microservices architecture.
