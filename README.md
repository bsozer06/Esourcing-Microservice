# Overview of the Project

<img src="https://user-images.githubusercontent.com/56292618/191577527-2ebd6b33-39c4-4396-a3c5-216f1a335a73.png" width="500">

There are 3 services in this project
* ESourcing.Products
* ESourcing.Order
* ESourcing.Sourcing

RabbitMQ is used as a message broker.
* ESourcing.EventBusRabbitMQ

To manage all services in the system, API Gateway service is created.
* ESourcing.APIGateway

For frontend, Blazor is utilized with .NET MVC project.
* ESourcing.UI

Docker was used for each services. And they are managed on docker-compose.yml
