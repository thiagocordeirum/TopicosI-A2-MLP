# TopicosI-A2-MLPs

Repositório da disciplina de Tópicos I - Atividade 2 - MLP

## 👥 Autores

| [<img src="https://github.com/thiagocordeirum.png?size=100" width=100><br><sub>Thiago Cordeiro</sub>](https://github.com/thiagocordeirum) | [<img src="https://github.com/Jaum36.png?size=100" width=100><br><sub>João Victor</sub>](https://github.com/Jaum36) | [<img src="https://github.com/cpc231341.png?size=100" width=100><br><sub>Cristiano Penihce Ceccon</sub>](https://github.com/cpc231341) |
|:---:|:---:|:---:|


## Descrição do Projeto

Este repositório contém a solução da Atividade 2 da disciplina de Tópicos I, focada na construção e avaliação de redes neurais Multilayer Perceptron (MLP) para classificação de renda utilizando o UCI Adult Income Dataset.

### Bibliotecas Utilizadas

- **pandas**: Manipulação e análise de dados.
- **numpy**: Operações matemáticas e arrays.
- **matplotlib.pyplot**: Visualização de gráficos.
- **torch, torch.nn, torch.optim**: Construção e treinamento das redes neurais.
- **TensorDataset, DataLoader**: Manipulação eficiente dos dados no PyTorch.
- **sklearn.model_selection**: Divisão dos dados em treino e teste.
- **sklearn.preprocessing**: Normalização dos dados.
- **sklearn.metrics**: Cálculo das métricas de avaliação.
- **prettytable**: Criação de tabelas comparativas.

### Metodologia

1. Pré-processamento dos dados: limpeza, padronização e codificação dos atributos categóricos.
2. Divisão do dataset em treino e teste, com balanceamento das classes.
3. Implementação de três arquiteturas de MLP em PyTorch: modelo simples, modelo com duas camadas ocultas e modelo customizado (CJT).
4. Treinamento dos modelos e análise da evolução da função de perda.
5. Avaliação dos modelos com métricas como acurácia balanceada, precisão, recall, F1-score e matriz de confusão.
6. Comparação dos resultados para identificar o modelo mais eficiente e aderente ao problema.
