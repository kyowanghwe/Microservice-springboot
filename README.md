# Microservice-springboot
https://www.youtube.com/watch?v=lh1oQHXVSc0

### `What is MicroService`
Microservice Architecture is an architectural development style which builds an application as a collection of small autonomous services developed for a business domain.
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


A **Message Bus** allows for multiple subscribers whereas a **Queue** will dequeue items one by one to anything listening to the queue.
### `Cache data(Redis)`
