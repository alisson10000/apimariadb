# apimariadb

#para utilizar a api use a extensão thunder cliente
Obs.: pode se utilizar o postman

#dependências

#npm init -y

#npm i express

#npm i mariadb

#npm i sequelize
Como utilizar a api:
Thunder para deletar:
Usa o json:
{
  "Codigo": 1
}
Thunder para criar:
Usa o json:
{
  "Descricao": "Nome do Produto",
  "DataCriacao": "2024-02-07T00:00:00.000Z",
  "DataAtualizacao": null,
  "createdAt": "2024-02-09T15:28:14.000Z",
  "updatedAt": "2024-02-09T15:28:14.000Z"
}




Para atualizar:
   {
      "Codigo":2,
  "Descricao": "fdfgdgfdfgdhgdfgdfdhg",
  "DataCriacao": "2024-02-07T00:00:00.000Z"
}
Para listar:
 GET localhost:4200/List
