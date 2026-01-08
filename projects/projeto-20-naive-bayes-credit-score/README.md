# Projeto 20 — Classificação de Credit Score com Naive Bayes (GaussianNB)

Este projeto treina e avalia um classificador **Naive Bayes Gaussiano (GaussianNB)** para prever a categoria de **Credit Score** a partir de variáveis numéricas e categóricas previamente codificadas.

---

## 🎯 Objetivo

- Prever a variável alvo `CREDIT SCORE_LE`
- Avaliar desempenho em **treino** e **teste**
- Analisar métricas de **Acurácia** e **Recall**
- Visualizar **matriz de confusão** com Plotly
- Implementar melhorias:
  - **Validação cruzada (cross-validation)**
  - **Análise de probabilidades (`predict_proba`)** para avaliação de risco

---

## 🧾 Mapeamento das Classes

| Código | Classe |
|------|-------|
| `0` | Alto |
| `1` | Baixo |
| `2` | Médio |

---

## 📊 Origem dos Dados

Os arquivos estão localizados na pasta **`data/`**:

- `x_train_bal.csv`
- `y_train_bal.csv`
- `x_test.csv`
- `y_test.csv`

### Observações:
- O **conjunto de treino foi balanceado com SMOTE**
- O conjunto de teste permanece **desbalanceado**, simulando um cenário real
- Os dados foram gerados no **Projeto 17 (Credit Score)**

---

## ▶️ Como Executar

### 1) Instalar dependências

```bash
pip install -r requirements.txt
