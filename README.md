# Atividade 2: Redes Neurais MLP para Classificação de Renda

Este repositório contém a implementação da **Atividade 2 da disciplina Tópicos para Computação 1 (2026.1)**, ministrada pela **Profa. Dra. Elloá B. Guedes** na **Escola Superior de Tecnologia (EST/UEA)**.

---

## 📁 Estrutura do Projeto
```
├── TopicosI-A2-MLPs.ipynb
├── adult/
│   ├── adult.data
│   └── adult.test
└── README.md
```

- **TopicosI-A2-MLPs.ipynb** → Notebook com toda a implementação dos modelos MLP  
- **adult/** → Conjunto de dados utilizado (Adult Income Dataset)  
- **README.md** → Documentação do projeto  

---

## ⚙️ Descrição da Atividade

A atividade consiste na construção e avaliação de **redes neurais do tipo Multilayer Perceptron (MLP)** para resolver um problema de **classificação de renda**, utilizando o **Adult Income Dataset**.

O objetivo é comparar diferentes arquiteturas de redes neurais e analisar seu desempenho com base em métricas de classificação.

---

## 🔎 Etapas do Processamento

### 🔸 Pré-processamento dos Dados
Preparação do dataset para uso nos modelos:

- Limpeza de dados ausentes  
- Codificação de variáveis categóricas  
- Normalização dos atributos numéricos  

---

### 🔸 Divisão dos Dados
Separação do dataset em:

- Conjunto de **treinamento**  
- Conjunto de **teste**  

Também é realizado o **balanceamento das classes** para evitar viés no modelo.

---

### 🔸 Construção dos Modelos MLP
Foram implementadas diferentes arquiteturas utilizando **PyTorch**:

- Modelo simples (uma camada oculta)  
- Modelo com duas camadas ocultas  
- Modelo customizado (CJT)  

---

### 🔸 Treinamento das Redes
Durante o treinamento:

- Ajuste dos pesos via **backpropagation**  
- Uso de função de perda (loss function)  
- Monitoramento da convergência do modelo  

---

### 🔸 Avaliação dos Modelos
Os modelos são avaliados utilizando:

- **Acurácia balanceada**  
- **Precisão (Precision)**  
- **Recall**  
- **F1-score**  
- **Matriz de confusão**  

---

### 🔸 Comparação de Desempenho
Os resultados são organizados em tabelas (PrettyTable), permitindo:

- Comparar eficiência entre modelos  
- Identificar a melhor arquitetura para o problema  

---

## 🧰 Tecnologias Utilizadas

- **Python**
- **Pandas** – manipulação de dados  
- **NumPy** – operações matemáticas  
- **Matplotlib** – visualização de gráficos  
- **PyTorch (`torch`, `torch.nn`, `torch.optim`)** – construção e treinamento das redes neurais  
- **Scikit-learn** – pré-processamento e métricas  
- **PrettyTable** – geração de tabelas comparativas  

---

## 👥 Autores

| [<img src="https://github.com/thiagocordeirum.png?size=100" width=100><br><sub>Thiago Cordeiro</sub>](https://github.com/thiagocordeirum) | [<img src="https://github.com/Jaum36.png?size=100" width=100><br><sub>João Victor</sub>](https://github.com/Jaum36) | [<img src="https://github.com/cpc231341.png?size=100" width=100><br><sub>Cristiano Peniche Ceccon</sub>](https://github.com/cpc231341) |
|:---:|:---:|:---:|

---

## 👩‍🏫 Orientação

- Orientador(a): **Profa. Dra. Elloá B. Guedes**  
- Instituição: **Escola Superior de Tecnologia – Universidade do Estado do Amazonas (EST/UEA)**  
- Data: **Março de 2026**  
