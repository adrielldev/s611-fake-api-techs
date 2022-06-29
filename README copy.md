# Techs fake api

Essa fake api visa cadastrar usuários, e cadastrar suas tecnologias

# Endpoints

### Cadastro

POST /register <br/>
POST /signup <br/>
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.


### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"


### Fullacess

GET /fullacess 

Endpoint visando mostrar ao usuário a mensagem de boas vindas da aplicação


### Techs

POST /techs
GET /techs

Endpoints visando criar ou ter acesso as endpoints de um usuário especifico.
Outros users podem ver as outras techs, porém apenas o owner pode modificá-las
