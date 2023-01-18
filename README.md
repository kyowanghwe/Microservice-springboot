# Microservice-springboot
https://www.youtube.com/watch?v=lh1oQHXVSc0


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
 - A Message Bus is a messaging infrastructure to allow different systems to communicate through a shared set of interfaces

### `Cache data(Redis)`
