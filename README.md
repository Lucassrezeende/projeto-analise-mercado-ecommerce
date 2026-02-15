# Análise de Mercado — E-commerce Brasileiro (Olist)

Este projeto realiza uma análise exploratória do mercado brasileiro de e-commerce utilizando a base pública da Olist (2016–2018). O objetivo é avaliar a estrutura competitiva do marketplace por meio de métricas quantitativas, investigando concentração de mercado, geração de receita, dinâmica temporal e distribuição geográfica.

A base de dados foi integrada a partir dos arquivos orders, order_items, products, customers e category_translation. A principal métrica construída foi a receita por pedido (price + freight), utilizada como unidade central de análise.

O tratamento envolveu consolidação das bases via joins, conversão de variáveis temporais, padronização de categorias e modelagem da variável de receita. A análise incluiu estatística descritiva, cálculo de receita por categoria, evolução mensal da receita, ticket médio por pedido, participação de mercado por seller, participação acumulada dos 10 maiores vendedores e o Índice Herfindahl-Hirschman (HHI) para mensuração formal da concentração.

Os resultados indicam que os 10 maiores sellers concentram aproximadamente 12,8% da receita total, e o HHI confirma baixa concentração estrutural, caracterizando um mercado pulverizado e competitivo. Observa-se crescimento consistente ao longo do período analisado, além de forte concentração geográfica da receita na região Sudeste, especialmente no estado de São Paulo. O ticket médio revela impacto relevante do frete na composição da receita total, sugerindo que estratégias logísticas influenciam diretamente a competitividade.

O projeto demonstra capacidade de integração e modelagem de dados, aplicação de métricas quantitativas e interpretação estratégica de indicadores de mercado, com base analítica fundamentada em Matemática.

Tecnologias utilizadas: Python, Pandas, Matplotlib e métricas econômicas de concentração de mercado.

Autor:  
Lucas Rezende  
Analista de Dados e Performance  
Bacharelado em Matemática (em andamento)
