![alt text](cover.png)

## Visão Geral
Criação de um pipeline de ingestão e transformação de dados em um Data Lake (ADLS Gen2), com processamento em Databricks (PySpark), orquestração em Azure Data Factory e visualização em Power BI.
## Objetivos
- Armazenar dados brutos em um Data Lake.
- Realizar processso de ELT com Azure Data Factory e Apache Spark.
- Servir dados limpos para visualização em Power BI.
## Tecnologias
- Ingestão (Azure Data Factory)
- Armazenamento (Azure Data Lake Gen2 + Delta Lake)
- Processamento (Databricks (PySpark/SQL))
- Catálogo de Metadados (Unity Catalog (opcional))
- Visualização (Power BI (DirectQuery))
- Governança (Azure Purview (opcional))
- Monitoramento (Azure Monitor/Log Analytics)
## Arquitetura
Modelagem de Dados OLTP:
![alt text](OLTP.png)

Modelagem de Dados do Datawarehouse:
![alt text](DW.png)

Detalhes das Camadas Delta Lake:
- Camada Bronze: dados brutos como foram recebidos, sem transformação.
- Camada Prata: dados limpos, normalizados, com tipos corretos e joins aplicados.
- Camada Ouro: dados prontos para consumo analítico e agregações.
![alt text](<architecture.png>)

## Documentações Utilizadas
https://learn.microsoft.com/en-us/azure/data-factory

https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-databricks-notebook
#
#
#
![alt text](cover.png)

## Overview
Creation of a data ingestion and transformation pipeline in a Data Lake (ADLS Gen2), with processing in Databricks (PySpark), orchestration in Azure Data Factory and visualization in Power BI.
## Objectives
- Storaging Raw Data in a Data Lake.
- Performing ELT processes with Azure Data Factory and Apache Spark.
- Serving clean data for visualization in Power BI.
## Technologies
- Ingestion (Azure Data Factory)
- Storaging (Azure Data Lake Gen2 + Delta Lake)
- Processing (Databricks (PySpark/SQL))
- Metadada Catalog (Unity Catalog (optional))
- Visualization (Power BI (DirectQuery))
- Governance (Azure Purview (optional))
- Monitoring (Azure Monitor/Log Analytics)
## Architecture
OLTP Data Modeling:
![alt text](OLTP.png)

Datawarehouse Data Modeling:
![alt text](DW.png)

Delta Lake Layer Details:
- Bronze Layer: raw data as received, without transformation.
- Silver Layer: clean, normalized data, with correct types and joins applied.
- Gold Layer: data ready for analytical consumption and aggregations.
![alt text](<architecture.png>)

## Documentation Used
https://learn.microsoft.com/en-us/azure/data-factory

https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-databricks-notebook