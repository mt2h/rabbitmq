# RabbitMQ

Commands:

````bash
docker pull rabbitmq:3-management
docker run --rm -d -p 15672:15672 -p 5672:5672 --name my_rabbitmq rabbitmq:3-management
#http://localhost:15672
#guest guest
````