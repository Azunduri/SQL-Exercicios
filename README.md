# SQL Exercícios e Estudos

Este repositório contém exemplos e exercícios para praticar SQL, desde conceitos básicos até avançados.

## Estrutura do Repositório

- **introducao**: Comandos básicos para criar tabelas, inserir dados e realizar consultas simples.
- **intermediario**: Conceitos intermediários, incluindo JOINs, subconsultas e funções agregadas.
- **avancado**: Scripts para tópicos avançados, como stored procedures, triggers e views.

## Começando

Para executar os scripts SQL, use um software de banco de dados como MySQL, PostgreSQL ou SQL Server.

### Exemplos de Conteúdo

```sql
-- Exemplo de criação de tabela
CREATE TABLE usuarios (
    id INT PRIMARY KEY,
    nome VARCHAR(50),
    idade INT,
    email VARCHAR(50)
);

-- Exemplo de inserção de dados
INSERT INTO usuarios (id, nome, idade, email)
VALUES (1, 'João Silva', 30, 'joao@email.com');


```` ### Serve para vê o nomes das tabelas dentro de um banco de dados e esquema
USE vd;
GO
SELECT TABLE_NAME 
FROM INFORMATION_SCHEMA.TABLES 
WHERE TABLE_TYPE = 'BASE TABLE';

# contagem de um item de uma coluna

select atividae, COUNT(*) as contagem
from [2810202]
group by atividae
order by atividae;


### COLOCAR EM ORDEM
SELECT Nome, atividae
FROM [2810202]
ORDER BY atividae


# vê o nome das colunas
USE vd;  
GO
SELECT COLUMN_NAME
FROM INFORMATION_SCHEMA.COLUMNS
WHERE TABLE_NAME = '2810202';

#inner join
use [ciclo 15 - base]
select * 
from [2800202]
inner join PEDIDOS
on [2800202].Nome = PEDIDOS.NomePessoa;
