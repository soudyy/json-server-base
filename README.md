URL:
https://json-serverteste.herokuapp.com

Rotas:

--Para cadastrar usuarios
https://json-serverteste.herokuapp.com/users

Para cadastrar um usuario, editar e ler ele voce tem que ser o dono dele. No cadastro devemos cadastrar
email e password obrigatoriamente, nome, idade e outros qualquer tipo são opcionais.
{
"email":"email@email.com",
"password":"123456",
"name":"nome",
"age": 22
}

--Para cadastrar animais
https://json-serverteste.herokuapp.com/animals

Apenas o dono pode editar mas todos podem visualizar. No Cadastro de animais devemos cadastrar type e name, outros itens são opcionais.
{
"type":"cat"
"name":"nome"

}
--Para cadastrar comidas
https://json-serverteste.herokuapp.com/foods

O usuario deve estar logado para poder cadastrar comidas, mas todos podem ler. No cadastro devemos cadastrar um type e name, outros são opcionais

{
"type":"fruta"
"name":"Abacate"
"Quantity": 3
}
