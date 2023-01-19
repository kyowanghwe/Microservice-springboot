# Microservice-springboot
https://www.youtube.com/watch?v=lh1oQHXVSc0

### `What is MicroService`
Microservice Architecture is an architectural development style which builds an application as a collection of small autonomous services developed for a business domain. \
Benefit: 
  - Distributed and loosely coupled
  - Highly maintainable and testable
  - Independently deployable
  - Organized around business capabilities
  - Managed by a small team

### `Discovery Service`
Because The number of instances of a service and its locations **changes dynamically**. We need to know where these instances are and their names to allow requests to arrive at the target microservice. The Service Discovery mechanism helps us know where each instance is located.
Discovery Server will fetch all host address and port of service client registered

### `API Gateway`
API Gateway **accepts API** calls from the client application and **forwarding** this traffic to the appropriate service

  - Routing based on Request Header
  - Authentication 
  - Security
  - Load balancing 
  - SSL termination

### `Message Queue (Kafka, RabitMQ) / Message Bus`
https://stackoverflow.com/questions/7793927/message-queue-vs-message-bus-what-are-the-differences
 - A **Message Bus** is a messaging infrastructure to allow different systems to communicate through a shared set of interfaces

The basic idea of a **Message Queue** is a simple one:
  - Two (or more) processes can exchange information via access to a common system message queue.
  - The sending process places via some (OS) message-passing module a message onto a queue which can be read by another process

A **Message Bus** allows for multiple subscribers whereas a **Queue** will dequeue items one by one to anything listening to the queue.
### `Cache data(Redis)`


### `Differences between Microservices and Monolithic`
**Monolithic architecture** is like a big container that contains all the software components of an application. These applications are clubbed inside a single package within the application.
**Microservice Architecture** is an architectural development style which builds an application as a collection of small autonomous services developed for a business domain.

| Microservices | Monolithic Architecture |
| --- | --- |
| Service Startup is `fast` | Service startup `takes time` | 
| Microservices are `loosely coupled` architecture | Monolithic architecture is `tightly coupled` architecture |
| Changes done in a single data model does not affect other Microservices | Any changes in the data model affect the entire database |
| It mainly focuses on `products`, not projects | It mainly focuses on the whole `project` |
