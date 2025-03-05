# digital-storefront-saas
Digital Storefront SAAS application

digital-storefront-saas/
├── pom.xml  # Parent POM

├── discovery-service/
│   ├── pom.xml
│   ├── src/main/java/com/ankit/discovery/DiscoveryServiceApplication.java
│   ├── src/main/resources/application.yml
├── api-gateway/
│   ├── pom.xml
│   ├── src/main/java/com/ankit/gateway/ApiGatewayApplication.java
│   ├── src/main/resources/application.yml
├── auth-service/
│   ├── pom.xml
│   ├── src/main/java/com/ankit/auth/AuthServiceApplication.java
│   ├── src/main/resources/application.yml
├── store-service/
│   ├── pom.xml
│   ├── src/main/java/com/ankit/store/StoreServiceApplication.java
│   ├── src/main/resources/application.yml
├── payment-service/
│   ├── pom.xml
│   ├── src/main/java/com/ankit/payment/PaymentServiceApplication.java
│   ├── src/main/resources/application.yml
├── common-lib/
│   ├── pom.xml
│   ├── src/main/java/com/ankit/common/dto/
│   ├── src/main/java/com/ankit/common/entity/
│   ├── src/main/java/com/ankit/common/exception/
│   ├── src/main/java/com/ankit/common/utils/
├── docker/
│   ├── docker-compose.yml
│   ├── Dockerfile
├── .github/
│   ├── workflows/
│   │   ├── ci-cd.yml  # GitHub Actions for CI/CD
├── README.md

