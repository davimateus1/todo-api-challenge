<h1 align="center">
  API - USUÁRIOS E TODOLIST
</h1>

<h4 align="center"> 
	Esta API foi desenvolvida no desafio do curso Ignite Node.JS da RocketSeat 
</h4>

<br>

## 💻 Sobre o Projeto

O desafio consiste em criar uma API de usuários armazenando o nome e username como fazer todo o CRUD de usuários:
  * Criar uma nova todo
  * Listar todas as todos
  * Alterar o title e deadline de uma todo existente
  * Marcar uma todo como feita
  * Excluir uma todo
Tudo isso para cada usuário em específico (Passando o username no header da requisição).

<br>

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- Node.js
- Express
- Uuid V4
- Jest
- Nodemon
- Supertest

<br>

## 💡 Como executar o projeto

É necessário clonar o repositório para a sua máquina e seguir as informações a seguir.

TESTES:

```bash
  Para rodar os testes execute o comando "yarn test" ou "npm run test"
```

BACKEND:

```bash
01 - Acessar a pasta do projeto no terminal e rodar o comando `yarn`

02 – Rodar o comando `yarn dev` para startar a aplicação

## Rotas para api

# Rota padrão
* http://localhost:3333

* Criar um usuário - POST /users
  - passar o objeto name e no headers passar o username
  {
	"name": "Davi",
	"username": "davi123"
  }

* Mostrar todas as todos - GET /todos

* Inserir uma todo para o usuário - POST /todos
  {
	"title": "Ir para a academia",
	"deadline": "2022-12-12"
  }

* Alterar uma todo - PUT /todos/:id
  {
	"title": "Estudar NodeJS",
	"deadline": "2022-12-12"
  }

* Alterar uma todo para realizada - PATCH /todos/:id

* Deletar uma todo - DELETE /todos/:id

Observação: Com excessão da rota POST /users, todas as outras rotas devem passar o username no header da requisição.
```

<br>

---

<h3 align="center"> Feito por Davi Mateus, no Desafio 01 - Conceitos do Node no Ignite, curso da Rocketseat </h3>

