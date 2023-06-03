# Projeto de Manipulação de Tabelas em MySQL

Este repositório contém uma coleção de exercícios de manipulação de tabelas em MySQL. Os exercícios foram projetados para ajudar a praticar e aprimorar as habilidades de manipulação de dados em um banco de dados relacional.

# MySQL

_SQL (Structured Query Language) é a linguagem mais usada para criar, pesquisar, extrair e também manipular dados dentro de um banco de dados relacional. Para que isso seja possível, existem comandos como o SELECT, UPDATE, DELETE, INSERT e WHERE, entre outros, que você aprenderá ao longo do curso._

> Todos os conceitos apresentados para se operar as informações em um banco de dados podem ser resumidos pelo conceito de CRUD.

- Adicionar novas informações ao banco de dados, utilizamos o conceito CREATE com o comando:
``INSERT INTO banco.tabela (coluna1, coluna2) VALUES (‘valor_A’, ‘valor_B’);``
- Obter as informações armazenadas no bando de dados, utilizamos o conceito READ, com o comando: ``SELECT colunaA, colunaB FROM banco.tabela;``
- Atualizar informações existentes no banco de dados, utilizamos o conceito UPDATE com o comando: ``UPDATE banco.tabela SET coluna1='valor' WHERE alguma_condicao;``
- Remover informações existentes no banco de dados, utilizamos o conceito DELETE com o comando: ``DELETE FROM banco.tabela WHERE alguma_condicao;``

### Para utilizar o MySQL em Docker

``docker container run --name container-mysql -e MYSQL_ROOT_PASSWORD=senha-mysql -d -p 3306:3306 mysql:8.0.31``

Rodar terminal do Docker ``docker exec -it container-mysql bash``

Terminal do MYSQL no Docker
``mysql -u root -p``

### Contato
Se tiver alguma dúvida ou consulta, entre em contato com Higino NEto por e-mail em engprodhigino@gmail.com.
