# Nombre de la aplicación - redis
---
## Comandos ejecutados - Todos los comandos que usaste, uno por uno:

docker search redis

docker pull redis

docker images

## Comando docker run completo:
docker run -d --name mi-redis -p 6379:6379 redis

## Comandos de verificación:
docker ps

docker logs mi-redis

## Comandos de limpieza:
docker stop mi-redis

docker rm mi-redis

docker rmi redis

## Explicación breve - Qué hace cada flag del comando docker run que usaste
-d: para correr en 2do plano

--name: nombre del contenedor

-p: puerto 6379 del host al puerto 6379 del contenedor

redis: imagen oficial

## Evidencia:
Screenshot de docker ps mostrando el container corriendo:

![container corriendo](https://github.com/githanshync/curso-docker-kubernetes-tareas/blob/main/clase1/screenshots/docker-ps.jpg)

Screenshot del navegador (si es httpd) o salida de docker logs (si es redis/mysql):

![docker logs](https://github.com/githanshync/curso-docker-kubernetes-tareas/blob/main/clase1/screenshots/redis-log.jpg)

Screenshot o salida mostrando que el container fue eliminado correctamente:

![limpieza redis](https://github.com/githanshync/curso-docker-kubernetes-tareas/blob/main/clase1/screenshots/limpieza-redis.png)


