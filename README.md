# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Projetos Front-end.

## Endpoints

Assim como a documentação do JSON-Server-Auth traz (https://www.npmjs.com/package/json-server-auth)

## Base Url

Para fazer suas requisições utilize esse end point !
(https://bestsweather.herokuapp.com)

### Cadastro

POST /signup

Você irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

### Login

POST /signin

Use esse endpoint para realizar login com um dos usuários cadastrados na lista de "Users"

## state

POST / state

Use esse endpoint para cadastrar o ESTADO de acordo com o user!
