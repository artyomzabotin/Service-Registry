# Service Registry

## Description
Service registry - is a microservice that is created to register microservices in Eureka Server.

## Getting started
Copy and start these applications: 

[Worker Service](https://github.com/artyomzabotin/Worker-Service)

[Scheduler Service](https://github.com/artyomzabotin/Schedule-Service)

[Service Registry](https://github.com/artyomzabotin/Service-Registry)

Install locally [Kafka](https://kafka.apache.org/downloads) and start Zookeeper and Kafka servers. Then you need to run Redis and Redis Commander using Docker. Go to root of Scheduler Service repo and type:

````
docker-compose -f docker-compose.yml -up
````

Now you are ready to use application.

