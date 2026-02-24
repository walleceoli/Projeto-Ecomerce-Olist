# Projeto de Análise de Dados - E-commerce Olist
## Objetivo
Desenvolver um projeto de análise de dados utilizando a base de dados do Olist disponível no Kaggle. O projeto terá como foco a criação de um pipeline ETL para carregar, limpar e estruturar os dados, utilizando Python, Pandas, Numpy e SQL (PostgreSQL). Além disso, o projeto será estruturado para possibilitar análises futuras, inclusive com integração ao Power BI.

## Ferramentas e Tecnologias
Python (Jupyter Notebook via VSCode)

* Pandas e Numpy para manipulação e transformação inicial dos dados

* Matplotlib, seaborn e plotly para graficos e visualizações exploratórias

* PostgreSQL para armazenamento, limpeza e estruturação dos dados em dois schemas:

* Schema 1: Base semi-tratada (dados carregados e parcialmente limpos)

* Schema 2: Base analítica (dados prontos para análise)

* Power BI para visualização e análise avançada (futuro)

## Etapas do Projeto
### Coleta e Carregamento dos Dados

* Importar os arquivos CSV da base do Olist usando Python e Pandas.

* Transformação Inicial (ETL)

* Realizar transformações básicas e junções necessárias em Python.

### Carga no Banco de Dados

* Criar os schemas no PostgreSQL.

* Carregar os dados semi-tratados no schema de base semi-tratada.

* Limpeza e Estruturação Avançada em SQL

* Aplicar regras de limpeza, normalização e criação de tabelas analíticas no schema analítico.

* Análise e Visualização

* Desenvolver queries analíticas em SQL.

* Exportar dados para Power BI para criação de dashboards (etapa futura).
