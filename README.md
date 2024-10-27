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