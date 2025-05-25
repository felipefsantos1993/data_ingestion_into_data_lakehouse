# Data Lakehouse com Azure Data Factory, Databricks e Power BI

Criação de um pipeline de ingestão e transformação de dados em um Data Lake (ADLS Gen2), com processamento em Azure Databricks (PySpark), orquestração em Azure Data Factory e visualização em Power BI.

## Visão Geral

Este projeto demonstra um pipeline completo de engenharia de dados usando:
- Azure Data Lake Storage Gen2
- Databricks (PySpark + Delta Lake)
- Power BI
- Orquestração com Azure Data Factory

## Objetivos
- Armazenar dados brutos em um Data Lake
- Realizar ETL com Spark
- Servir dados limpos para visualização em Power BI

## Arquitetura

![alt text](image.png)

## Como Executar

1. Provisionar recursos no Azure usando Bicep ou Terraform.
2. Carregar dados de exemplo em `data/` para o Data Lake.
3. Rodar os notebooks Databricks.
4. Executar o pipeline Data Factory (`pipelines/`).
5. Abrir o dashboard em `powerbi/sales_dashboard.pbix`.

## Requisitos
- Teste