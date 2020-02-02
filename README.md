
# Projeto CRUD em Node.js utilizando middlewares

Este é um simples projeto de CRUD em Node.js, utilizando middleware global para controlar o tempo de execução das rotas e middleware local para verificar se o usuário já existe no array. Segue abaixo as rotas para testes.

**Incluir um usuário**

Método POST: /users, e no body passar na propriedade name o nome do usuário que quer incluir.

    {
    	"name": "Sansão"
    }

**Alterar um usuário**

Método PUT: /users/:index, onde index é a posição no array que se encontra o usuário que queira alterar o nome, e no body passar na propriedade name o novo nome do usuário.

    {
    	"name" : "Ricardo Silva"
    }

**Listar todos os usuários**

Método GET: /users

**Listar um usuário**

Método GET: /users/:index, onde index é a posição no array que se encontra o usuário em que quer listar.

**Excluir um usuário**

Método DEL: /users/:index, onde index é a posição no array do usuário que quer excluir do array.
