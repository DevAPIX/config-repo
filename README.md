# DevAPIX - Configuration Repository

## Overview
This repository contains all the externalized configuration files (YAML/Properties) for the DevAPIX microservices platform. It acts as the backend data source for the Spring Cloud Config Server.

## Key Features
- **Service Configurations**: Contains application-specific property files (e.g., `api-gateway.yml`, `auth-service.yml`).
- **Global Configurations**: Includes `application.yml` for shared properties across all services.
- **Environment Profiles**: Organizes configurations by environment profiles for easy deployment transitions.
- **Version Control**: Allows tracking and auditing of all configuration changes across the platform.

## Important Note
This repository should be securely managed as it may contain sensitive information such as database credentials and API keys (though secrets should ideally be injected via environment variables or a secrets manager).
