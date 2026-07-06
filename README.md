# Projeto-DataBricks_01
# Pipeline de Engenharia de Dados com Databricks

## 📌 Sobre o Projeto

Este projeto demonstra a construção de um pipeline moderno de Engenharia de Dados utilizando a plataforma Databricks, seguindo as melhores práticas de processamento distribuído e arquitetura em camadas (Medallion Architecture).

O pipeline foi desenvolvido para processar dados provenientes de diferentes formatos, como **JSON**, **CSV** e **Parquet**, consolidando essas informações em um fluxo único de processamento.

Durante a execução do pipeline, os dados passam pelas etapas de ingestão, limpeza, padronização, transformação e enriquecimento, garantindo maior qualidade, consistência e confiabilidade antes de serem disponibilizados para análise.

Como estratégia de armazenamento e organização dos dados, foi utilizada a arquitetura **Bronze, Silver e Gold**, com todas as tabelas implementadas no formato **Delta Lake**, proporcionando recursos como versionamento, transações ACID, otimização de consultas e maior confiabilidade no processamento.

Ao final do projeto, todo o fluxo é automatizado por meio da criação de um **Job** na plataforma **Databricks**, permitindo a execução orquestrada do pipeline de ponta a ponta.

---

## 🎯 Objetivos

* Construir um pipeline completo de Engenharia de Dados.
* Realizar a ingestão de dados em múltiplos formatos (JSON, CSV e Parquet).
* Consolidar diferentes fontes de dados em um único fluxo de processamento.
* Aplicar processos de limpeza, padronização e enriquecimento dos dados.
* Implementar a arquitetura **Medallion (Bronze, Silver e Gold)**.
* Armazenar os dados utilizando **Delta Lake**.
* Automatizar a execução do pipeline utilizando **Databricks Jobs**.
* Disponibilizar uma camada de dados pronta para consumo analítico e criação de dashboards.

---

## 🏗️ Arquitetura do Pipeline

```text
Arquivos (JSON | CSV | Parquet)
              │
              ▼
        Camada Bronze
(Ingestão dos dados brutos)
              │
              ▼
        Camada Silver
(Limpeza, padronização,
tratamento e enriquecimento)
              │
              ▼
         Camada Gold
(Dados consolidados e
prontos para análise)
              │
              ▼
      Databricks Jobs
(Orquestração e automação)
```

---

## 🛠️ Tecnologias Utilizadas

* Databricks
* Apache Spark (PySpark)
* Delta Lake
* Databricks Workflows (Jobs)
* JSON
* CSV
* Parquet

---

## 📊 Resultado

Ao final da execução do pipeline, os dados encontram-se organizados na camada **Gold**, prontos para consumo por ferramentas de Business Intelligence, dashboards, análises exploratórias e modelos analíticos, garantindo um fluxo automatizado, escalável e confiável de processamento de dados.

---

## 🚀 Principais Competências Demonstradas

* Engenharia de Dados
* Apache Spark (PySpark)
* ETL / ELT
* Delta Lake
* Medallion Architecture
* Databricks
* Data Lake
* Data Processing
* Data Quality
* Data Transformation
* Data Pipeline Automation


