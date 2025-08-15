# 📊 Classificação: Validação de modelos e métricas de avaliação com Python

Este repositório contém dois notebooks interativos focados na prática de **análise exploratória de dados (EDA)** e **modelos de classificação supervisionada**, utilizando Python e bibliotecas poderosas como `pandas`, `plotly`, `scikit-learn` e outras.

---

## 🎯 Objetivo do Projeto
O objetivo deste projeto é consolidar habilidades práticas em análise e modelagem de dados com Python por meio de dois estudos aplicados:

- **Desafios de manipulação e visualização de dados**  
  Utilizando bases com características de clientes e churn, com foco em filtragem, agregações, e visualizações interativas com Plotly.

- **Desenvolvimento de um modelo de classificação supervisionada**  
  Aplicado a um cenário de investimento em marketing, abordando desde a análise exploratória até a construção, avaliação e comparação de modelos preditivos com a biblioteca Scikit-learn.

O projeto visa exercitar o raciocínio analítico, fortalecer o domínio das principais bibliotecas da stack de ciência de dados e introduzir boas práticas no fluxo de machine learning, como:
- Separação de dados
- Encoding
- Validação cruzada
- Ajuste de hiperparâmetros
- Métricas de avaliação
- Balanceamento de classes
- Serialização de modelos

---

## 🧪 Visão Geral dos Notebooks

### `classificação_validação_e_métricas.ipynb`

Este notebook aplica uma **pipeline completa de classificação supervisionada**, desde a leitura e transformação dos dados até a comparação entre diferentes modelos de machine learning com métricas apropriadas.

#### Etapas do projeto:
- Análise exploratória inicial
- Pré-processamento e limpeza
- Modelagem preditiva com:
  > - DecisionTreeClassifier (baseline e ajustado)
  > - Técnicas de validação (Holdout, K-Fold)
- Métricas de avaliação:
  > - Acurácia
  > - Precisão
  > - Recall
  > - F1-Score
  > - Curva ROC e AUC
  > - Curva Precision-Recall e AP
- Validação cruzada
- Balanceamento de dados (Oversampling e Undersampling)
- Avaliação final com matriz de confusão

---

### `hora_da_prática.ipynb`

Este notebook reúne **desafios práticos divididos por aulas temáticas**. O objetivo é consolidar os conhecimentos adquiridos em aulas de introdução à análise de dados, com foco na biblioteca `pandas` e visualizações com `plotly.express`.

#### Etapas do projeto:
- Leitura e inspeção de dados
- Limpeza e tratamento de valores ausentes
- Criação de novas variáveis
- Visualização de distribuições e relações
- Aplicação de modelos de classificação para avaliação prática
- Comparação de desempenho de algoritmos (Decision Tree, Random Forest)
- Cálculo e interpretação de métricas

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python 
- **Bibliotecas de análise:** Pandas, NumPy
- **Visualização:** Matplotlib, Plotly Express
- **Machine Learning:** Scikit-learn

---

## 📌 Exemplos de Saída

### Classificação e Métricas
```
Acurácia de treino: 0.9206155632984901
Acurácia de validação: 0.9055831373573731
----
Precisão: 0.25595238095238093
Recall: 0.04291417165668663
----
F1-Score: 0.0735042735042735
AUC: 0.5154927762568193
AP: 0.09451329370574367
```
