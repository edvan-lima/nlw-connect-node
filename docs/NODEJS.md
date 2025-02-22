# 🌟 NodeJS Configuration

### Pré-requisitos

- Node.js v22.12.0 ou superior
- npm v9.8.1 ou superior

```bash
# Criar projeto e instalar dependências básicas
mkdir nlw-connect-node && cd nlw-connect-node
npm init -y

# Instalar Fastify (core do projeto)
npm i fastify

# Configurar ambiente TypeScript
mkdir src
npm i tsx typescript @types/node -D
npx tsc --init
```

https://github.com/tsconfig/bases

```typescript
// tsconfig.json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "compilerOptions": {
    "lib": ["es2023"],
    "module": "node16",
    "target": "es2022",
    "strict": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "moduleResolution": "node16",
    "outDir": "dist",
    "rootDir": "src",
    "sourceMap": true,
    "baseUrl": ".",
    "paths": {
      "@/*": ["./src/*"]
    }
  },
  "include": ["src/**/*"],
  "exclude": ["node_modules"]
}
```
