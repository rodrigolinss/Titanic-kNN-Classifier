# Titanic kNN Classifier

## Descrição

O projeto **Titanic kNN Classifier** tem como objetivo desenvolver um modelo preditivo para classificar a sobrevivência dos passageiros do Titanic, utilizando o algoritmo k-Nearest Neighbors (kNN). A análise foi realizada com a base de dados disponível no [Kaggle](https://www.kaggle.com/c/titanic).

## Metodologia

Para alcançar esse objetivo, foi realizada uma análise abrangente dos dados, que incluiu:

- **Exploração dos Dados**: Analisamos as características dos passageiros, identificando quais variáveis influenciavam a sobrevivência.
- **Pré-processamento**: Variáveis irrelevantes foram removidas e variáveis categóricas foram convertidas em variáveis dummy, representadas como 0 e 1. As escalas das variáveis numéricas foram equalizadas para garantir que o modelo pudesse funcionar adequadamente.
- **Definição de Target e Features**: Estabelecemos os alvos (sobrevivência) e as características (features) que alimentariam o modelo.
- **Treinamento do Modelo**: Utilizamos o algoritmo kNN para treinar o modelo com os dados processados, ajustando o hiperparâmetro k para encontrar o valor ideal.

  
Após a implementação, o modelo foi avaliado e alcançou uma acurácia de **79%** na previsão de sobrevivência dos passageiros.

## Resultados

Após otimizar os hiperparâmetros e identificar o melhor valor de k, o modelo kNN alcançou uma acurácia de **79%** na previsão de sobrevivência dos passageiros do Titanic. Esse resultado ressalta a importância do pré-processamento de dados e da seleção adequada de hiperparâmetros em tarefas de aprendizado de máquina.
