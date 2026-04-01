# PROJETO AULA MONGODB API

Este projeto foi desenvolvido como parte de uma **aula online no YouTube** para aprendizado de **.NET 10 e MongoDB**, com adaptações e implementações próprias.

## Descrição
Este Projeto é uma API RESTful desenvolvida em .NET10, conectada com um banco de dados MongoDB, criada sob fins educacionais.
O objetivo é demonstrar operações básicas de CRUD com MongoDB e como criar endpoints seguros e funcionais.

## Tecnologias Utilizadas
> .NET 10
> C#
> MongoDB
> MongoDb Compass
> Swagger/ OpenAPI para documentação da API

## Funcionalidades 
> Conexão com banco MongoDB local ou remoto
> CRUD copm´pleto para coleção Produto
> Swagger UI para teste dos endpoints
> Configuração dfe variáveis de ambiente para conexão segura

## Estrutura do Projeto
/ProjetoAulaMongoAPI
│
├─ Controllers/
│   └─ ProdutoController.cs
├─ Models/
│   └─ Produto.cs
│   └─ ProdutoDatabaseSettings.cs
├─ appsettings.json
├─ Program.cs
├─ README.md

## Como Rodar o Projeto
1. Clonar o repositório:
   git clone https://github.com/BarbaraFSilva7/ProjetoAulaMongoAPI.git
2. Abrir o Visual Studio 2022 ou superior
3. Restaurar pacotes NuGet
4. Configurar MongoDB em appsettings.json
5. Executar a API
6. Abrir o Swager para testar:
   https://localhost:<porta>/swagger
