# AutoManager API 🚗

Sistema simples de cadastro de carros desenvolvido em **.NET 8 + MySQL**.

## Funcionalidades
- Cadastrar novo carro
- Listar todos os carros
- Consultar carro por ID
- Atualizar dados de um carro
- Excluir carro

## Tecnologias
- .NET 8 Web API
- Entity Framework Core
- MySQL
- Swagger

## Estrutura da Tabela
| Campo | Tipo | Descrição |
|-------|------|------------|
| Id | int | Identificador único |
| Marca | varchar(50) | Nome da marca do carro |
| Modelo | varchar(50) | Nome do modelo |
| Ano | int | Ano de fabricação |
| Cor | varchar(30) | Cor do carro |
| Preco | decimal(10,2) | Valor do carro |

## Como rodar o projeto
1. Crie o banco de dados no MySQL:
   ```sql
   CREATE DATABASE automanager;