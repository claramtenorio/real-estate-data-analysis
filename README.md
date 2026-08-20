# real-estate-data-analysis

Análise exploratória de dados e modelagem estatística (Regressão Linear) de preços de imóveis utilizando Python, Pandas e Scikit-Learn.

## O Projeto
Este projeto tem como objetivo analisar o comportamento de preços no mercado imobiliário com técnicas de estatística descritiva, testes de hipótese e modelagem preditiva. O dataset utilizado foi um de preços de casas do Kaggle.

## Problema de Negócio
O foco desta análise é responder a perguntas relacionadas a precificação dos imóveis, como:
* Quais são os principais fatores que influenciam o preço de venda de um imóvel?
* Como a qualidade de um imóvel impacta (estatisticamente) o seu valor de mercado?
* É possível construir um modelo preditivo confiável com base apenas no tamanho do imóvel?

## Principais Insights
* A área do imóvel (GrLivArea) possui uma correlação forte (aprox. 0.74) com o preço de venda, mostrando-se ser o principal fator na precificação.
* **Testes de Hipótese:** O teste t de Student aplicado em diferentes faixas de qualidade (baixa/média e alta) comprovou que imóveis de qualidade alta têm preços estatisticamente maiores (com p-valor menor que 0.05), rejeitando a hipótese nula de que essa diferença ocorre ao acaso.
* **Modelo Preditivo (OLS):** O modelo de Regressão Linear simples (utilizando o tamanho do imóvel) atingiu um coeficiente de determinação ($R^2$) de 0.5552, indicando que mais de 55% da variação dos preços é explicada unicamente pela área útil.

## Tecnologias / Ferramentas
* Python (principal linguagem)
* Pandas & NumPy (transformação e análise exploratória de dados)
* SciPy & Statsmodels (estatística descritiva, intervalos de confiança e testes de hipótese)
* Scikit-Learn (modelo de Regressão Linear / OLS)
* Power BI & Matplotlib (visualização de dados)
