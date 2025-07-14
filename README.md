# mlflow-from-scratch

<p align="center">
  <img src="https://github.com/VictorFrancheto/mlflow-from-scratch/blob/main/image.jpg">
</p>

# 📊 Experimento com MLflow 3.1.1 — Treinamento, Registro e Carregamento de Modelo

Este repositório demonstra como utilizar o **MLflow 3.1.1** para acompanhar todo o ciclo de vida de um experimento de machine learning, desde o treinamento até o carregamento do modelo final.

---

## 🚀 O que será feito

- Treinamento de um modelo de machine learning (usando `XGBoost`);
- Otimização de hiperparâmetros com **Optuna**;
- Registro dos hiperparâmetros, métricas e gráficos no **MLflow**;
- Salvamento do **melhor modelo treinado** no MLflow;
- Carregamento do modelo posteriormente usando sua URI.

---

## 🧠 Por que usar MLflow?

O MLflow permite:

✅ **Rastrear automaticamente** métricas, parâmetros e artefatos dos experimentos;  
✅ **Comparar execuções** de forma organizada via interface web;  
✅ **Salvar e versionar modelos** treinados, evitando perda de reprodutibilidade;  
✅ **Carregar modelos salvos facilmente**, sem necessidade de salvar manualmente em disco;  
✅ Integrar com múltiplos frameworks como `xgboost`, `sklearn`, `pytorch`, entre outros.

---

## 📦 Requisitos

- Python 3.8+
- MLflow 3.1.1
- XGBoost
- Optuna
- Matplotlib / Pandas / Scikit-learn (para visualizações e preparação de dados)

---

## ▶️ Como executar

1. Instale as dependências:
   ```bash
   pip install mlflow==3.1.1 xgboost optuna scikit-learn matplotlib pandas
