# SQL Projects Repository

Este repositório contém projetos SQL para análise de dados e automação. Os projetos incluem consultas complexas, otimizações e exemplos de integração com Python.

## Estrutura
- `scripts/`: Contém scripts SQL organizados por caso de uso.
- `datasets/`: Inclui arquivos de dados como backups `.bak` e CSVs de exemplo.
- `notebooks/`: Notebooks Jupyter para integração Python + SQL.

## Pré-requisitos
- SQL Server 2019 ou superior
- Python 3.8+ com as bibliotecas `pyodbc`, `pandas` e `sqlalchemy`
- Acesso ao banco AdventureWorks2019 (backup fornecido em `datasets/`).

## Como usar
1. Restaure o banco de dados usando o arquivo `datasets/adventureworks2019.bak`.
2. Rode as consultas no arquivo `scripts/sales_analysis.sql`.
3. Use o notebook `notebooks/analysis_with_python.ipynb` para análises adicionais.

---
