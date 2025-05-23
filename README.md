# fraud-detection-logistic-regression

Este projeto utiliza **Regressão Logística** para detectar transações bancárias fraudulentas, usando um dataset real de cartões de crédito. O objetivo é aplicar técnicas de Machine Learning para identificar padrões e prever fraudes com precisão.

---

## 📊 Dataset

- Fonte: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contém transações realizadas com cartão de crédito em setembro de 2013.
- Possui **284.807** transações e **31** características (atributos).
- Classes: `0` (legítimo) e `1` (fraudulento)

---

## 🧠 Tecnologias e Bibliotecas

- Python 3.13.3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

---

## ⚙️ Funcionalidades do Projeto

- 📦 Carregamento e limpeza dos dados
- 📈 Análise exploratória e visualização
- ⚖️ Tratamento de desbalanceamento de classes
- 🤖 Treinamento de modelo de regressão logística
- 🧪 Avaliação com matriz de confusão, precision, recall e f1-score
- 💾 Salvamento do modelo com `joblib`
- (Opcional) Deploy com Streamlit

---

## 🚀 Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/fraud-detection-logistic-regression.git
cd fraud-detection-logistic-regression
