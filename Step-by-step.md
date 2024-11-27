# 1. Build Eureka Registry Service 
## Depenancies:
    - Eureka Server (Spring Cloud Discovery)


# 2. Build Catalog Service
## Depenancies:
    - Eureka Client
    - MySQL connector
    - JPA
    - Config client
    - Zipkin


# 3. Build Streaming Video Service
## Depenancies:
    - Eureka Client
    - Cloud LoadBalancer (Spring Cloud Routing)
    - Config client
    - Zipkin
## Config:
    - RestConfig: loadbalance


# 4. Gateway
## Depenanies:
    - Eureka Client
    - Gateway (SpringCloud Routing)


# 5. Config Server
## Control configuration of all microservices here
    - Config Server (Spring Cloud Config)
    - Eureka Discovery Client

    