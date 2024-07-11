# Gestor de Clientes

## Resumo do Projeto
O Gestor de Clientes é uma aplicação para gerenciar informações de clientes, onde você pode cadastrar, editar e remover clientes. Este projeto foca no uso de `structs` em C#. O sistema gerencia três campos principais: nome, email e CPF do cliente.

## ✔️ Técnicas e Tecnologias Utilizadas
- .NET (C#)
- Entity Framework
- SQL Server
- ASP.NET Core
- Bootstrap (para a interface do usuário)
- Trello (para gerenciamento de tarefas)
- Visual Studio (como IDE)

## 🛠️ Abrir e Rodar o Projeto

### Pré-requisitos
- [.NET Core SDK](https://dotnet.microsoft.com/download) instalado.
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) instalado e configurado.

### Passos para Rodar o Projeto Localmente

1. Clone o repositório:
   ```sh
   git clone git@github.com:SandraMatosTech/portif-lio.git
   
2. Navegue  ate o diretório do projeto: cd portif-lio/GestorDeClientes
   
3.Restaure a dependencia do projeto: dotnet restore

4.Atualize a string de conexão com o banco de dados no arquivo 'appsettings.json'

5.Aplique as migrações do Entity Framework para criar o banco de dados:dotnet ef database update

6.Execute a aplicação: dotnet run

7.Abra seu navegador e acesse https://localhost:5001 para ver a aplicação em execução.
