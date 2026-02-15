📊 Análise de Mercado — E-commerce Brasileiro (Olist)
📌 Contexto do Projeto

Este projeto analisa a estrutura competitiva do e-commerce brasileiro utilizando a base pública da Olist (2016–2018).

O objetivo foi aplicar técnicas de análise de dados e métricas econômicas para gerar insights estratégicos sobre:

Concentração de mercado

Geração de receita

Dinâmica temporal

Distribuição geográfica

Performance por categoria

🎯 Problema de Negócio

Como está estruturado o mercado de sellers dentro do marketplace?

O mercado é concentrado?

Existem players dominantes?

Quais categorias geram maior receita?

O mercado está crescendo ao longo do tempo?

🗂 Base de Dados

Fonte: Brazilian E-Commerce Public Dataset (Kaggle)
Período: 2016–2018

Bases utilizadas:

orders

order_items

products

customers

category_translation

Métrica principal construída:
Receita por pedido = price + freight

🔎 Etapas da Análise
1️⃣ Tratamento e Modelagem

Integração das bases via joins

Conversão de datas

Criação da variável de receita

Tradução e padronização de categorias

2️⃣ Análises Realizadas

Receita total por categoria

Receita mensal (série temporal)

Ticket médio

Participação de mercado por seller

Top 10 Market Share

Índice Herfindahl-Hirschman (HHI)

A análise foi conduzida com base em estatística descritiva e métricas formais de concentração de mercado, aplicando fundamentos matemáticos na modelagem e interpretação dos resultados.

📊 Principais Resultados
🏪 Estrutura de Mercado

Top 10 sellers concentram aproximadamente 12,8% da receita total.

HHI indica baixa concentração.

Mercado altamente fragmentado.

📌 Conclusão:
O marketplace apresenta ambiente competitivo, sem dominância estrutural de grandes players.

📦 Categorias

Categorias líderes concentram maior volume financeiro.

Indícios de maturidade em segmentos específicos.

📌 Insight:
Há espaço para estratégias de especialização em nichos menos saturados.

📈 Evolução Temporal

Crescimento estrutural ao longo do período analisado.

📌 Insight:
O mercado digital brasileiro apresentou expansão consistente entre 2016–2018.

🌎 Distribuição Geográfica

Receita concentrada principalmente na região Sudeste.

Estado de São Paulo com maior representatividade.

📌 Insight:
Possível oportunidade de expansão regional.

💳 Ticket Médio

Ticket intermediário.

Frete impacta significativamente a receita total.

📌 Insight:
Estratégias logísticas influenciam diretamente competitividade e margem.

🧠 Conclusão Geral

O mercado analisado apresenta:

Estrutura pulverizada

Baixa concentração entre sellers

Crescimento consistente

Forte concentração regional

Do ponto de vista analítico, o projeto demonstra:

Capacidade de integração e modelagem de dados

Aplicação de métricas quantitativas

Interpretação estratégica de indicadores

Uso de fundamentos matemáticos na análise de mercado

🛠 Tecnologias Utilizadas

Python

Pandas

Matplotlib

Estatística Descritiva

Métricas de Concentração (HHI, Market Share)

👤 Autor

Lucas Rezende
Analista de Dados e Performance
Bacharelado em Matemática (em andamento)