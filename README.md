# 🚀 NLW Connect - (Node.js)

![Node.js Version](https://img.shields.io/badge/node-%3E%3D22.12.0-brightgreen)
![npm Version](https://img.shields.io/badge/npm-%3E%3D9.8.1-blue)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

### Pré-requisitos

- Node.js v22.12.0 ou superior
- npm v9.8.1 ou superior
- PostgreSQL instalado
- Redis (opcional para cache)

### 🚀 Começando

```bash
# Clonar repositório
git clone https://github.com/edvan-lima/nlw-connect-node.git
cd nlw-connect-node

# Instalar dependências
npm install

# Configurar variáveis de ambiente
cp .env.example .env
# Edite o .env com suas credenciais
```

### 📦 Bibliotecas Instaladas

**Principais Dependências:**

- [`fastify`](https://fastify.dev): Framework web rápido
- [`zod`](https://zod.dev): Validação de schemas
- [`drizzle-orm`](https://orm.drizzle.team): ORM Type-safe
- [`@fastify/jwt`](https://github.com/fastify/fastify-jwt): Autenticação JWT

### 📂 Estrutura do Projeto

```bash
/src
├── drizzle/         # Configuração do drizzle
├── functions/       # Todas as funções da API
├── redis/           # Configuração do redis
├── routes/          # Todas as rotas da API
├── env.ts           # Validação do .env com zod
└── server.ts        # Inicialização do servidor

```

### ✨ Features Principais

✅ Documentação Swagger automática

✅ Validação de dados com Zod

✅ ORM moderno com Drizzle

✅ Cache com Redis

✅ Configuração TypeScript otimizada

### 📑 Documentação

- [Guia do Node.js](docs/NODEJS.md)
- [Guia do Drizzle ORM](DRIZZLE.md)
- [Guia do Docker](docs/DOCKER.md)
