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

## Fanout Exchange

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

## Direct Exchange

![Direct Exange](./img/14.png)

![Direct Exange On Rabbit](./img/15.png)

![Queues for Direct Exange On Rabbit](./img/16.png)

![Queue Error On Direct Exange](./img/17.png)

![Queue Error On Direct Exange](./img/18.png)

![Send Message to Direct Exange](./img/19.png)

![Get Message on Direct Exange](./img/20.png)

## Topic Exchange

![Topic  Exange](./img/21.png)

![Topic  Exange Schema](./img/22.png)

![Topic Exange On Rabbit](./img/23.png)

![Queue 1 On Topic Exange](./img/24.png)

![Queue 2 On Topic Exange](./img/25.png)

![Queue 3 On Topic Exange](./img/26.png)

![Send Message to Topic Exange](./img/27.png)

![Get Message on Topic Exange](./img/28.png)

## Headers Exchange

![Headers  Exange](./img/29.png)

![Headers Exange On Rabbit](./img/30.png)

![Queue 1 for Headers Exange On Rabbit](./img/31.png)

![Queue 2 for Headers Exange On Rabbit](./img/32.png)

![Send first Message to Exange](./img/33.png)

![Send second Message to Exange](./img/34.png)
