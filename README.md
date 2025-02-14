<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Orders Microservice

## Dev

1. Clone rep
2. Install dependencies
3. Create `.env` file based on `env.example`
4. Exec prisma migration `npx prisma migrate dev`
5. Have launched database with `docker compose up -d`
6. Have launched NATS server

```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```

7. Exec `npm run start:dev`
