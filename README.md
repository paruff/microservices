# microservices


## Links

### Implement DB as a service.
* Does MongoDB provide a REST interface?

### Replication.
* Service should hide the replication.
* Research/devise patterns.
* Implement database replication for Piper.

### Elasticity.

### Authentication and authorization.
* TAM integration.
* Patterns: e.g., individual user authentication at the service versus at the end use application.

### Encryption.
* TLS.
* IP6.
* Encryption of secret stores (e.g., etcd).
* AWS: http://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-agent-config.html

Multi-tenancy.
Brian’s talk.

Recovery.
Discover how Kubernetes handles recovery.
Implement for SHS.

Rollback.
Primary issue is database migration reversibility.
Research/devise patterns.

Common stacks.
Spring Boot.
JBoss.
Drop Wizzard.
Go.
Nginx.

Export for analytics.

Consistency patterns.

Messaging and queueing patterns.
RabbitMQ, ZeroMQ, Netty.
gRPC. Use at Square: https://www.slideshare.net/apigee/grpc-the-story-of-microservices-at-square-59995024
Event-driven consistency. Nginx article: https://www.nginx.com/blog/event-driven-data-management-microservices/
Apache Thrift: https://thrift.apache.org/

Logging.
Research Apache Kafka.

Caching.
Research Debezium.

Storage.
Integration with block storage.

Service versioning.

Blueprints and pattern management.

Base image management.

Capacity management.

Tradeoffs.
Martin Fowler: https://martinfowler.com/articles/microservice-trade-offs.html
