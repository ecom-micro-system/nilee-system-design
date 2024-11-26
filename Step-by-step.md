# 1. Build Eureka Registry Service 
## Depenancies:
    - Eureka Server (Spring Cloud Discovery)


# 2. Build Catalog Service
## Depenancies:
    - Eureka Client
    - MySQL connector
    - JPA
## API:
    - Insert video
    - Get all video
    - Find video path by video ID


# 3. Build Streaming Video Service
## Depenancies:
    - Eureka Client
    - Cloud LoadBalancer (Spring Cloud Routing)
## API:
    - Load video from Server
## Config:
    - RestConfig: loadbalance


# 4. Gateway
## Depenanies:
    - Eureka Client
    - Gateway (SpringCloud Routing)




    