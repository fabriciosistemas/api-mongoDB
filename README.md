# api-mongoDB

Uma API que faz utilização do banco NoSQL MongoDb, onde operações CRUD podem ser feitas a partir de um programa como o Postman. Aplicação feita com base em curso da Digital Innovation One.

OBS: é preciso configurar o acesso ao banco no appsettings, passando sua ConnectionString (gerada pelo Atlas do MongoDB).

## Technologies

- .NET 5.0.100: backend
- MongoDB: para criar o banco na nuvem
- Postman 7.36.5: para fazer as operações CRUD
- Visual Studio Code: editor de texto usado na codificação
- Prompt de Comando do Windows: para rodar a aplicação com o comando dotnet run na pasta do projeto


Para teste:

https://localhost:5001/infectado

```json
{
	"dataNascimento": "1990-03-01",
	"sexo": "M",
	"latitude": -23.5630994,
	"longitude": -46.6565712
}
```


## Links Uteis:

- .net core - https://dotnet.microsoft.com/download

- visual code - https://code.visualstudio.com/download

- postman - https://www.postman.com/downloads/

- mongo atlas - https://www.mongodb.com/cloud/atlas/register


-----------------------------------------------

Referências:

https://docs.mongodb.com/

https://docs.mongodb.com/manual/

https://docs.mongodb.com/ecosystem/drivers/csharp/

https://docs.atlas.mongodb.com/
