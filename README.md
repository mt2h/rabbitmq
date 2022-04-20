# RabbitMQ

Commands:

````bash
docker pull rabbitmq:3-management
docker run --rm -d -p 15672:15672 -p 5672:5672 --name my_rabbitmq rabbitmq:3-management
#http://localhost:15672
#guest guest
````

# Images

## Element and Attributes

Element of mesaaging system

![Element of mesaaging system](./img/1.png)

Binding

![Binding](./img/2.png)

Attributes of Messages

![Attributes of Messages](./img/3.png)

Attributes of a Queue

![Attributes of a Queue](./img/4.png)

Attributes of a Exchange

![Attributes of a Exchange](./img/5.png)

## Exchanges

![Exchanges](./img/6.png)

Exchanges

![Fanout Exchange](./img/7.png)

Add Fanout Exange

![ AddFanout Exchange](./img/8.png)

Add Queue

![Add Queue](./img/9.png)


Binding Queue

![Binding Queue](./img/10.png)

Publish message from the Exchange

![Publish Message](./img/11.png)

Get messages from the Queue

![Get Message](./img/12.png)

![Get Message](./img/13.png)