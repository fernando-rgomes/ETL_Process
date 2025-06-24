# Projeto ETL com SQL Server 🚀

Este projeto realiza um processo simples de ETL (Extração, Transformação e Carga) utilizando Python, Pandas e SQL Server. Os dados são tratados em um notebook Jupyter e posteriormente carregados para uma tabela chamada `VENDAS` no banco de dados SQL Server.

## 📊 Estrutura dos Dados

A base utilizada possui as seguintes colunas:

- `data`: data da venda
- `nome`: nome do vendedor
- `id`: identificador do vendedor
- `vendas`: número de vendas realizadas

Exemplo:

| data       | nome      | id   | vendas |
|------------|-----------|------|--------|
| 2024-05-20 | jackson   | 7839 | 4      |

## ⚙️ Tecnologias utilizadas

- Python 3.10+
- Jupyter Notebook
- pandas
- sqlalchemy
- pyodbc
- SQL Server

## 🧼 Tratamentos realizados

- Preenchimento de valores ausentes em `vendas` com 0
- Conversão da coluna `vendas` para o tipo `int`

## 🛠️ Requisitos

Instale as bibliotecas necessárias com:

```bash
pip install pandas sqlalchemy pyodbc
# ETL_Process
Processo de ETL Simples utilizando Python, Pandas e SqlAlchemy
