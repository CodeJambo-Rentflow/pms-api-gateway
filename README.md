# PMS API Gateway

Spring Cloud Gateway for PMS Kenya. Routes client traffic to backend microservices and validates Keycloak-issued JWTs.

## Tech Stack

- Java 21
- Spring Boot 3.4.1
- Spring Cloud Gateway 2024.0.0
- Keycloak (OIDC resource server)

## Local Development

### Prerequisites

- Docker Desktop running
- Keycloak running locally (see `../local-dev/docker-compose.yml`)
- Realm `pms-kenya` with client `pms-api-gateway` configured

### Run

```bash
mvn spring-boot:run# pms-api-gateway
PMS Kenya - pms-api-gateway
