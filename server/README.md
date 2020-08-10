# Funcionalidades

## Conexões

- Rota para listar o total de conexões realizadas;
- Rota para criar uma nova conexão;

## Aulas

- Rota para criar uma aula;
- Rota para listar aulas;
  - Filtrar port matéria, dia da semana e horário;

# Passo a passo seguido para instalação de pacotes
```bash
yarn init -y

yarn add typescript -D

# Criar o tsconfig.json (lembrar de alterar o target para es2017
yarn tsc --init

# Após adicionar tsnd, inserir no package.json o script:
#  "scripts": {
#    "start": "tsnd --transpile-only --ignore-watch node_modules --respawn src/server.ts"
#  },
yarn add ts-node-dev -D

yarn add express

yarn add @types/express -D

yarn add knex sqlite3

yarn add @types/knex -D

yarn add cors
yarn add @types/cors -D
```