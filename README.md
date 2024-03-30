# Gerenciamento de Tarefas

Este é um projeto de backend para um sistema de gerenciamento de tarefas. O sistema possui um banco de dados MySQL para armazenar informações de usuários e suas respectivas tarefas. A API é desenvolvida em Node.js e segue a arquitetura MVC. O objetivo principal é fornecer funcionalidades de autenticação de usuários, operações CRUD para tarefas, atribuição de tarefas e filtros/ordenações.

## Funcionalidades

- Autenticação de Usuários: Registro, login e logout do sistema.
- CRUD de Tarefas: Operações de criação, leitura, atualização e exclusão de tarefas.
- Atribuição de Tarefas: Capacidade de atribuir tarefas a usuários do sistema.
- Filtragem e Ordenação: Funcionalidades para filtrar e ordenar tarefas com base em diferentes critérios.

## Estrutura do Projeto

- `docs`: Contém o DER (Diagrama de Entidade-Relacionamento) conceitual e lógico.
- `bd`: Scripts de criação do banco de dados.
- `testes`: Script de população do banco de dados com dados de teste e arquivo Insomnia com rotas de teste.
- `api`: Contém a implementação da API back-end com os CRUDs no padrão MVC.

## Desafio

Desenvolver as funcionalidades descritas, garantindo que a aplicação seja capaz de lidar com as operações de gerenciamento de tarefas de forma eficiente e segura.

## Tecnologias Utilizadas

- Node.js
- MySQL
- Express.js
- Insomnia (para testes)

## Como Testar

1. Clone este repositório do GitHub.
2. Certifique-se de ter o Node.js e o MySQL instalados em sua máquina.
3. Importe o script `script.sql` para criar o banco de dados e as tabelas necessárias.
4. Importe o script `testes.sql` para popular o banco de dados com dados de teste.
5. Instale as dependências do projeto utilizando o comando `npm install`.
6. Inicie o servidor executando `nodemon`.
7. Utilize o Insomnia ou qualquer outra ferramenta de API para testar as rotas disponíveis. Importe o arquivo `insomnia.json` para obter as rotas de teste pré-configuradas.