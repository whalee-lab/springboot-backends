# springboot-backends

## Spring Boot backend projects (2) — Auth & RBAC Microservice; Recommendation Service with RPC/REST
These satisfy JUnit testing requirement.

### Spring A — Auth & RBAC Microservice
- Why: essential for enterprise systems; shows design of secure services.
- Difficulty: ★★★☆☆
- Doability: ★★★★★
- Core features
  1. OAuth2/JWT auth, roles, permissions, refresh tokens
  2. User + role management APIs
  3. JUnit unit tests + integration tests (mock MVC)
- Deliverables/issues
  1. Design API spec + DB schema
  2. Implement controllers/services/repositories
  3. JUnit test coverage target -> add to CI

### Spring B — Recommendation Service (RPC + REST)
- Why: shows backend + ML integration in Java ecosystem.
- Difficulty: ★★★★☆
- Doability: ★★★☆☆
- Core features
  1. Recommendation engine (collab filtering / embedding-based)
  2. Expose RPC (gRPC) for internal microservices + REST for external clients
  3. JUnit tests + contract tests
- Deliverables/issues
  1. Model serving endpoint (load model artifact)
  2. gRPC proto + server implementation
  3. REST wrapper + tests
