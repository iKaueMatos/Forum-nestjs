# Hackaton 4.0 Saúde | Glasgow Back-end 🧠

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/iKaueMatos/Glasgow)](https://github.com/iKaueMatos/Glasgow/issues)

## Visão Geral

Esse projeto teve como objetivo aperfeiçoar meus conhecimento em padrões de projeto, 
utilizando typescript com framework nest.js que extremamente voltado para desenvolvimento de projetos escalaveis.
Baseado foi desenvolvido uma aplicação onde simula o comportamento de um forum onde as pessoas podem publicar um comentário, edita-lo e deleta-lo também e possivel
ser notificado sobre um comentário em que o usuario fez ou se encontra interligado.

## Tecnologias Utilizadas 🛠️

- Node.js
- Nest.js
- TypeScript
- Prisma
- Docker
- PostgreSQL
  
## Pré-requisitos 💡

1. Docker
2. WSL

### Instalação 📄

1. Clone o repositório: `git clone https://github.com/iKaueMatos/nest-js-clean/`
2. Instale as dependências: `npm install`

### Docker 🐳

Para rodar o projeto com Docker:

**Atenção: ** rodando o projeto com docker todo o ambiente do back-end irar ser inicializado de maneira simultanea, possibilitando fazer requisições para API.

1. Instale o Docker e o Docker Compose
2. Execute: `docker-compose up`

### Executando o Projeto sem o Docker ⚙️

Atenção: rodando o projeto sem a utilização do docker sera necessário instalar um SGBD na própria maquina. 

- **Desenvolvimento**: `npm run start:dev`
- **Produção**: `npm run start:prod`
