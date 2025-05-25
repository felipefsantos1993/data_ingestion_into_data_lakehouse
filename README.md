# Data Lakehouse with Azure Data Factory, Databricks and Power BI

## Visão Geral

Este projeto demonstra um pipeline completo de engenharia de dados usando:
- Azure Data Lake Storage Gen2
- Databricks (PySpark + Delta Lake)
- Power BI
- Orquestração com Apache Airflow
- SQL Server para staging

## Objetivos
- Armazenar dados brutos em um Data Lake
- Realizar ETL com Spark
- Servir dados limpos para visualização em Power BI

## Arquitetura

![arquitetura](docs/arquitetura.png)

## Como Executar

1. Provisionar recursos no Azure usando Bicep ou Terraform.
2. Carregar dados de exemplo em `data/` para o Data Lake.
3. Rodar os notebooks Databricks.
4. Executar o pipeline Airflow (`pipelines/airflow_dag.py`).
5. Abrir o dashboard em `powerbi/sales_dashboard.pbix`.

## Requisitos

```bash
pip install -r requirements.txt

