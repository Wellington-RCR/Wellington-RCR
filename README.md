# Olá, eu sou Wellington Richard 👋

### Analytics Engineer | em dados desde 2016 · Curitiba / São José dos Pinhais — PR

Profissional de dados com experiência em ArcelorMittal, BRF e Unidas, migrando de operações e BI para **Analytics Engineering**. Foco em construir a estrutura que permite análises confiáveis — modelagem, qualidade de dados e pipelines reproduzíveis.

---

## 🛠️ Stack

![dbt](https://img.shields.io/badge/dbt-Intermediário-orange?style=flat-square&logo=dbt&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Intermediário-blue?style=flat-square&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-Intermediário-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-Básico-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-Básico-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-Básico-F05032?style=flat-square&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Intermediário-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![SAP](https://img.shields.io/badge/SAP-Experiente-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-Experiente-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Avançado-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

---

## 🚀 Projetos

### 🚕 [NYC Taxi Analytics — dbt + BigQuery + Airflow](https://github.com/Wellington-RCR/portfolio-nyc-taxi-dbt)
Pipeline de Analytics Engineering completo em cloud data warehouse, com orquestração — 84,6 milhões de corridas de táxi de Nova York.

- Arquitetura **staging → intermediate → marts**, modelagem **Star Schema** (Kimball) com `fct_trips` e 4 dimensões
- Modelo **incremental** (estratégia `merge`) com chave sintética e particionamento
- **12 testes automatizados** de qualidade de dados, com 5 investigações documentadas de causa raiz (tarifas inválidas, duplicidade geográfica, códigos não documentados, timestamps corrompidos)
- Orquestração via **Apache Airflow** (Astro CLI + Docker)
- Stack: `dbt Core 1.8` · `Google BigQuery` · `Apache Airflow` · `Docker` · `SQL` · `Git`

### 📦 [dbt Olist Analytics](https://github.com/Wellington-RCR/dbt-olist-analytics)
Pipeline de Analytics Engineering completo com dados reais de e-commerce brasileiro (Olist/Kaggle).

- Arquitetura **Medallion** — Bronze → Silver → Gold
- **5 modelos de staging** com limpeza, cast de tipos e padronização
- Modelagem **Star Schema** com `fct_orders` e modelo de relatório `rpt_sales_by_month`
- Testes automatizados de qualidade de dados (`not_null`, `unique`, `accepted_values`)
- Documentação com **lineage graph** gerado automaticamente pelo dbt docs
- Stack: `dbt Core 1.11` · `DuckDB` · `SQL` · `Git`

---

## 📚 Atualmente estudando

- Aprofundamento em **SQL** — CTEs avançadas, window functions, otimização de queries
- Data Warehousing — modelagem dimensional aplicada (Kimball)

---

## 🏆 Certificações e formações concluídas

- **dbt Core + BigQuery** — formação completa em pipeline de Analytics Engineering (Udemy)
- Version Control – Meta (mar/2026)
- Versionamento de Código GitHub – DNC (mar/2026)
- SQL para Análise de Dados – DNC
- Análise de Dados com Python – DNC
- Limpeza e Organização de Dados com Python – DNC
- Análise de Dados com Excel e Power BI – DNC

---

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Wellington%20Rodrigues-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wellington-rodrigues-4984b353)
[![Email](https://img.shields.io/badge/Email-wellington--rod%40hotmail.com-D14836?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:wellington-rod@hotmail.com)

---

<sub>⚡ "Não basta o dado estar certo — é preciso provar que ele está certo."</sub>
