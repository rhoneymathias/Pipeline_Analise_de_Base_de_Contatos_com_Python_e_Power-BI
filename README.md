# 📊 Pipeline de Análise de Dados de uma Base de Contatos com Python e Power BI
![Python](https://img.shields.io/badge/Python-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?logo=powerbi)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

## 📖 Sobre o Projeto

Este projeto apresenta um pipeline completo de análise de dados desenvolvido em **Python (Pandas)** e **Power BI**, utilizando uma base de contatos exportada do **Google Contatos**.

O objetivo foi transformar dados brutos em informações estratégicas por meio de etapas de limpeza, padronização, análise exploratória e visualização de dados.

> **⚠️ Observação:** A base de dados original **não está disponível neste repositório**, pois contém informações pessoais. O projeto foi publicado apenas com o código-fonte e a documentação, preservando a privacidade dos dados.

---

# 🎯 Problema de Negócio

A base de contatos apresentava inconsistências de preenchimento, diferentes grafias para os mesmos bairros e ausência de padronização, dificultando análises e segmentações geográficas.

O desafio consistiu em organizar, limpar e analisar essa base para compreender sua distribuição geográfica, avaliar a qualidade dos dados e gerar informações que apoiassem o planejamento estratégico e a tomada de decisão.

---

# 🎯 Objetivo

Desenvolver um pipeline de análise de dados utilizando **Python (Pandas)** e **Power BI** para preparar, analisar e visualizar uma base de contatos, transformando dados brutos em informações estratégicas.

---

# 📌 Objetivos Específicos

- Importar e compreender a estrutura da base de dados;
- Realizar a limpeza e padronização dos registros;
- Identificar inconsistências e duplicidades;
- Criar novas variáveis para enriquecer a análise;
- Realizar Análise Exploratória dos Dados (EDA);
- Construir indicadores de desempenho (KPIs);
- Desenvolver dashboards interativos no Power BI;
- Gerar insights que apoiem o planejamento estratégico.

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Power BI Desktop
- Excel

---

# 🔄 Pipeline do Projeto

O projeto foi desenvolvido seguindo as seguintes etapas:

1. Importação da base exportada do Google Contatos;
2. Limpeza e tratamento dos dados;
3. Padronização dos bairros;
4. Criação da variável **bairro_padronizado**;
5. Agrupamento dos bairros da região Nova Poá (**bairro_agrupado**);
6. Criação da variável **zona** (Parte de cima / Parte de baixo);
7. Análise Exploratória dos Dados (EDA);
8. Construção de indicadores (KPIs);
9. Desenvolvimento dos dashboards no Power BI.

---

# 📈 Fluxo do Projeto

- Recebimento de uma base com aproximadamente **3.600 contatos**;
- Tratamento e limpeza dos dados utilizando **Python (Pandas)**;
- Extração e padronização dos bairros;
- Criação de atributos derivados (`bairro_padronizado`, `bairro_agrupado` e `zona`);
- Validação dos dados e correção de inconsistências;
- Construção de dashboards interativos no **Power BI**.

---

# 📊 Principais Resultados

- Base analisada com **3.629 contatos**;
- **34 bairros** identificados e padronizados;
- Segmentação dos contatos entre **Parte de Cima** e **Parte de Baixo** da cidade;
- Construção de dashboards para análise geográfica da base;
- Organização dos dados para facilitar consultas e apoiar a tomada de decisão.

---

# 📊 Dashboards

O projeto contempla dashboards desenvolvidos no **Power BI** para facilitar a análise e interpretação dos dados.

Os painéis apresentam indicadores como:

- Total de contatos;
- Quantidade de bairros identificados;
- Distribuição dos contatos por região da cidade;
- Distribuição dos contatos por bairro;
- Indicadores específicos da região Nova Poá.

## Dashboard 1 – Visão Geral

<img width="1161" height="681" alt="image" src="https://github.com/user-attachments/assets/23d03fc4-f503-4ce5-93a5-267680505215" />


## Dashboard 2 – Distribuição por Região

<img width="1160" height="654" alt="image" src="https://github.com/user-attachments/assets/6bc6b377-1409-4fd2-8538-1c684132a018" />

---

# 🔒 Base de Dados

A base de dados original **não foi disponibilizada** neste repositório por conter informações pessoais.

Todo o pipeline de tratamento, análise e construção dos dashboards pode ser compreendido por meio do notebook e da documentação do projeto.

---

# 🚀 Competências Demonstradas

- Limpeza e transformação de dados;
- Padronização de registros;
- Engenharia de atributos;
- Análise Exploratória de Dados (EDA);
- Construção de indicadores (KPIs);
- Desenvolvimento de dashboards no Power BI;
- Visualização de dados;
- Comunicação de resultados.
