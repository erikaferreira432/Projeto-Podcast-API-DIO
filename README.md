# Podcast API

API desenvolvida no bootcamp da DIO com Node.js e TypeScript para listar e filtrar episódios de podcasts em vídeo. O projeto utiliza o módulo HTTP nativo do Node.js e dados armazenados em um arquivo JSON local.

## Funcionalidades

- Listar episódios cadastrados.
- Filtrar episódios pelo nome do podcast.

## Tecnologias

- Node.js
- TypeScript
- TSX
- TSUP

## Como executar

Instale as dependências:

```bash
npm install
```

Execute o projeto:

```bash
npm run start:dev
```

Acesse:

```txt
http://localhost:3333/api/list
```

## Rotas

```http
GET /api/list
```

```http
GET /api/podcasts?p=flow
```
