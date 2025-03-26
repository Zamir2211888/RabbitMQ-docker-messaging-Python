# RabbitMQ-docker-messaging-Python

# Primero iniciamos el contenedor de RabbitMQ

```bash
docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:management
```

Acceder a la interfaz de administración de RabbitMQ:

```bash
http://"10.6.101.98":15672
```

Cambia "10.6.101.98" por tu localhost.

Las credenciales por defecto son:

1. Usuario: guest
2. Contraseña: guest


# Luego Creamos la carpeta python-producer y python-consumer.
```bash
mkdir python-producer
```
```bash
mkdir python-consumer
```