# Backend Developer Knowledge Base
Choose your language:
- 🇬🇧 **English** (default)
- 🇮🇷 [فارسی](00-Translations/fa/README.md)

A comprehensive, opinionated, and practical knowledge base for Backend Developers.

This repository is **not** a collection of random notes or interview trivia.
It is a structured reference that covers the **core concepts, trade-offs, and real-world considerations** required to design, build, deploy, and operate backend systems at scale.

---

## 🎯 Goals of This Repository

- Define **what a competent backend developer should actually know**
- Explain **why** each concept exists, not just *how* to use it
- Highlight **trade-offs**, failure modes, and architectural consequences
- Provide **vendor-neutral fundamentals** before tools
- Serve as:
  - A learning roadmap
  - A revision reference
  - A system design thinking guide

---

## 📚 Topics Covered

### 1. Operating Systems & Networking Basics
- Linux fundamentals
- Bash scripting
- Process & memory basics
- File descriptors & sockets

---

### 2. Web Fundamentals
- HTTP methods & status codes
- REST principles & REST maturity levels
- Idempotency & safe retries
- Pagination, filtering & sorting patterns
- API versioning strategies

---

### 3. Authentication & Security
- Authentication vs Authorization
- Sessions vs JWT
- OAuth 2.0 & OpenID Connect
- Hashing, salting & encryption standards
- Rate limiting strategies
- DDoS protection fundamentals
- Zero Trust concepts

---

### 4. Real-Time Communication
- WebSockets
- Long polling vs Server-Sent Events
- Backpressure & scalability concerns

---

### 5. Databases & Storage
- SQL vs NoSQL (use cases & trade-offs)
- ACID properties & transactions
- Indexing strategies
- Query optimization
- Normalization vs denormalization
- Sharding & replication
- Connection pooling

---

### 6. Caching & Performance
- Cache-aside vs write-through
- Redis & Memcached
- Cache invalidation strategies
- CDN fundamentals
- Edge caching

---

### 7. Messaging & Eventing
- Message brokers overview
  - Kafka
  - RabbitMQ
- Event-driven architecture
- At-least-once vs exactly-once delivery
- Idempotent consumers

---

### 8. API Technologies
- REST vs GraphQL
- gRPC & Protocol Buffers
- BFF (Backend For Frontend) pattern
- API gateways
- API monetization & throttling
- OpenAPI / Swagger documentation

---

### 9. System Design & Architecture
- Monolith vs microservices
- Service boundaries
- Load balancing strategies
- Vertical vs horizontal scaling
- Failure handling & graceful degradation
- Distributed tracing fundamentals

---

### 10. Infrastructure & Deployment
- Docker & containerization
- Reverse proxies (Nginx, Envoy)
- CI/CD pipelines (GitHub Actions, GitLab CI)
- Blue-green & canary deployments
- Zero-downtime deployments
- Feature flags

---

### 11. Cloud & Platform Concepts
- Core cloud primitives (AWS / GCP / Azure)
- Serverless fundamentals
- Infrastructure as Code (Terraform, CloudFormation)
- Edge computing basics

---

### 12. Observability
- Structured logging
- Metrics & monitoring (Prometheus, Grafana)
- Alerting principles
- Distributed tracing

---

### 13. Testing & Reliability
- Unit vs integration testing
- Load & stress testing
- k6 & JMeter fundamentals
- Reliability vs scalability
- SLO, SLA, SLI concepts

---

## 🧠 Philosophy

- Tools change, **principles do not**
- Scalability problems usually start as **design mistakes**
- Every abstraction has a cost
- There is no "best architecture", only **appropriate trade-offs**

---

## 📂 Repository Structure

Each topic is broken down into:
- Core concepts
- Why it exists
- How it works
- Common mistakes
- Real-world trade-offs

---

## 🚧 Status

This repository is a **living document**.
Contributions, corrections, and discussions are welcome.

---

## 📜 License

MIT License
