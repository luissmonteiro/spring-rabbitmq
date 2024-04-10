# Spring Boot RabbitMQ Project

This project is a simple demonstration of how to use RabbitMQ with Spring Boot. It is written in Java and uses Maven as a build tool.

## Project Structure

The project is divided into two main parts: the producer and the consumer.

### Producer

The producer is responsible for sending messages to the RabbitMQ server. The main class for this is `RabbitMQProducer.java` which uses the `RabbitTemplate` to send messages. The exchange and routing key used for sending messages are configured via application properties.

### Consumer

There are two consumers in this project: `RabbitMQConsumer.java` and `RabbitMQJsonConsumer.java`. The former consumes simple string messages while the latter consumes JSON messages and converts them into `User` objects.

## Running the Project

To run the project, you need to have RabbitMQ server running. After that, you can use the `publish message.http` file to send HTTP requests to the application which will then publish the messages to RabbitMQ.

## Technologies Used

- Java
- Spring Boot
- RabbitMQ
- Maven

## Git Repository

The project is hosted on GitHub at the following URL: https://github.com/luissmonteiro/spring-rabbitmq.git. The main branch is `main`.

## Contact

For any further questions, you can reach out to the repository owner.
