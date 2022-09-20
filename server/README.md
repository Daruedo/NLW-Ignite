# Back-end

> Pesquisar CDN (Content Delivery Network)

Iniciando Projeto Backend:

npm init -y

Instalar Express:

npm install express

Instalar Typescript como dependencia de desenvolvimento:

npm install typescript -D

Iniciar arquivo tsconfig:

npx tsc --init

Instalar tipagens Express:

npm install @types/express -D

Instalar ts-node-dev:

npm install ts-node-dev -D

Instalar CORS:

npm i cors
npm i @types/cors -D


..
Instalar Prisma:
npm i prisma -D

Iniciar configurações prisma:
npx prisma init --datasource-provider SQLite

Rodar migration:
npx prisma migrate dev

npm i @prisma/client

```
npx prisma studio
```

## Entidades

### Game

id
title
bannerUrl

### Ad

id
gameId
name
yearsPlaying
discord
weekDays
hourStart
hourEnd
useVoiceChannel
createdAt

## Casos de uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio