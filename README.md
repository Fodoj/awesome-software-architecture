<p align="center">
  <img src="banner.png" height="400">
  <h1 align="center">
   Awesome Software Architecture
    <br>
    <a href="https://github.com/mehdihadeli/awesome-software-architecture/actions/workflows/ci.yml"><img alt="build-status" src="https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square" /></a>
    <a href="https://github.com/sindresorhus/awesome" ><img alt="awesome" src="https://awesome.re/badge-flat2.svg?style=flat-square" /></a>
    <a href="https://github.com/mehdihadeli/awesome-software-architecture/blob/main/LICENSE" ><img alt="license" src="https://img.shields.io/badge/License-CC0_1.0-E91E63.svg?style=flat-square" /></a>
  </h1>
</p>

> Curated list of awesome articles and resources to learn and practice software architecture, patterns and principles. This repository will be updated continuously, keep yourself up to date .

I created this repository to share a set of links that I found valuable and inspiring and I share them with others to improve our knowledge together ✌️. 

**🚀 Go ahead to the official web page here:** 
**[https://awesome-architecture.com](https://awesome-architecture.com/)**

--------------------------

## Contents

- [Software Architecture](#software-architecture)
- [Actor Model Architecture](#actor-model-architecture)
- [Algorithms](#algorithm)
- [Clean Architecture](#clean-architecture)
- [Onion Architecture](#onion-architecture)
- [Hexagonal Architecture](#hexagonal-architecture)
- [Vertical Slice Architecture](#vertical-slice-architecture)
- [Event Driven Architecture](#event-driven-architecture)
- [Service Oriented Architecture](#service-oriented-architecture)
- [Domain Driven Design](#domain-driven-design)
- [Data Driven Design](#data-driven-design)
- [CQRS](#cqrs)
- [Microservices](#microservices)
- [Modular Monolith](#modular-monolith)
- [Architectural Design Principles](#architectural-design-principles)
- [Design Patterns](#design-patterns)
- [Cloud Design Patterns](#cloud-design-patterns)
- [Cloud Best Practices](#cloud-best-practices)
- [Cloud Native](#cloud-native)
- [Platform as a Service](#platform-as-a-service)
- [Infrastructure as a Service](#infrastructure-as-a-service)
- [DevOps](#devops)
- [Reverse Proxy - Load Balancing](reverse-proxy---load-balancing)
- [Service Discovery And Registry](#service-discovery-and-registry)
- [Service Mesh](#service-mesh)
- [Object Oriented Design](#object-oriented-design)
- [Systems Design](#systems-design)
- [Scaling](#scaling)
- [Back Pressure](#back-pressure)
- [Clean Code](#clean-code)
- [Abstraction](#abstraction)
- [Design Best Practices](#design-best-practices)
- [Anti Patterns](#anti-patterns)
- [Eventual Consistency](#eventual-consistency)
- [Messaging](#messaging)
- [Distributed Transactions](#distributed-transactions)
- [Distributed Locking](#distributed-locking)
- [Eventual Consistency](#eventual-consistency)
- [RESTful API Design](#rest)
- [gRPC](#grpc)
- [Caching](#caching)
- [Functional Programming](#functional)
- [Concurrency](#concurrency)
- [Sharding](#sharding)
- [Refactoring](#refactoring)
- [NoSQL](#nosql)
- [Relational Database](relational-database)
- [Azure Cloud](azure-cloud)
- [Modeling](#modeling)
- [Open Source](#open-source)
- [Code Review](#code-review)
- [Interview](#interview)
- [Architecture Decision Records (ADR)](#adr)
- [Micro-Frontend](#micro-frontend)
- [Others](#others)


> **Note**: Above table of contents is not complete yet and it's in progress, full resources currently is available on the official web page: 
 **[https://awesome-architecture.com](https://awesome-architecture.com/)**

### Software Architecture

| Topic | Description |
|:-------:|:----------- |
| [Software Architecture](docs/software-architecture.md) | Software architecture refers to the fundamental structures of a software system and the discipline of creating such structures and systems.

### Actor Model Architecture

| Topic | Description |
|:-------:|:----------- |
| [Actor Model Architecture](docs/actor-model-architecture/actor-model-architecture.md) |  The Actor Model is a programming paradigm in which the basic unit of execution is the actor. In the Actor Model, an actor does work by using messages to express actions upon a system or other actors within the given system
| [Akka .NET](docs/actor-model-architecture/akka-net.md) |  Akka.NET is a toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET.
| [Microsoft Orleans](docs/actor-model-architecture/orleans.md) |Orleans is a cross-platform framework for building robust, scalable distributed applications.  
| [ProtoActor](docs/actor-model-architecture/protoactor.md) | Ultra fast distributed actors for Go, C# and Java/Kotlin.

### Algorithms

| Topic | Description |
|:-------:|:----------- |
| [Algorithms](docs/algorithm.md) |  An algorithm is a procedure used for solving a problem or performing a computation.

### Clean Architecture

| Topic | Description |
|:-------:|:----------- |
| [Clean Architecture](docs/clean-architecture.md) |  The Clean Architecture is the system architecture guideline proposed by Robert C. Martin (Uncle Bob) derived from many architectural guidelines like Hexagonal Architecture, Onion Architecture, etc...

### Onion Architecture
| Topic | Description |
|:-------:|:----------- |
| [Onion Architecture](docs/onion-architecture.md) | The Onion architecture, introduced by Jeffrey Palermo, and it is a form of layered architecture and we can visualize these layers as concentric circles.

### Hexagonal Architecture
| Topic | Description |
|:-------:|:----------- |
| [Hexagonal Architecture](docs/hexagonal-architecture.md) | The Hexagonal Architecture or Ports and Adapters architecture, introduced by Alistair Cockburn and it's an architectural pattern that allows input by users or external systems to arrive into the Application at a Port via an Adapter, and allows output to be sent out from the Application through a Port to an Adapter.

### Vertical Slice Architecture
| Topic | Description |
|:-------:|:----------- |
| [Vertical Slice Architecture](docs/vertical-slice-architecture.md) | The vertical slice architecture is a technique that helps us build maintainable applications by separating the application around features or `vertical slices`. 

### Event Driven Architecture
| Topic | Description |
|:-------:|:----------- |
| [Event Driven Architecture](docs/event-driven-architecture.md) | TODO...

### Service Oriented Architecture
| Topic | Description |
|:-------:|:----------- |
| [Service Oriented Architecture](docs/service-oriented-architecture.md) | TODO...

### Domain Driven Design
| Topic | Description |
|:-------:|:----------- |
| [Domain Driven Design](docs/domain-driven-design/domain-driven-design.md) | TODO...
| [Value Objects](docs/domain-driven-design/value-objects.md) | TODO...
| [Aggregation](docs/domain-driven-design/aggregation.md) | TODO...
| [Anemic Domain Model](docs/domain-driven-design/anemic-domain-model.md) | TODO...
| [Rich Domain Model](docs/domain-driven-design/rich-domain-model.md) | TODO...
| [Domain Model](docs/domain-driven-design/domain.md) | TODO...
| [Domain Service](docs/domain-driven-design/domain-service.md) | TODO...
| [Application Service](docs/domain-driven-design/application-service.md) | TODO...
| [Domain Events](docs/domain-driven-design/domain-events.md) | TODO...
| [Integration Events](docs/domain-driven-design/integration-event.md) | TODO...
| [Bounded Context](docs/domain-driven-design/bounded-context.md) | TODO...
| [Infrastructure](docs/domain-driven-design/infrastructure.md) | TODO...
| [Tactical Design Patterns](docs/domain-driven-design/tactical-design-patterns.md) | TODO...
| [Strategic Design Patterns](docs/domain-driven-design/strategic-design-patterns.md) | TODO...
| [Mappings](docs/domain-driven-design/mapping.md) | TODO...
| [Domain Primitives](docs/domain-driven-design/domain-primitives.md) | TODO...
| [Enum](docs/domain-driven-design/enums.md) | TODO...
| [Exception and Validation](docs/domain-driven-design/exception-and-validation.md) | TODO...

### Data Driven Design
| Topic | Description |
|:-------:|:----------- |
| [Data Driven Design](docs/data-driven-design.md) | TODO...

### CQRS
| Topic | Description |
|:-------:|:----------- |
| [CQRS](docs/cqrs.md) | TODO...

### Microservices
| Topic | Description |
|:-------:|:----------- |
| [Microservices](docs/microservices/microservices.md) | TODO...
| [Communication](docs/microservices/communication.md) | TODO...
| [Composite UI](docs/microservices/composite-ui.md) | TODO...
| [Service Boundaries](docs/microservices/services-boundries.md) | TODO...
| [Testing](docs/microservices/testing.md) | TODO...
| [API Gateway](docs/microservices/api-gateway/api-gateway.md) | TODO...
| [API Gateway - Ambassador](docs/microservices/api-gateway/ambassador.md) | TODO...
| [API Gateway - Kong](docs/microservices/api-gateway/kong.md) | TODO...
| [API Gateway - Ocelot](docs/microservices/api-gateway/ocelot.md) | TODO...
| [Observability](docs/microservices/observability/observability.md) | TODO...
| [Observability - Distributed Tracing](docs/microservices/observability/distributed-tracing.md) | TODO...
| [Observability - Monitoring](docs/microservices/observability/monitoring.md) | TODO...
| [Observability - Metrics](docs/microservices/observability/metrics.md) | TODO...
| [Observability - Diagnostics](docs/microservices/observability/diagnostics.md) | TODO...
| [Observability - Logging](docs/microservices/observability/logging.md) | TODO...
| [Observability - CorrelationId](docs/microservices/observability/correlationId.md) | TODO...
| [Observability - Tools - EFK](docs/microservices/observability/tools/efk.md) | TODO...
| [Observability - Tools - ELK](docs/microservices/observability/tools/elk.md) | TODO...
| [Observability - Tools - Fluent Bit](docs/microservices/observability/tools/fluent-bit.md) | TODO...
| [Observability - Tools - FluentD](docs/microservices/observability/tools/fluentd.md) | TODO...
| [Observability - Tools - Loki](docs/microservices/observability/tools/loki.md) | TODO...
| [Resiliency](docs/microservices/resiliency/resiliency.md) | TODO...
| [Resiliency - Idempotency](docs/microservices/resiliency/idempotency.md) | TODO...
| [Resiliency - High Availability](docs/microservices/resiliency/high-availibility.md) | TODO...
| [Security](docs/microservices/security/security.md) | TODO...
| [Security - Key Vault](docs/microservices/security/vault.md) | TODO...
| [Tools - CAP](docs/microservices/tools/cap.md) | TODO...
| [Tools - Dapr](docs/microservices/tools/dapr.md) | TODO...
| [Tools - Mass Transit](docs/microservices/tools/mass-transit.md) | TODO...
| [Tools - NService Bus](docs/microservices/tools/nservice-bus.md) | TODO...
| [Tools - SteelToe](docs/microservices/tools/steeltoe.md) | TODO...
| [Tools - Tye](docs/microservices/tools/tye.md) | TODO...

### Modular Monolith
| Topic | Description |
|:-------:|:----------- |
| [Modular Monolith](docs/modular-monolith.md) | TODO...

### Architectural Design Principles
| Topic | Description |
|:-------:|:----------- |
| [Architectural Design Principles](docs/architectural-design-principles/architectural-design-principles.md) | TODO...
| [CAP](docs/architectural-design-principles/cap.md) | TODO...
| [Cohesion](docs/architectural-design-principles/cohesion.md) | TODO...
| [Coupling](docs/architectural-design-principles/coupling.md) | TODO...
| [Architectural Design Principles](docs/architectural-design-principles/cqs.md) | TODO...
| [Cross Cutting Concerns](docs/architectural-design-principles/cross-cutting-concerns.md) | TODO...
| [Dependency Inversion](docs/architectural-design-principles/dependency-inversion.md) | TODO...
| [Dry](docs/architectural-design-principles/dry.md) | TODO...
| [Encapsulation](docs/architectural-design-principles/encapsulation.md) | TODO...
| [Fail Fast Design Principles](docs/architectural-design-principles/fail-fast.md) | TODO...
| [Composition Over Inheritance](docs/architectural-design-principles/favor-composition-over-inheritance.md) | TODO...
| [Grasp](docs/architectural-design-principles/grasp.md) | TODO...
| [Interface Segregation](docs/architectural-design-principles/interface-segregation.md) | TODO...
| [Inversion Control](docs/architectural-design-principles/inversion-control.md) | TODO...
| [KIIS](docs/architectural-design-principles/kiss.md) | TODO...
| [Open Closed Principles](docs/architectural-design-principles/open-closed-principles.md) | TODO...
| [Persistence Ignorance](docs/architectural-design-principles/persistence-ignorance.md) | TODO...
| [Single Responsibility](docs/architectural-design-principles/single-responsibility.md) | TODO...
| [Solid](docs/architectural-design-principles/solid.md) | TODO...
| [Yagni](docs/architectural-design-principles/yagni.md) | TODO...

### Design Patterns
| Topic | Description |
|:-------:|:----------- |
| [Design Patterns](docs/design-patterns/design-patterns.md) | TODO...
| [Adapter Pattern](docs/design-patterns/adapter-pattern.md) | TODO...
| [AutoPilot](docs/design-patterns/autopilot.md) | TODO...
| [Builder](docs/design-patterns/builder.md) | TODO...
| [Chain of Responsibility](docs/design-patterns/chain-of-responsibility.md) | TODO...
| [Command Message Pattern](docs/design-patterns/command-message-pattern.md) | TODO...
| [Command Pattern](docs/design-patterns/command-pattern.md) | TODO...
| [Decorator Patterns](docs/design-patterns/decorator-pattern.md) | TODO...
| [Factory Patterns](docs/design-patterns/factory-pattern.md) | TODO...
| [Mediator Patterns](docs/design-patterns/mediator-pattern.md) | TODO...
| [Observer Patterns](docs/design-patterns/observer.md) | TODO...
| [Query-Object Patterns](docs/design-patterns/query-object-pattern.md) | TODO...
| [Repository Pattern](docs/design-patterns/repository-pattern.md) | TODO...
| [REPR](docs/design-patterns/repr.md) | TODO...
| [Service Locator](docs/design-patterns/service-locator.md) | TODO...
| [Singleton](docs/design-patterns/singleton.md) | TODO...
| [Specification Pattern](docs/design-patterns/specification-pattern.md) | TODO...
| [State Pattern](docs/design-patterns/state-pattern.md) | TODO...
| [Strategy Patterns](docs/design-patterns/strategy-pattern.md) | TODO...
| [Transaction-Script Patterns](docs/design-patterns/transaction-script-pattern.md) | TODO...

### Cloud Design Patterns
| Topic | Description |
|:-------:|:----------- |
| [Cloud Design Patterns](docs/cloud-design-patterns/cloud-design-patterns.md) | TODO...
| [Ambassador Pattern](docs/cloud-design-patterns/ambassador-pattern.md) | TODO...
| [Anti Corruption Layer Pattern](docs/cloud-design-patterns/anti-corruption-layer-pattern.md) | TODO...
| [BFF](docs/cloud-design-patterns/bff.md) | TODO...
| [Bulkhead Pattern](docs/cloud-design-patterns/bulkhead-pattern.md) | TODO...
| [Circuit Breaker](docs/cloud-design-patterns/circuit-breaker.md) | TODO...
| [Exactly One Delivery](docs/cloud-design-patterns/exactly-one-delivery.md) | TODO...
| [Gateway Aggregation](docs/cloud-design-patterns/gateway-aggregation.md) | TODO...
| [Gateway Pattern](docs/cloud-design-patterns/gateway-pattern.md) | TODO...
| [Inbox Patterns](docs/cloud-design-patterns/inbox-pattern.md) | TODO...
| [Outbox Patterns](docs/cloud-design-patterns/outbox-pattern.md) | TODO...
| [Saga Patterns](docs/cloud-design-patterns/saga.md) | TODO...
| [Sidecar Patterns](docs/cloud-design-patterns/sidecar.md) | TODO...
| [Strangler Fig Patterns](docs/cloud-design-patterns/strangler-fig-pattern.md) | TODO...

### Cloud Best Practices
| Topic | Description |
|:-------:|:----------- |
| [Cloud Best Practices](docs/cloud-best-practices/cloud-best-practices.md) | TODO...

### Cloud Native
| Topic | Description |
|:-------:|:----------- |
| [Cloud Native](docs/cloud-native.md) | TODO...

### Platform as a Service
| Topic | Description |
|:-------:|:----------- |
| [Heroku](docs/paas/heroku.md) | TODO...
| [Netlify](docs/paas/netlify.md) | TODO...
| [OpenShift](docs/paas/openshift.md) | TODO...
| [Rancher](docs/paas/rancher.md) | TODO...

### Infrastructure as a Service
| Topic | Description |
|:-------:|:----------- |
| [Infrastructure as a Service](docs/iaas/iaas.md) | TODO...
| [Nomad](docs/iaas/nomad.md) | TODO...
| [Pulumi](docs/iaas/pulumi.md) | TODO...
| [Terraform](docs/iaas/terraform.md) | TODO...

### DevOps
| Topic | Description |
|:-------:|:----------- |
| [Containerd](docs/devops/containerd.md) | TODO...
| [Docker](docs/devops/docker/docker.md) | TODO...
| [Docker - Docker Compose](docs/devops/docker/docker-compose.md) | TODO...
| [Kubernetes](docs/devops/kubernetes/kubernetes.md) | TODO...
| [Kubernetes - Services](docs/devops/kubernetes/services.md) | TODO...
| [Kubernetes - Deployment Strategies](docs/devops/kubernetes/deployment-strategies.md) | TODO...
| [Kubernetes - Deployment Tools - ArgoCd](docs/devops/kubernetes/deployment-tools/argo-cd.md) | TODO...
| [Kubernetes - Deployment Tools - Flux](docs/devops/kubernetes/deployment-tools/flux.md) | TODO...
| [Kubernetes - Deployment Tools - Helm](docs/devops/kubernetes/deployment-tools/helm.md) | TODO...
| [Kubernetes - Deployment Tools - Jenkins](docs/devops/kubernetes/deployment-tools/jenkins.md) | TODO...
| [Kubernetes - Deployment Tools - Kubernetes Operator](docs/devops/kubernetes/deployment-tools/kubernetes-operator.md) | TODO...
| [Kubernetes - Deployment Tools - Kustomize](docs/devops/kubernetes/deployment-tools/kustomize.md) | TODO...
| [Kubernetes - Ingress Controller](docs/devops/kubernetes/ingress-controller/ingress-controller.md) | TODO...
| [Kubernetes - Ingress Controller - Nginx](docs/devops/kubernetes/ingress-controller/nginx-ingress.md) | TODO...
| [Kubernetes - Ingress Controller - Traefik](docs/devops/kubernetes/ingress-controller/traefik-ingress.md) | TODO...
| [Kubernetes - Other Tools - K3s](docs/devops/kubernetes/other-tools/k3s.md) | TODO...
| [Kubernetes - Other Tools - Kind](docs/devops/kubernetes/other-tools/kind.md) | TODO...
| [Kubernetes - Other Tools - Tilt](docs/devops/kubernetes/other-tools/tilt.md) | TODO...

### Reverse Proxy - Load Balancing
| Topic | Description |
|:-------:|:----------- |
| [Load Balancing](docs/reverse-proxy-lb/load-balancing.md) | TODO...
| [Reverse Proxy](docs/reverse-proxy-lb/reverse-proxy.md) | TODO...
| [Envoy](docs/reverse-proxy-lb/envoy.md) | TODO...
| [HAProxy](docs/reverse-proxy-lb/haproxy.md) | TODO...
| [MetalLB](docs/reverse-proxy-lb/metallb.md) | TODO...
| [Nginx](docs/reverse-proxy-lb/nginx.md) | TODO...
| [Traefik](docs/reverse-proxy-lb/traefik.md) | TODO...
| [Yarp](docs/reverse-proxy-lb/yarp.md) | TODO...

### Service Discovery And Registry
| Topic | Description |
|:-------:|:----------- |
| [Service Discovery](docs/service-discovery/service-discovery.md) | TODO...
| [Consul](docs/service-discovery/consul.md) | TODO...
| [Eureka](docs/service-discovery/eureka.md) | TODO...

### Service Mesh
| Topic | Description |
|:-------:|:----------- |
| [Service Mesh](docs/service-mesh/service-mesh.md) | TODO...
| [Istio](docs/service-mesh/istio.md) | TODO...
| [Linkerd](docs/service-mesh/linkerd.md) | TODO...
| [Maesh](docs/service-mesh/maesh.md) | TODO...

### Object Oriented Design
| Topic | Description |
|:-------:|:----------- |
| [Object Oriented Design](docs/object-oriented-design.md) | TODO...

### System Design
| Topic | Description |
|:-------:|:----------- |
| [System Design](docs/systems-design/systems-design.md) | TODO...
| [Consistent Hash](docs/systems-design/consistent-hash.md) | TODO...

### Scaling
| Topic | Description |
|:-------:|:----------- |
| [Scaling](docs/scaling.md) | TODO...

### Back Pressure
| Topic | Description |
|:-------:|:----------- |
| [Back Pressure](docs/back-pressure.md) | TODO...

### Clean Code
| Topic | Description |
|:-------:|:----------- |
| [Clean Code](docs/clean-code.md) | TODO...


### Abstraction
| Topic | Description |
|:-------:|:----------- |
| [Abstraction](docs/abstraction.md) | TODO...

### Design Best Practices
| Topic | Description |
|:-------:|:----------- |
| [Design Best Practices](docs/design-best-practices/design-best-practices.md) | TODO...
| [12 Factor](docs/design-best-practices/12-factor.md) | TODO...
| [Strongly Typed Ids](docs/design-best-practices/strongly-typed-ids.md) | TODO...
| [Thin Controllers](docs/design-best-practices/thin-controllers.md) | TODO...

### Anti Patterns
| Topic | Description |
|:-------:|:----------- |
| [Anti Patterns](docs/anti-patterns/anti-patterns.md) | TODO...
| [Big Ball of Mud](docs/anti-patterns/big-ball-of-mud.md) | TODO...
| [Code Smells](docs/anti-patterns/code-smells.md) | TODO...
| [God Object](docs/anti-patterns/god-object.md) | TODO...
| [Leaky Abstractions](docs/anti-patterns/leaky-abstractions.md) | TODO...
| [Partial Object](docs/anti-patterns/partial-object.md) | TODO...
| [Static Cling](docs/anti-patterns/static-cling.md) | TODO...

### Eventual Consistency
| Topic | Description |
|:-------:|:----------- |
| [Eventual Consistency](docs/eventual-consistency.md) | TODO...

### Messaging
| Topic | Description |
|:-------:|:----------- |
| [Messaging](docs/messaging/messaging.md) | TODO...
| [Kafka](docs/messaging/kafka.md) | TODO...
| [Rabbitmq](docs/messaging/rabbitmq.md) | TODO...
| [Nats](docs/messaging/nats.md) | TODO...
| [Change Data Capture (CDC)](docs/messaging/change-data-capture.md) | TODO...
| [Documentation](docs/messaging/documentation.md) | TODO...

### Distributed Transactions
| Topic | Description |
|:-------:|:----------- |
| [Distributed Transactions](docs/distributed-transactions.md) | TODO...

### Distributed Locking
| Topic | Description |
|:-------:|:----------- |
| [Distributed Locking](docs/distributed-locking.md) | TODO...

### Eventual Consistency
| Topic | Description |
|:-------:|:----------- |
| [Eventual Consistency](docs/eventual-consistency.md) | TODO...

### RESTful API Design
| Topic | Description |
|:-------:|:----------- |
| [RESTful API Design](docs/rest.md) | TODO...

### gRPC
| Topic | Description |
|:-------:|:----------- |
| [gRPC](docs/grpc.md) | TODO...

### Caching
| Topic | Description |
|:-------:|:----------- |
| [Caching](docs/caching.md) | TODO...

### Functional Programming
| Topic | Description |
|:-------:|:----------- |
| [Functional Programming](docs/functional.md) | TODO...

### Concurrency
| Topic | Description |
|:-------:|:----------- |
| [Concurrency](docs/concurrency.md) | TODO...

### Sharding
| Topic | Description |
|:-------:|:----------- |
| [Sharding](docs/sharding.md) | TODO...

### Refactoring
| Topic | Description |
|:-------:|:----------- |
| [Refactoring](docs/refactoring.md) | TODO...

### NoSQL
| Topic | Description |
|:-------:|:----------- |
| [NoSQL](docs/nosql/nosql.md) | TODO...
| [MongoDB](docs/nosql/mongodb.md) | TODO...
| [RavenDB](docs/nosql/ravendb.md) | TODO...
| [Cosmosdb](docs/nosql/cosmosdb.md) | TODO...
| [Documentdb](docs/nosql/documentdb.md) | TODO...

### Relational Database
| Topic | Description |
|:-------:|:----------- |
| [Relational Database](docs/relational/relational-database.md) | TODO...
| [Postgres](docs/relational/postgres.md) | TODO...

### Microsoft Azure Cloud
| Topic | Description |
|:-------:|:----------- |
| [Microsoft Azure Cloud](docs/azure/azure-cloud.md) | TODO...
| [AKS](docs/azure/aks.md) | TODO...
| [Azure API Management](docs/azure/azure-api-management.md) | TODO...
| [Azure App Service Plan](docs/azure/azure-app-service-plan.md) | TODO...
| [Azure App Service](docs/azure/azure-app-service.md) | TODO...
| [Azure Arc](docs/azure/azure-arc.md) | TODO...
| [Azure Configuration](docs/azure/azure-configuration.md) | TODO...
| [Azure Functions](docs/azure/azure-functions.md) | TODO...
| [Azure Load Balancing](docs/azure/azure-load-balancing.md) | TODO...
| [Azure Logic App](docs/azure/azure-logic-app.md) | TODO...
| [Azure Resource](docs/azure/azure-resource.md) | TODO...
| [Azure Resource Manager](docs/azure/azure-resource-manager.md) | TODO...
| [Azure SQL Server](docs/azure/azure-sql.md) | TODO...
| [Azure Security - Azure Key Vault](docs/azure/azure-security/azure-key-vault.md) | TODO...
| [Azure Security - Azure Active Directory](docs/azure/azure-security/azure-active-directory.md) | TODO...
| [Azure Messaging](docs/azure/messaging/messaging.md) | TODO...
| [Azure Messaging - Azure Service Bus](docs/azure/messaging/azure-service-bus.md) | TODO...
| [Azure Messaging - Azure Event Grid](docs/azure/messaging/azure-event-grid.md) | TODO...
| [Azure Messaging - Azure Event Hub](docs/azure/messaging/azure-event-hub.md) | TODO...
| [Azure Messaging - Azure Queue](docs/azure/messaging/azure-queue.md) | TODO...
| [Azure Messaging - Azure Web Pub Sub](docs/azure/messaging/azure-web-pub-sub.md) | TODO...
| [Azure NoSQL](docs/azure/nosql/azure-nosql.md) | TODO...
| [Azure NoSQL - CosmosDB](docs/azure/nosql/cosmosdb.md) | TODO...
| [Azure Storage](docs/azure/storage/storage.md) | TODO...
| [Azure Storage - Blob Storage](docs/azure/storage/blob.md) | TODO...
| [Azure Storage - File Storage](docs/azure/storage/file.md) | TODO...
| [Azure Storage - Queue Storage](docs/azure/storage/queue.md) | TODO...
| [Azure Storage - Table Storage](docs/azure/storage/table.md) | TODO...
 
### Modeling
| Topic | Description |
|:-------:|:----------- |
| [Modeling](docs/modeling/modeling.md) | TODO...
| [Architecture Diagram](docs/modeling/architecture-diagram.md) | TODO...
| [Class Diagram](docs/modeling/class-diagram.md) | TODO...
| [Component Diagram](docs/modeling/component-diagram.md) | TODO...
| [Conceptual Modeling](docs/modeling/conceptual-modeling.md) | TODO...
| [Data Model Notations](docs/modeling/data-model-notations.md) | TODO...
| [Domain Stroytelling](docs/modeling/domain-stroytelling.md) | TODO...
| [ER Diagrams](docs/modeling/er-diagrams.md) | TODO...
| [Event Modeling](docs/modeling/event-modeling.md) | TODO...
| [Event Storming](docs/modeling/event-storming.md) | TODO...
| [Logical Modeling](docs/modeling/logical-modeling.md) | TODO...

### Open Source
| Topic | Description |
|:-------:|:----------- |
| [Open Source](docs/open-source.md) | TODO...

### Code Review
| Topic | Description |
|:-------:|:----------- |
| [Code Review](docs/code-review.md) | TODO...

### Interview
| Topic | Description |
|:-------:|:----------- |
| [Interview](docs/interview.md) | TODO...

### Architecture Decision Records (ADR)
| Topic | Description |
|:-------:|:----------- |
| [Architecture Decision Records (ADR)](docs/adr.md) | TODO...

### Micro-Frontend
| Topic | Description |
|:-------:|:----------- |
| [Micro-Frontend](docs/micro-frontend.md) | TODO...

### Others
| Topic | Description |
|:-------:|:----------- |
| [Others](docs/others.md) | TODO...


## 🙏 Special Thanks

Thanks to the authors of the links for their valuable content, I gather them in one place for finding topics to read easier.

## ⭐ Support 

If you like, feel free to ⭐ this repository, it helps out :)

Thanks a bunch for supporting me!


## 🤝 Contribution

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mehdihadeli/awesome-software-architecture/blob/main/contributing.md) pages first.

Thanks to all [contributors](https://github.com/mehdihadeli/awesome-software-architecture/graphs/contributors), you're awesome and this wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

<a href="https://github.com/mehdihadeli/awesome-software-architecture/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=mehdihadeli/awesome-software-architecture" />
</a>
