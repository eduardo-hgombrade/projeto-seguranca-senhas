# 🔐 Senhas em Risco: Big Data e Segurança Digital

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red.svg)
![Parquet](https://img.shields.io/badge/Data-Apache%20Parquet-orange.svg)

## 📖 Sobre o Projeto
O **Senhas em Risco** é uma aplicação de análise de Big Data voltada para a conscientização em Segurança da Informação. O projeto processa e analisa grandes volumes de dados de vazamentos reais (Data Breaches) para identificar vulnerabilidades matemáticas e comportamentais na criação de senhas.

O produto final é um **Dashboard Interativo** que traduz métricas complexas de criptografia (Entropia) e Engenharia Social em visualizações acessíveis, demonstrando o tempo estimado para quebra de credenciais via ataques de força bruta.

> **Importante:** Este projeto possui finalidade exclusivamente acadêmica e educacional (Extensão Universitária).

---

## 🚀 Arquitetura e Tecnologias
O sistema foi desenvolvido sob uma arquitetura de dados robusta:
* **Pipeline ETL:** Extração, limpeza e enriquecimento de dados utilizando `Pandas` e `NumPy`.
* **Motor NLP/Regex:** Algoritmos em Python para identificar padrões humanos (Engenharia Social) em senhas.
* **Processamento Otimizado:** Transição de CSV para o formato colunar **Apache Parquet** (`PyArrow`), garantindo alta velocidade de leitura (I/O).
* **Data Visualization:** Geração de gráficos interativos e *Data Storytelling* com `Plotly`.
* **Interface Web:** *Deploy* do Dashboard interativo construído em `Streamlit`.

---

## 🎯 Funcionalidades do Dashboard
* 🧮 **Calculadora de Entropia:** Demonstração matemática da força de uma senha.
* ⏱️ **Estimativa de Quebra:** Tempo necessário para invasão via *Brute Force*.
* 📊 **Análise Comportamental:** Gráficos interativos revelando os padrões de senhas mais usados no Brasil e no mundo.
* 📜 **Timeline de Vazamentos:** Histórico visual dos maiores incidentes de segurança cibernética (2004-2024).

---

## 👥 Equipe de Desenvolvimento
* **Eduardo Gombrade** — Análise e Desenvolvimento (Pipeline ETL e Backend)
* **João Vendito** — Dashboard e Visualizações (Streamlit / Plotly)
* **Leandro Schiavo** — Documentação (Pesquisa Acadêmica e Roteiro)

---
*Projeto desenvolvido para a disciplina de Tópicos de Big Data em Python (UniMetrocamp Wyden - 2026).*
