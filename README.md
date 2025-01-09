# Next Upcoming App: Goliath National Bank: Demo of Cloud Native Microservices with Spring Framework

- Production ready microservice architecture, practicing cloud native methodology with Spring Boot and Spring Cloud tool chains.
- Orchestraed microservice Kubernetes cluster with **Istio service mesh** and enforced **Mutual Transportation Layer Security (mTLS)** protocol, effectively managing and securing East-West communications.
- Implemented server-side service discovery and load balancing with Kubernetes discovery server and **Ingress**; created API Gateway with **Spring Cloud Gateway**; consolidated system resiliency by deploying **rate limiter** and **bulkhead** with **Resilience4j**.
- Engineered runtime config refreshing pipeline through **Spring Cloud Bus** and Config Monitor with **RabbitMQ**.
- Deployed Dockerized Containers on **Helm-Chart**-managed Kubernetes clusters on GCP with **Google Kubernetes Engine (GKE)**. (GCP deployment was temporary and experimental due to concerns on cost incurred by cloud platform)
- Streamlined dependency management by **Bill Of Materials (BOM)** in Maven, ensuring version consistency and simplifying the process of upgrading libraries across all microservices.
- **MySQL/H2** as the distributed database solution, and **Spring Data JPA** was used as ORM.
- Industry standard observability solution: visualization data panels on **Promethus, Grafana, Loki, Promtail, Tempo**. 
- Resilient event-driven message queue: **Apache Kafka** through **Spring Cloud Stream** for microservices.
- Standardised API management: OpenAPI Specification, Swagger 
