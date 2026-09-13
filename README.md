# Pipeline de Engenharia de Dados — Arquitetura Medalhão

Projeto de Engenharia de Dados desenvolvido no Databricks para processar dados de clientes, produtos e vendas utilizando a **Arquitetura Medalhão**.

## Arquivos de origem

O projeto utiliza seis arquivos CSV:

- `cust_info.csv`
- `prd_info.csv`
- `sales_datails.csv`
- `CUST_AZ12.csv`
- `LOC_A101.csv`
- `PX_CAT_G1V2.csv`

## Arquitetura

O processamento está organizado em três camadas:

- **Bronze:** ingestão dos dados brutos, preservando as informações originais.
- **Silver:** limpeza, padronização, validação e integração dos dados.
- **Gold:** criação de dados consolidados e preparados para análises e relatórios.

## Tecnologias utilizadas

- Databricks
- Apache Spark
- PySpark
- SQL e Spark SQL
- Delta Lake
- Unity Catalog

## Objetivo
Construir um pipeline de dados organizado, escalável e confiável, aplicando boas práticas de ingestão, transformação, qualidade e disponibilização de dados.
