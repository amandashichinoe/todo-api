# To-Do List


API desenvolvida utilizando o tutorial Aplicativos API Web da Microsoft, disponível em: https://docs.microsoft.com/pt-br/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio-code


| API                       | Descrição                                 | Corpo da Solicitação      | Corpo da resposta                    |
| ------------------------- | ----------------------------------------- | ------------------------- | ------------------------------------ |
| GET /api/TodoItems        | Obter todos os itens de tarefas pendentes | Nenhum                    | Matriz de itens de tarefas pendentes |
| GET /api/TodoItems{id}    | Obter um item por ID                      | Nenhum                    | Item de tarefas pendentes            |
| POST /api/TodoItems       | Adicionar um novo item                    | Item de tarefas pendentes | Item de tarefas pendentes            |
| PUT /api/TodoItems{id}    | Atualizar um item existente               | Item de tarefas pendentes | Nenhum                               |
| DELETE /api/TodoItems{id} | Excluir um item                           | Nenhum                    | Nenhum                               |



## Design do aplicativo



![O cliente é representado por uma caixa à esquerda. Ele envia uma solicitação e recebe uma resposta do aplicativo, uma caixa desenhada à direita. Dentro da caixa do aplicativo, três caixas representam o controlador, o modelo e a camada de acesso a dados. A solicitação é recebida no controlador do aplicativo e as operações de leitura/gravação ocorrem entre o controlador e a camada de acesso a dados. O modelo é serializado e retornado para o cliente na resposta.](https://docs.microsoft.com/pt-br/aspnet/core/tutorials/first-web-api/_static/architecture.png?view=aspnetcore-5.0)



## Etapa 1  - Criar uma API Web


### Aprendizados

* Criar um projeto de API Web.
* Adicionar uma classe de modelo e um contexto de banco de dados.
* Fazer scaffold de um controlador com métodos CRUD.
* Configurar o roteamento, os caminhos de URL e os valores retornados.
* Chamar a API Web com o Postman.


### Pacotes Utilizados

* Microsoft.EntityFrameworkCore.InMemory
* Microsoft.VisualStudio.Web.CodeGeneration.Design
* Microsoft.EntityFrameworkCore.Design
* Microsoft.EntityFrameworkCore.SqlServer


