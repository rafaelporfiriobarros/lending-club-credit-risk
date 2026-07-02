<<<<<<< HEAD
# Credit Risk Prediction using Lending Club Data


## Sobre o Projeto

Este projeto tem como objetivo desenvolver um modelo de **Machine Learning** para previsão de inadimplência utilizando a base pública da **Lending Club**.

O projeto segue um fluxo completo de Ciência de Dados, desde o entendimento do problema de negócio até a avaliação dos modelos preditivos, simulando um cenário real de análise de risco de crédito.

---

## Objetivo

Construir um modelo capaz de prever se um cliente possui maior probabilidade de entrar em **default**, auxiliando instituições financeiras na tomada de decisão durante a concessão de crédito.

---

## Dataset

- Base: Lending Club Loan Data
- Tipo do problema: Classificação Binária
- Target: `good_bad_loan`

Classes:

- **1** → Bom pagador
- **0** → Inadimplente

---

## 🛠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## Estrutura do Projeto

```
.
├── data/
├── notebooks/
├── models/
├── images/
├── requirements.txt
└── README.md
```

---

## Pipeline do Projeto

```text
Coleta dos Dados
        │
        ▼
Análise Exploratória (EDA)
        │
        ▼
Limpeza dos Dados
        │
        ▼
Feature Engineering
        │
        ▼
Tratamento de Missing Values
        │
        ▼
One-Hot Encoding
        │
        ▼
Padronização
        │
        ▼
Balanceamento das Classes
        │
        ▼
Treinamento dos Modelos
        │
        ▼
Avaliação dos Resultados
```

---

## Pré-processamento

Durante a preparação dos dados foram realizadas as seguintes etapas:

- Remoção de variáveis com Data Leakage;
- Tratamento de valores ausentes;
- Conversão de variáveis categóricas;
- Engenharia de atributos;
- One-Hot Encoding;
- Padronização das variáveis numéricas;
- Balanceamento da variável alvo.

---

## Análise Exploratória

Foram realizadas análises para compreender o comportamento dos clientes, incluindo:

- Distribuição das variáveis;
- Correlação entre atributos;
- Taxa de inadimplência por categoria;
- Identificação de outliers;
- Análise de Missing Values.

---

## Modelos Avaliados

Os seguintes algoritmos foram treinados e comparados:

- Logistic Regression
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost

---

## Métricas Utilizadas

Os modelos foram avaliados utilizando:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

---

## Resultados

O projeto demonstrou que algoritmos baseados em árvores apresentaram melhor capacidade preditiva em comparação aos modelos lineares.

Entre os principais aprendizados:

- Engenharia de atributos contribuiu significativamente para o desempenho do modelo;
- O tratamento de dados desbalanceados melhorou a identificação da classe minoritária;
- A remoção de variáveis com **Data Leakage** foi essencial para evitar superestimação do desempenho.

---

## Principais Técnicas Aplicadas

✔ Data Cleaning

✔ Feature Engineering

✔ Data Leakage Prevention

✔ One-Hot Encoding

✔ StandardScaler

✔ Class Balancing

✔ Model Comparison

✔ Model Evaluation

---

## Como executar

Clone o repositório

```bash
git clone https://github.com/seuusuario/lending-club-credit-risk.git
```

Instale as dependências

```bash
pip install -r requirements.txt
```

Execute o notebook principal

```bash
jupyter notebook
```

--- 

## Dataset

https://www.kaggle.com/datasets/wordsforthewise/lending-club/data

---

## Aprendizados

Este projeto permitiu aplicar, na prática, todo o ciclo de desenvolvimento de um modelo de Machine Learning para risco de crédito, incluindo boas práticas de pré-processamento, engenharia de atributos, comparação de algoritmos e avaliação de desempenho.

---

## Autor

**Rafael Porfírio Barros**

MBA em Data Science & Analytics – USP/ESALQ

Graduando em Ciências Contábeis – FIPECAFI

GitHub: https://github.com/rafaelporfiriobarros

LinkedIn: https://linkedin.com/in/rafaelporfirio
=======
"# lending-club-credit-risk" 
>>>>>>> 6dd3942c116dd4b1c3f1ddf14314d0b2fe52bb4b
