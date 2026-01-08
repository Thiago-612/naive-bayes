# Projeto 20 — Classificação de Credit Score com Naive Bayes (GaussianNB)

Este projeto treina e avalia um classificador **Naive Bayes Gaussiano (GaussianNB)** para prever a categoria de **Credit Score** a partir de variáveis numéricas/codificadas.

## Objetivo
- Prever `CREDIT SCORE_LE` (classe alvo) com Naive Bayes
- Avaliar desempenho em **treino** e **teste**
- Visualizar matriz de confusão (Plotly)
- Adicionar melhorias: **cross-validation** e análise de **probabilidades** (`predict_proba`)

## Mapeamento das classes
- `0 = Alto`
- `1 = Baixo`
- `2 = Médio`

## Origem dos dados
Os conjuntos `x_train_bal.csv`, `y_train_bal.csv`, `x_test.csv`, `y_test.csv` constam na pasta **data**.
O conjunto de treino foi **balanceado (SMOTE)**.

## Como executar

### 1) Instalar dependências
```bash
pip install -r requirements.txt
