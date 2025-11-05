# Auth Service
This service is responsible for handling user authentication and authorization. The auth service is implemented with keycloak and provides functionalities for user login, registration, role management, and token generation.

## Features
- User Authentication: Secure user login and registration.
- Role Management: Assign and manage user roles and permissions.
- Token Generation: Generate JWT tokens for authenticated users.
- Integration with other services: Seamless integration with other microservices for authentication.
- Admin User Bootstrap: Automatically creates an admin user on startup.
- Dockerized: Easily deployable using Docker.
- Kubernetes Ready: Can be deployed in a Kubernetes cluster.

## Environment Variables
```
POSTGRES_DB=
POSTGRES_USER=
POSTGRES_PASSWORD=
KC_BOOTSTRAP_ADMIN_USERNAME=
KC_BOOTSTRAP_ADMIN_PASSWORD=
```