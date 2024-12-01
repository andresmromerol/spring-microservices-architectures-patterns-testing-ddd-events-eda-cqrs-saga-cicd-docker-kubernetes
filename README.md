
# spring-microservices-architectures-patterns-testing-ddd-events-eda-cqrs-saga-cicd-docker-kubernetes

---
## 🔗 Hi, I'm Andrés Romero! 👋
<br>
andresmromerolopez@gmail.com  - andresandresmromero7@gmail.com

[![linkedin](./diagrams/img/linkedin.svg)](https://www.linkedin.com/in/andres-mauricio-romero-lopez-9276b3337)

---
<div style="max-width: 100%; height: auto;">
  <img src="./diagrams/2-add-observability-and-monitoring.gif" alt="Funny GIF" style="width: 100%; height: auto;">
</div>

| **Component**            | **Description**                                                                                                                                                                                                                                             |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Discovery Server**     | It registers microservices and allows them to discover each other to facilitate communication. <br> **TechStack:** Spring Boot, Eureka Server, Prometheus and Spring Actuator                                                                               |
| **Configuration Server** | It manages and distributes configuration settings to microservices to ensure consistency and centralized management. <br> **TechStack:** Spring Boot, Spring Actuator, OpenTelemetry and Prometheus                                                         |
| **Gateway**              | It acts as a single entry point for client requests and routes them to the appropriate microservices. <br> **TechStack:** Spring Boot, Spring Actuator, OpenTelemetry and Prometheus |
| **User-context**         | **TechStack:** Spring Boot |
|                          |                                                                                                                                                                                                                                                             |
| **Observability**        | **TechStack:** OpenTelemetry, Loki, Tempo, Prometheus and Grafana                                                                                                                                                                                           |