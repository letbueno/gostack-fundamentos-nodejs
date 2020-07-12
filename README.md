![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67](https://user-images.githubusercontent.com/50913322/87230209-c2d41600-c384-11ea-9339-71a8deacfccc.png)


<h1 align="center">:rocket: Desafio 05 do Nível 02 do Bootcamp GoStack 11.0 - Iniciando o Back-End :rocket:</h1>

A proposta deste desafio era testar os conhecimentos do módulo Iniciando o Back-End. Onde consistia implementar o back-end da aplicação de gestão de transações, para armazenar transações financeiras de entrada e saída e permitir o cadastro e a listagem dessas transações.

### Funcionalidades Implementadas :bookmark_tabs:
- Criar a tabela de transação no banco de dados. :heavy_check_mark:
- Implementar as rotas e as funções de cadastrar, listar e deletar uma transação. :heavy_check_mark:


### Como Rodar a Aplicação :desktop_computer:


- No terminal, clone o projeto:

```
https://github.com/letbueno/gostack-fundamentos-nodejs/
```

- Instale as dependências:
```
yarn 
```

- Para executar a aplicação:
```
yarn dev:server
```

### Como testar as requisições 	:technologist:
Para testar as requisições você pode fazer uso de uma API Client, a que eu usei para realizar o projeto foi o [Insomnia](https://insomnia.rest).

- Para listar uma transação: **`GET /transactions`**
- Para cadastrar uma requisição: **`POST /transactions`**
- Para deletar uma requisição: **`DELETE /transactions/:id`**

![fundamentosnode](https://user-images.githubusercontent.com/50913322/87253808-617b7800-c454-11ea-9b26-89c37ce0db84.jpg)

### Como Rodar os Testes? :desktop_computer:
Os testes foram desenvolvidos pela Rocketseat, para testar se as funcionalidades seguem os parâmetros indicados:
- Cadastrar uma nova transação. :heavy_check_mark:
- Não permitir uma transação de saída de saldo caso não há saldo suficiente. :heavy_check_mark:
- Deletar uma transação. :heavy_check_mark:

Para rodar o teste:
```
yarn test
```
### Dependências e Tecnologias :books: 
- [Node.js](https://nodejs.org/en/docs/)
- [Javascript](https://devdocs.io/javascript/)
- [Typescript](https://www.typescriptlang.org/docs/home.html)
- [Typeorm](https://typeorm.io/#/)
- [Cors](https://www.npmjs.com/package/cors)

### Participante: 
|Name|E-mail|Course|
| -------- | -------- | -------- |
|Leticia Bueno Martins|leticia.bueno.martins@gmail.com|Bootcamp GoStack 11.0|
