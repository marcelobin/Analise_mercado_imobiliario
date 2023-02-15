# **Projeto de análise imobiliária**

Este é um projeto de análise de imóveis que utiliza algoritmos de regressão para prever os preços de imóveis em diferentes regiões. O objetivo deste projeto é encontrar o modelo de regressão que melhor se ajusta ao problema, e utilizar esse modelo para prever os preços de novos imóveis.

## **Dados**
Os dados utilizados neste projeto foram coletados a partir de fontes públicas e contêm informações sobre o preço final, valores de condomínio, tamanho em m² do imóvel, número de quartos, número de banheiros, número de suítes, número de vagas de estacionamento, classificação binária para a presença de elevador, classificação binária para o imóvel estar mobiliado, classificação binária para a presença de piscina e classificação binária para o imóvel ser novo ou usado.

## **Modelos**
Foram testados três modelos de regressão: Regressão Linear, Árvore de Decisão e Floresta Aleatória. Para avaliar o desempenho desses modelos, foram utilizadas métricas como Mean Squared Error (MSE) e Mean Absolute Error (MAE).

## **Resultados**
Os resultados mostraram que, após a remoção das variáveis Latitude e Longitude do conjunto de teste, todos os modelos tiveram um desempenho significativamente melhor. O modelo de Regressão Linear teve o melhor desempenho, com um score perfeito de 1.0 nas métricas MSE e MAE.

## **Conclusão**
Os resultados sugerem que a remoção de variáveis irrelevantes pode ter um impacto significativo no desempenho do modelo de regressão. No entanto, é importante notar que esses resultados são específicos para este conjunto de dados e que os resultados podem ser diferentes para outros conjuntos de dados.
