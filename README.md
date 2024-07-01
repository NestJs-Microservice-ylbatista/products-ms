<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Product Microservice





## Dev

1. Clonar repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `.env.template`
4. Ejecutar migración de prisma `npx prisma migrate dev`
5. Levantar servidor NATS
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Ejecutar `npm run start:dev`