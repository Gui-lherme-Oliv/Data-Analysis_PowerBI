# Compilado de diferentes análises exploratórias de dados (EDA) realizadas utilizando Power BI
#### Autor: Guilherme Oliveira da Rocha Cunha

Estas análises foram apresentadas no curso **Microsoft Power BI Para Business Intelligence e Data Science** oferecido pelo portal de capacitação profissional Data Science Academy ([link](https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-business-intelligence-e-data-science)). Neste curso as análises são apresentadas em laboratórios práticos ou em mini-projetos. Todos os laboratórios e mini-projetos foram refeitos do zero por mim, construídos de acordo com as instruções do professor Daniel Mendes, instrutor responsável por este curso. Todos os conjuntos de dados (.csv ou .xlsx) e dashboards (.pbix) estão presentes neste repositório.

## Laboratório Prático 1 - Dashboard Analítico de Vendas Globais
Neste laboratório foram utilizados dados de vendas de uma empresa fictícia que comercializa produtos em todos os cantos do mundo.

O Dashboard deve responder às seguintes perguntas de negócio:
- Pergunta 1 - Qual o valor total vendido?
- Pergunta 2 - Quantas vendas foram realizadas por categoria de produto?
- Pergunta 3 - Quantas vendas foram realizadas por país considerando a prioridade de entrega?
- Pergunta 4 - Qual foi a média de desconto nas vendas por subcategoria de produto?
- Pergunta 5 - Quais países tiveram maior média de valor de venda? Demonstre em um mapa.

O Dashboard deve dar ao usuário a possibilidade de filtrar os dados por ano, por segmento e por país.

#### Dashboard gerado:
![Lab_1](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/cbcad32a-37dc-42c8-95a3-d433406d0ac1)

## Laboratório Prático 2 - Dashboard de Vendas, Custo, Margem de Lucro e KPI
Neste laboratório foram explorados os conceitos de **modelagem de dados, cardinalidade, recursos de limpeza de dados do Power BI e introdução ao DAX**. Foram utilizados dados de vendas fictícios obtidos em 4 diferentes tabelas: Clientes, Pedidos, Produtos e Vendas.

O Dashboard deve responder às seguintes perguntas de negócio:
- Pergunta 1 - Qual foi o total de valor venda considerando cada modo de envio dos pedidos? Use um gráfico de cascata.
- Pergunta 2 - Quais mercados tiveram o maior custo médio de envio dos produtos vendidos? Use um gráfico treemap.
- Pergunta 3 - A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. Mostre um indicador (KPI – Key Performance Indicator) com o valor médio de venda. A empresa ficou abaixo ou acima da meta no mês de Abril/2014?
- Pergunta 4 - Considere que o lucro é equivalente a: valor venda - custo envio. Qual categoria de produto apresentou maior lucro médio?
- Pergunta 5 - Qual foi o comportamento da margem de lucro ao longo do tempo? Considere a margem de lucro como o lucro dividido pelo valor venda.

