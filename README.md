# slc-recruitment-task
# Task A – GraphQL Integration (IIIT Clubs Backend)

## Objective

The goal of this task is to understand the backend architecture of the IIIT Clubs
website, run the microservices locally using Docker, and interact with the Apollo
GraphQL interface to perform CRUD operations on clubs, members, and events.

The frontend (Next.js) codebase was intentionally ignored as per the task
instructions.

---

## Repositories & Documentation Referred

- Backend Services Repository:
  https://github.com/Clubs-Council-IIITH/services
- Website:
  https://clubs.iiit.ac.in
- Documentation:
  https://slc-docs.iiit.ac.in

---

## Architecture Overview (High Level)

The system follows a microservices-based architecture where:
- Multiple backend services run as Docker containers
- NGINX acts as a reverse proxy
- MongoDB is used as the primary database
- Apollo GraphQL provides a unified API layer

Each service exposes GraphQL schemas which are federated through Apollo Gateway.

---

## Prerequisites

- Docker
- Docker Compose plugin
- (Optional) MongoDB Compass for database inspection

---


