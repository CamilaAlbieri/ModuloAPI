# 📘 Projeto CRUD com Entity Framework

![.NET](https://img.shields.io/badge/.NET-6.0-blueviolet?logo=dotnet)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-Core-green)
![Status](https://img.shields.io/badge/Status-Em%20Estudo-yellow)

Projeto simples desenvolvido para **estudos**, com foco em praticar **CRUD** usando **Entity Framework Core** em uma API .NET.

---

## 🚀 Tecnologias utilizadas
- [.NET 6/7](https://dotnet.microsoft.com/)  
- [Entity Framework Core](https://learn.microsoft.com/ef/core/)  
- Banco de Dados (**MySQL** ou **SQL Server**)  

---

## 📚 Conceitos praticados
- Estrutura de um CRUD (Create, Read, Update, Delete)  
- Instalação e configuração do **Entity Framework**  
- Criação de **entidades** e do **DbContext**  
- Configuração da **connection string**  
- Uso de **Migrations**  
- Criação de **Controllers** e endpoints REST:
  - Criar (POST)  
  - Obter por ID (GET)  
  - Obter por Nome (GET com parâmetro)  
  - Atualizar (PUT)  
  - Deletar (DELETE)  
- Entendimento dos **verbos HTTP**  

---

## 🔧 Como executar o projeto
1. Clone este repositório:
   git clone https://github.com/seu-usuario/nome-do-repo.git
   
3. Restaure os pacotes:
   dotnet restore

4. Configure a connection string no appsettings.json:
   "ConnectionStrings": {
  "DefaultConnection": "Server=localhost;Database=CrudDb;User Id=seu-usuario;Password=sua-senha;"
   }

5. Execute as migrations:
   dotnet-ef migrations add CriacaoTabelaContato
   dotnet ef database update

6. Rode a aplicação:
   dotnet run

7. A API estará disponível em:
   https://localhost:5001
