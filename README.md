# Rabbit-mq
Example how to use RabbitMQ in C#.

In this sample has 2 Console Applications, one for the producer and one for the consumer. The producer is responsible for sending messages and the consumer for consume those messages.

# Run the application
To start this example, first of all you will need to run RabbitMQ an I suggest you run in a docker container.

In a command line, run the following command: docker run -d -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management This will start RabbitMQ in port 15672 (http://localhost:15672/)

After you will need to run the console applications. Run dotnet run command for the consumer and producer. Basically the producer will producing messages and the consumer will be consuming those messages. Run as many consumers do you want.
