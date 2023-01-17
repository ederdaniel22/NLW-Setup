Projeto criado durante NLW Setup da escola Rocketseat

COMANDOS:

Criar o package.json

## npm init -y

Integrando FASTIFY

## npm i fastify

Integrando Typescript

## npm install typescript -D

INICIALIZAR

## npx tsc --init

Mudar o target no package.json para 2020

## npm i tsx -D

Para iniciar o server

## npx tsx src/server.ts

Para dar reload automático
no package.json alterar o script

## scripts

## "test": tsx watch src/server.ts

Rodar o projeto:

## npm run dev

Com servidor rodando abrir painel lateral e instalar o prisma:

## npm i -D prisma

## npm i @prisma/client

Executar o comando:

## npx prisma init --datasource-provider SQlite

Esse comando cria a pasta prisma e dentro dela o arquivo schema.prisma onde serão
adicionadas as informações do banco de dados.

Depois de incluir as informações

## npx prisma migrate dev

Para abrir a tabela no browser

## npx prisma studio

Para integrar o back com front end instalar o CORS

## npm i @fastify/cors
