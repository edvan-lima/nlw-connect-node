# 🐳 Docker Configuration

### Pré-requisitos

- Docker version 27.5.1
- Docker Compose version v2.32.4-desktop.1

```bash
# Construir e iniciar containers em background

docker-compose up -d --build

# Verificar status dos containers

docker-compose ps

# Parar containers

docker-compose down

# Visualizar logs da aplicação

docker-compose logs -f app

# Forçar rebuild da imagem

docker-compose build --no-cache
```
