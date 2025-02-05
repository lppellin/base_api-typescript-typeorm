# API TypeScript com TypeORM

Este é um projeto template para APIs, construído com TypeScript e TypeORM.

## Passos para executar este projeto:

1. Instale as dependências com:
    ```sh
    npm install
    ```

2. Configure as variáveis de ambiente no arquivo [.env](http://_vscodecontentref_/0) (veja o exemplo em [.env.example](http://_vscodecontentref_/1)):
    ```env
    DB_HOST=localhost
    DB_PORT=5432
    DB_USER=user
    DB_PASSWORD=1234
    DB_NAME=postgres
    NODE_ENV=development
    ```

3. Execute o projeto com:
    ```sh
    npm run dev
    ```

## Scripts disponíveis

- `npm run dev`: Inicia o servidor em modo de desenvolvimento.
- `npm run test`: Executa os testes (atualmente não há testes configurados).
- `npm run migration:run`: Executa as migrações do banco de dados.
- `npm run migration:revert`: Reverte as migrações do banco de dados.
- `npm run lint`: Executa o linter nos arquivos TypeScript.
- `npm run lint:fix`: Executa o linter e corrige problemas automaticamente.
- `npm run prettier`: Formata o código usando Prettier.
- `npm run prettier:check`: Verifica a formatação do código usando Prettier.
- `npm run format`: Formata todo o projeto usando Prettier.

## Estrutura do Projeto

- `src`: Diretório principal.
  - `controllers/`: Controladores da aplicação.
  - `entity/`: Entidades do TypeORM.
  - `middlewares/`: Middlewares da aplicação.
  - `migration/`: Migrações do banco de dados.
  - `routes/`: Rotas da aplicação.
  - `data-source.ts`: Configuração do banco de dados do TypeORM.
  - `index.ts`: Arquivo principal que inicializa o servidor.
