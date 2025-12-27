# Dashboard Hashtag Eletro (Power BI) — Vendas & Devoluções | 2020–2022
## 1) Problema de Negócio
A Hashtag Eletro precisava de uma visão consolidada e comparável da performance comercial e do impacto de devoluções, respondendo perguntas como:
-	Qual foi o faturamento, lucro, volume de vendas e margem por ano?
-	Como o resultado evoluiu mês a mês e como o ano atual se compara ao ano anterior?
-	Qual a participação de tipo de loja (Física vs Online) e de continentes no desempenho?
-	Qual o impacto financeiro das devoluções (quantidade, % e faturamento perdido) e quais marcas concentram mais devoluções?
## 2) Contexto
O projeto foi construído no Power BI com bases históricas de vendas (2020, 2021 e 2022) e devoluções, enriquecidas por tabelas de cadastro (produtos, lojas, localidades e clientes).
O dashboard foi organizado em duas abas principais:
-	Análise de Vendas
-	Devoluções
## 3) Premissas da análise
-	A moeda do relatório é USD ($).
-	O campo Ano Selecionado controla toda a navegação e os KPIs.
-	A comparação “vs. Ano Anterior” considera:
-	2021 vs 2020
-	2022 vs 2021
## 4) Estratégia / Construção do Dashboard
A solução foi desenhada para leitura executiva e exploração:
-	KPIs principais no topo: Faturamento, Lucro, Total de Vendas e Margem.
Gráfico de Faturamento Atual vs Ano Anterior (evolução mensal).
-	Composições e rankings:
-	Faturamento por categoria (ex.: celular, notebook, etc.)
-	Total de Vendas por Tipo de Loja (Física x Online)
-	Tabela por Continente com Faturamento, Lucro e Vendas
-	Aba de devoluções com:
-	Faturamento perdido, Qtd devoluções, % faturamento perdido, % devoluções
-	Evolução mensal, mapa por continente e ranking por marca
________________________________________
## 5) Principais resultados e insights
### 5.1 Análise de Vendas
#### 2020
-	Faturamento Total: $2.183.760
-	Lucro Total: $1.414.636
-	Total de Vendas: 2.630
-	Margem: 64,78%
-	Participação por tipo de loja: Física 83,27% | Online 16,73%
-	Destaque de faturamento por categoria: Celular (~$1,80 Mi)
#### 2021 (vs 2020)
-	Faturamento Total: $5.982.861 (+174%)
-	Lucro Total: $3.872.368 (+174%)
-	Total de Vendas: 36.230 (+1278%)
-	Margem: 64,72%
-	Tipo de loja: Física 83,03% | Online 16,97%
#### 2022 (vs 2021)
-	Faturamento Total: $7.059.459
-	Lucro Total: $4.555.624
-	Total de Vendas: 45.314
-	Margem: 64,53%
-	Tipo de loja: Física 83,01% | Online 16,99%
-	Categoria com maior faturamento no ranking: Notebook (~$4,05 Mi)
Leitura geral
-	Há forte crescimento de faturamento, lucro e volume entre 2020–2022, com margem estável (~64%–65%), indicando crescimento com manutenção de rentabilidade.
-	O mix por tipo de loja permanece consistente, com predominância do canal físico (~83%).
________________________________________
### 5.2 Devoluções
#### 2020
-	Faturamento perdido: $75.115,72
-	Devoluções: 86
-	% faturamento perdido: 3,44%
-	% devoluções: 3,27%
#### 2021
-	Faturamento perdido: $154.643,80
-	Devoluções: 770
-	% faturamento perdido: 2,58%
-	% devoluções: 2,13%
#### 2022
-	Faturamento perdido: $203.273,35
-	Devoluções: 972
-	% faturamento perdido: 2,88%
-	% devoluções: 2,15%
-	O ranking evidencia concentração de devoluções em marcas específicas, chegando a 10,20% no maior pico do gráfico.
Leitura geral
-	Apesar do aumento das devoluções em números absolutos, as taxas percentuais se mantêm relativamente controladas (≈2%–3%).
-	O detalhamento por marca permite direcionar investigações para possíveis causas (qualidade, logística reversa, pós-venda).
________________________________________
## 6) Entregáveis
-	Dashboard interativo no Power BI com:
-	KPIs executivos por ano
-	Comparativo anual e evolução mensal
-	Análises por continente, tipo de loja e categoria
-	Módulo específico para devoluções (impacto financeiro e ranking por marca)

#### Link para o dashboard completo: 
https://app.powerbi.com/view?r=eyJrIjoiYzY2MzcwMDItMDhmZC00MzkwLTg4YTYtNGY1MmMwYzcwMjcxIiwidCI6ImQzYTZmNGFiLWZjMGUtNDRiOS04MTA1LTdkZDI0MmYxY2Q4NyJ9
