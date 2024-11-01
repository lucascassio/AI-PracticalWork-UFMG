# AI-PracticalWork-UFMG

Este repositório contém o código e a documentação do Trabalho Prático de IA, desenvolvido com o objetivo de explorar e implementar algoritmos de Aprendizado Supervisionado e Aprendizado por Reforço em um conjunto de problemas do domínio da aviação e controle de sistemas dinâmicos. O trabalho está dividido em três partes principais: Regressão, Classificação e Reforço.

## Descrição do Projeto

O objetivo deste trabalho é desenvolver modelos de aprendizado supervisionado e por reforço para resolver problemas relacionados ao ajuste dos ailerons de uma aeronave e ao controle do pêndulo invertido (CartPole). As abordagens incluem análise exploratória, modelagem de regressão e classificação, assim como a implementação de Q-Learning para o controle dinâmico.

## Tarefas

### 1. Aprendizado Supervisionado - Regressão

Modelagem de regressão para prever a deflexão dos ailerons da aeronave e responder às questões:

- Análise exploratória e descrição de variáveis (correlação, `pair_plots`).
- Modelos de regressão desenvolvidos:
  - Regressão Linear
  - Ridge (alpha: {0.2, 1, 5})
  - XGBoost
- Comparação de modelos com as métricas de erro (MAE, MSE, RMSE).
- Seleção de variáveis e análise dos coeficientes na Regressão Linear.

### 2. Aprendizado Supervisionado - Classificação

Desenvolvimento de modelos de classificação para a discretização das deflexões dos ailerons, abordando:

- Modelos de classificação e seus hiperparâmetros:
  - Regressão Logística
  - Naive Bayes (Gaussian)
  - Árvores de Decisão 
  - K-Nearest Neighbors 
  - XGBoost
- Comparação de odds-ratio e análise de suposições no modelo Naive Bayes.
- Análise de métricas de avaliação para comparação dos modelos.

### 3. Aprendizado por Reforço

Implementação de Q-Learning para o controle do CartPole, abordando:

- Ajuste dos parâmetros `alpha`, `gamma` e `epsilon`.
- Experimento de perturbação e retorno à estabilidade.
- Descrição e análise de uma topologia para Deep Reinforcement Learning que possa resolver o problema do CartPole.

## Referências

- [Ailerons Dataset](https://sci2s.ugr.es/keel/category.php?cat=reg&order=insR#sub2)
- [Cart Pole Environment](https://www.gymlibrary.dev/environments/classic_control/cart_pole/)
