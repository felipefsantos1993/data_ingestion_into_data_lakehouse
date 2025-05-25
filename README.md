# Ingestão de Dados em Data Lakehouse
![alt text](cover.png)
## Visão Geral
Criação de um pipeline de ingestão e transformação de dados em um Data Lake (ADLS Gen2), com processamento em Azure Databricks (PySpark), orquestração em Azure Data Factory e visualização em Power BI.
## Objetivos
- Armazenar dados brutos em um Data Lake
- Realizar processso de ELT com Azure Data Factory e Apache Spark
- Servir dados limpos para visualização em Power BI
## Tecnologias
- Ingestão (Azure Data Factory)
- Armazenamento (Azure Data Lake Gen2 + Delta Lake)
- Processamento (Azure Databricks (PySpark/SQL))
- Catálogo de Metadados (Unity Catalog (opcional))
- Visualização (Power BI (Direct Lake, Import, DQ))
- Governança (Azure Purview (opcional))
- Monitoramento (Azure Monitor / Log Analytics)
## Arquitetura
Detalhes das Camadas Delta Lake:
- Bronze Layer: dados brutos como foram recebidos, sem transformação.
- Silver Layer: dados limpos, normalizados, com tipos corretos e joins aplicados.
- Gold Layer: dados prontos para consumo analítico e agregações.

![alt text](architecture.png)
#
#
#
# Data Ingestion into Data Lakehouse
![alt text](cover.png)
## Visão Geral
Criação de um pipeline de ingestão e transformação de dados em um Data Lake (ADLS Gen2), com processamento em Azure Databricks (PySpark), orquestração em Azure Data Factory e visualização em Power BI.
## Objetivos
- Armazenar dados brutos em um Data Lake
- Realizar processso de ELT com Azure Data Factory e Apache Spark
- Servir dados limpos para visualização em Power BI
## Tecnologias
- Ingestão (Azure Data Factory)
- Armazenamento (Azure Data Lake Gen2 + Delta Lake)
- Processamento (Azure Databricks (PySpark/SQL))
- Catálogo de Metadados (Unity Catalog (opcional))
- Visualização (Power BI (Direct Lake, Import, DQ))
- Governança (Azure Purview (opcional))
- Monitoramento (Azure Monitor / Log Analytics)
## Arquitetura
Detalhes das Camadas Delta Lake:
- Bronze Layer: dados brutos como foram recebidos, sem transformação.
- Silver Layer: dados limpos, normalizados, com tipos corretos e joins aplicados.
- Gold Layer: dados prontos para consumo analítico e agregações.

![alt text](architecture.png)