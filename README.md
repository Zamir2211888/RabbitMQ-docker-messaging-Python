# RabbitMQ-docker-messaging-Python

Primero iniciamos el contenedor de RabbitMQ

```bash
docker run -it --rm --name rabbitmq -p 5552:5552 -p 15672:15672 -p 5672:5672 -e RABBITMQ_SERVER_ADDITIO

´´´


docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:management

Para acceder a la interfaz de administración de RabbitMQ, ve a http://"10.6.101.98":15672

Cambia "10.6.101.98" por tu localhost.

Las credenciales por defecto son:

Usuario: guest
Contraseña: guest
