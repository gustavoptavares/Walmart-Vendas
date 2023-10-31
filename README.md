# # Entendendo as vendas das lojas do Walmart

## Visão Geral

Neste projeto, vamos analisar os dados disponíveis, no conjunto de dados de vendas para 45 lojas do Walmart.

Você pode conferir o dataset e o projeto na íntegra clicando abaixo:

Link dataset: https://www.kaggle.com/datasets/yasserh/walmart-dataset

Link do código do projeto: https://github.com/gustavoptavares/Walmart-Vendas/blob/main/Walmart_Vendas.ipynb

## Problema e Solução

Vamos analisar os dados O conjunto de dados de vendas do Walmart, para entender o funcionamento do estoque e das vendas. Com um conjunto de dados consiste em dados históricos de vendas de 45 lojas do Walmart localizadas em diferentes regiões, vamos entender, no detalhe, aspectos relacionados a demanda de vendas, como:

• Enteder o conjunto de dados com todas as variáveis.

• Previsão das vendas com uma variável e multiplas variáveis. 

## O Processo

O primeiro passo do projeto foi adquirir os dados. Utilizamos os dados do portal Kaagle, carregando-o no Google Colab, para a exploração e análise dos dados utilizando a linguagem de programação Python e suas bibliotecas, como Pandas, Matplotlib e Scikit-Learn. Foi feita análise exploratória, visualização dos dados, e foi aplicado o modelo preditivo de regressão, utilizando o algoritmo de regressão linear para previsão das vendas.

## Resultados

O modelo de regressão linear para prever as vendas (Weekly_Sales) com uma variável alcançou os seguintes resultados:

Erro Quadrático Médio (MSE): 3.20 × 10¹¹

Coeficiente de Determinação (R²): 0.0055

O modelo de regressão linear para prever as vendas com mais variáveis alcançou os seguintes resultados:

Erro Quadrático Médio (MSE): 2.74 × 10¹¹

Coeficiente de Determinação (R²): 0.1481

Comparação dos modelos

O MSE diminuiu, indicando um melhor ajuste do modelo aos dados.

O valor R²aumentou consideravelmente de 0.0055 para 0.1481, o que sugere que o modelo de várias variáveis é mais eficaz em prever Weekly_Sales do que o modelo de uma variável.

## Conclusões

Modelo de Uma Variável vs. Modelo de Várias Variáveis: O modelo de regressão linear com várias variáveis tem um desempenho significativamente melhor do que o modelo de uma variável. Isso indica a importância de considerar múltiplos fatores ao prever as vendas semanais.

Variáveis Mais Significativas: A identificação da loja (Store) e o Índice de Preços ao Consumidor (CPI) são as variáveis mais significativas na previsão das vendas semanais, seguidas pela taxa de desemprego (Unemployment).
