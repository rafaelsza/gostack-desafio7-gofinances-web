# GoFinances com ReactJS

Desafio n°7 do bootcamp GoStack, onde tivemos que desenvolver um front-end web utilizando ReactJS e TypeScript.

### Funcionalidades:

- Listar transações retornadas do back-end desenvolvido no [desafio n°6](https://github.com/rafaelsza/gostack-desafio6-typeorm-upload).
- Exibir o valor total de entradas, de saídas e o saldo.
- Importar um arquivo CSV com dados de transações na rota /import.

### Utilizado:

- **TypeScript**
- **ReactJS**
- **ReactDOM**
- **React Router DOM**: para realizar a navegação entre páginas.
- **Axios**: realizar conexão com a API.
- **Polished**: trabalhar com cores no React.
- **Styled Components**: criar e estilizar componentes.

### Padronização de código utilizando:

- ESLint
- Prettier

## Para utilizar em sua máquina:

**Necessário ter o
[NodeJS](https://nodejs.org/en/download)
instalado.**

> No projeto foi utilizado o
[yarn](https://yarnpkg.com/getting-started/install)
como gerenciador de pacotes, mas caso queira utilizar o npm basta substituír os comandos que começam com yarn por npm.

Clone o projeto:
```
git clone https://github.com/rafaelsza/gostack-desafio7-gofinances-web.git
```

Entrar na pasta raíz:
```
cd gostack-desafio7-gofinances-web
```

Então executar yarn para instalar as dependências do projeto:
```
yarn
```

Agora execute
```
yarn start
```

> **Lembrando que você deve estar com o back-end em execução na sua máquina.**

Pronto! O app já estará rodando em sua máquina.

Utilize o navegador para acessar as rotas abaixo:

**ROTA**: [http://localhost:3000](http://localhost:3000)

Lista todas as transações retornadas da API, e o balanço das mesmas.

**ROTA**: [http://localhost:3000/import](http://localhost:3000/import)

Realiza o upload de um arquivo CSV e importa os dados das transações contidas no mesmo.

A formatação do arquivo deverá ser da seguinte forma:
  ```json
  title, type, value, category
  Salário, income, 500, Freelance
  Padaria, outcome, 200, Alimentação
  ```
