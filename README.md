Microservice Order Management System
This project is a Microservice-based Order Management System designed to provide a scalable and efficient way to handle orders within a microservices architecture. Leveraging Spring Boot for the microservice framework and including Spring Cloud components for service discovery and administration, it offers a comprehensive solution for modern cloud-native applications.

Description
The Microservice Order Management System is built to facilitate the management of customer orders through a microservice architecture, enhancing scalability and resilience. It uses @EnableDiscoveryClient for service discovery, allowing services to find and communicate with each other in a dynamic environment. Additionally, @EnableAdminServer is used to integrate an admin server for managing and monitoring microservice instances.

Getting Started
Dependencies
JDK 11 or newer for compatibility with Spring Boot 2.5.0+
Spring Boot 2.5.0 or higher for the microservice framework
Spring Cloud for service discovery and configuration
Maven 3.6.3 or higher for project building
Any relational database (MySQL, PostgreSQL) for data persistence
An IDE that supports Java and Spring (IntelliJ IDEA, Eclipse, VS Code)
Features
Service Discovery: Allows services to dynamically discover and communicate with each other.
Admin Server: Provides a dashboard for managing and monitoring microservice instances.
Order Management: Facilitates the creation, retrieval, and management of orders.


Order Endpoints

Create a New Order
POST /api/orders
Description: Creates a new order with the provided order details.
Retrieve All Orders
GET /api/orders
Description: Retrieves a list of all orders.
Retrieve a Single Order by ID
GET /api/orders/{orderId}
Description: Retrieves details of a specific order by order ID.
Update an Order
PUT /api/orders/{orderId}
Description: Updates the order details for the specified order ID.
Delete an Order
DELETE /api/orders/{orderId}
Description: Deletes the specified order by order ID.
