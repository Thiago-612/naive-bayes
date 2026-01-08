# Naive Bayes — Estudos e Projetos

Este repositório reúne projetos práticos utilizando algoritmos da família **Naive Bayes**,
aplicados a diferentes problemas de classificação.

O objetivo é demonstrar:
- Fundamentos probabilísticos (Teorema de Bayes)
- Uso prático do Gaussian Naive Bayes
- Avaliação de modelos (accuracy, recall, matriz de confusão)
- Análise de incerteza via `predict_proba`
- Validação com cross-validation

## Estrutura

naive-bayes/
├─ projects/
│ └─ project-20-credit-score/
│ ├─ src/
│ ├─ data/
│ └─ README.md

## Projetos

### 🔹 Projeto 20 — Credit Score Classification
Classificação de clientes em **Alto / Médio / Baixo risco de crédito**
utilizando **Gaussian Naive Bayes**, com:
- Base balanceada (SMOTE)
- Avaliação em treino e teste
- Cross-validation
- Análise de confiança das previsões

➡️ Veja detalhes em `projects/project-20-credit-score/`

## Tecnologias
- Python
- scikit-learn
- pandas
- numpy
- plotly

## Observação
Os datasets são descritos nos READMEs individuais de cada projeto.
