# 🤖 Uso de IA para Aprendizado de Modelagem Dimensional Aplicada ao Power BI

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Data%20Analytics-yellow?style=for-the-badge&logo=powerbi"/>
  <img src="https://img.shields.io/badge/NotebookLM-IA%20Aplicada-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data%20Modeling-Star%20Schema-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge"/>
</p>

<p align="center">
  <b>Projeto desenvolvido para explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa aplicada à modelagem dimensional no Power BI.</b>
</p>

<br>

# 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio prático da DIO com foco na utilização do NotebookLM para potencializar o aprendizado técnico utilizando Inteligência Artificial.

O objetivo principal foi construir um caderno temático estruturado sobre modelagem dimensional aplicada ao Power BI, explorando:

* organização do conhecimento;
* engenharia de prompts;
* revisão técnica;
* análise crítica de respostas geradas por IA;
* construção de material reutilizável para estudos futuros.

Os principais temas abordados foram:

* modelagem dimensional;
* tabela fato;
* tabela dimensão;
* relacionamentos;
* granularidade;
* cardinalidade;
* Star Schema;
* Snowflake Schema.

<br>

# 🎯 Objetivos de Estudo

✅ Compreender os fundamentos da modelagem dimensional

✅ Aprender a estruturar tabelas fato e dimensão

✅ Entender o funcionamento do Star Schema

✅ Aplicar boas práticas de modelagem no Power BI

✅ Utilizar IA como ferramenta de aprendizagem ativa

✅ Desenvolver habilidades de engenharia de prompts

<br>

# 📚 Curadoria de Fontes

As seguintes fontes foram utilizadas no NotebookLM para construção do caderno temático:

### 📘 Microsoft Learn — Star Schema e Power BI

https://learn.microsoft.com/pt-br/power-bi/guidance/star-schema

### 📘 Microsoft Learn — Relacionamentos no Power BI

https://learn.microsoft.com/pt-br/power-bi/transform-model/desktop-relationships-understand

### 📘 Ralph Kimball Group

https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/

### 📘 AWS — O que é Data Warehouse?

https://aws.amazon.com/what-is/data-warehouse/

### 📘 Google Cloud — Conceitos de Data Warehouse

https://cloud.google.com/learn/what-is-a-data-warehouse

<br>

# 🧠 Engenharia de Prompts

Durante os estudos foram realizados diversos testes de prompts para melhorar a qualidade das respostas geradas pela IA.

## 🔹 Prompt 1 — Introdução à Modelagem

```text id="azvphs"
Explique modelagem dimensional aplicada ao Power BI para iniciantes.
```

### 📌 Resultado

A IA apresentou conceitos básicos sobre modelagem dimensional e organização de dados analíticos.

### ⚠️ Problema Encontrado

A resposta ficou superficial e pouco técnica.

### ✅ Refinamento Aplicado

```text id="32d4hi"
Explique modelagem dimensional aplicada ao Power BI abordando:
- tabela fato;
- tabela dimensão;
- granularidade;
- cardinalidade;
- Star Schema;
- boas práticas.
```

### 🚀 Resultado Final

A resposta ficou mais detalhada, organizada e alinhada ao objetivo do estudo.

<br>

## 🔹 Prompt 2 — Tabela Fato e Dimensão

```text id="mgom91"
Explique a diferença entre tabela fato e dimensão utilizando um cenário de vendas.
```

### 📌 Resultado

A IA utilizou exemplos práticos envolvendo:

* clientes;
* produtos;
* vendas;
* calendário.

Isso facilitou significativamente o entendimento da estrutura dimensional.

<br>

## 🔹 Prompt 3 — Star Schema vs Snowflake

```text id="mb2d5v"
Compare Star Schema e Snowflake Schema considerando:
- performance;
- simplicidade;
- normalização;
- uso no Power BI.
```

### ⚠️ Dificuldade Encontrada

A resposta apresentou excesso de teoria e poucos exemplos reais.

### ✅ Solução Aplicada

Solicitação de:

* exemplos práticos;
* cenários empresariais;
* representações visuais.

<br>

## 🔹 Prompt 4 — Erros Comuns em Modelagem

```text id="2q4esg"
Liste erros comuns em modelagem dimensional que prejudicam dashboards no Power BI.
```

### 📌 Resultado

Foram identificados problemas como:

* relacionamento muitos-para-muitos;
* granularidade incorreta;
* ausência de tabela calendário;
* duplicidade em dimensões.

<br>

# ⚠️ Troubleshooting e “Cicatrizes”

## 🔸 Respostas Muito Genéricas

Em alguns momentos a IA apresentou respostas superficiais.

### ✅ Solução

Refinamento dos prompts utilizando:

* contexto específico;
* objetivos claros;
* tópicos obrigatórios.

<br>

## 🔸 Excesso de Conceitos Acadêmicos

Algumas respostas ficaram excessivamente teóricas.

### ✅ Solução

Solicitação de:

* exemplos reais;
* aplicações práticas;
* cenários corporativos.

<br>

## 🔸 Problemas com Relacionamentos

A IA confundiu conceitos relacionados à cardinalidade e direção de filtro.

### ✅ Solução

Validação das informações utilizando documentação oficial da Microsoft.

<br>

# 📘 Miniguia de Estudo

# ⭐ Modelagem Dimensional

A modelagem dimensional é uma técnica utilizada em ambientes analíticos para organizar dados de forma otimizada para consultas e dashboards.

### 🎯 Objetivos

✅ Melhorar performance

✅ Simplificar análises

✅ Facilitar interpretação dos dados

✅ Otimizar dashboards no Power BI

<br>

# 📊 Tabela Fato

A tabela fato armazena:

* métricas;
* indicadores;
* eventos de negócio.

### 📌 Exemplos

* vendas;
* faturamento;
* lucro;
* quantidade vendida.

### 📌 Características

✅ Grande volume de dados

✅ Dados quantitativos

✅ Chaves estrangeiras

<br>

# 🧩 Tabela Dimensão

A tabela dimensão fornece contexto para análise dos dados.

### 📌 Exemplos

* cliente;
* produto;
* vendedor;
* calendário.

### 📌 Características

✅ Dados descritivos

✅ Filtros analíticos

✅ Categorização

<br>

# ⭐ Star Schema

O Star Schema é um modelo dimensional onde:

* a tabela fato fica no centro;
* as dimensões ficam ao redor.

### 🚀 Vantagens

✅ Melhor performance

✅ Simplicidade

✅ Facilidade de manutenção

✅ Melhor leitura analítica

<br>

# 🔗 Relacionamentos

Os relacionamentos conectam tabelas fato e dimensão.

### 📌 Conceitos Importantes

* cardinalidade;
* direção de filtro;
* integridade referencial;
* granularidade.

<br>

# 📖 Glossário

| Conceito         | Definição                            |
| ---------------- | ------------------------------------ |
| Tabela Fato      | Armazena métricas e eventos          |
| Tabela Dimensão  | Armazena contexto descritivo         |
| Cardinalidade    | Tipo de relacionamento entre tabelas |
| Granularidade    | Nível de detalhe dos dados           |
| Star Schema      | Modelo dimensional centralizado      |
| Snowflake Schema | Modelo dimensional normalizado       |
| OLAP             | Processamento analítico              |
| ETL              | Extração, transformação e carga      |
| Data Warehouse   | Repositório analítico de dados       |

<br>

# 🧠 Prompts Reutilizáveis

## 📌 Revisão Técnica

```text id="t2wkz0"
Explique este conceito como se estivesse ensinando um iniciante em Power BI.
```

## 📌 Comparação de Modelos

```text id="8ghvwl"
Compare Star Schema e Snowflake Schema utilizando exemplos práticos.
```

## 📌 Simulação de Cenários

```text id="mq96fr"
Crie um exemplo de modelagem dimensional para uma empresa de vendas.
```

## 📌 Identificação de Problemas

```text id="0bjlwm"
Liste erros comuns de modelagem dimensional no Power BI.
```

<br>

# 🚀 Tecnologias Utilizadas

🟡 Power BI

🔵 NotebookLM

⚫ GitHub

🟢 Inteligência Artificial Generativa

<br>

# 👨‍💻 Autor
## Risoaldo Almeida
💼 Analista de Dados | Power BI | Business Intelligence | IA Aplicada

🔗 LinkedIn:
https://www.linkedin.com/in/risoaldoalmeida/

</p>
