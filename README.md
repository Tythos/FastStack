# FastStack

## Original

Here is the original "stack", from https://github.com/tiangolo/full-stack-fastapi-template :

* FastAPI for the Python backend API.

  - SQLModel for the Python SQL database interactions (ORM).

  - Pydantic, used by FastAPI, for the data validation and settings management.

  - PostgreSQL as the SQL database.

* React for the frontend.

  - Using TypeScript, hooks, Vite, and other parts of a modern frontend stack.

  - Chakra UI for the frontend components.

  - An automatically generated frontend client.

  - Dark mode support.

* Docker Compose for development and production.

* Secure password hashing by default.

* JWT (JSON Web Token) authentication.

* Email based password recovery.

* Tests with Pytest.

* Traefik as a reverse proxy / load balancer.

* Deployment instructions using Docker Compose, including how to set up a frontend Traefik proxy to handle automatic HTTPS certificates.

* CI (continuous integration) and CD (continuous deployment) based on GitHub Actions.

## Variation

Here is our "variation", presented as a checklist with some minor modifications to match our deployment target (a self-contained Docker image to be deployed on a DigitalOcean VM, or "droplet"):

- [ ] FastAPI for the Python backend API.

- [ ] SQLModel for the Python SQL database interactions (ORM).

- [ ] Pydantic, used by FastAPI, for the data validation and settings management.

- [ ] PostgreSQL as the SQL database.

- [ ] React for the frontend.

- [ ] Vite-based build/pack (JSX is fine for now).

- [ ] Chakra UI for the frontend components.

- [ ] Dark mode support.

- [ ] Docker for development and production (self-contained image).

- [ ] Secure password hashing by default.

- [ ] JWT (JSON Web Token) authentication.

- [ ] Email based password recovery (may need a subscription to a third-party email service).

- [ ] Tests with Pytest.

- [ ] CI (continuous integration) and CD (continuous deployment) based on GitHub Actions.
