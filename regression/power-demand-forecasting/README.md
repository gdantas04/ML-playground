# ⚡ Power Demand Forecasting

Projeto de modelagem preditiva para consumo de energia elétrica com foco em análise exploratória, detecção de anomalias e previsão de carga total utilizando algoritmos de Machine Learning.

O objetivo é construir um pipeline robusto e replicável que simula uma abordagem de previsão de curto prazo, aplicável a contextos reais de monitoramento energético. A proposta busca alinhar ciência de dados à realidade do setor elétrico, com potencial para aplicações na operação, planejamento e otimização do sistema.

---

## 📈 Objetivos

* Realizar limpeza e preparação dos dados de consumo elétrico.
* Detectar padrões anômalos usando Isolation Forest.
* Prever o consumo total com Random Forest Regressor.
* Otimizar os hiperparâmetros do modelo via Optuna.
* Avaliar desempenho com métricas explicativas (R², RMSE, MAE, MAPE).

---

## 📊 Fonte dos Dados

* **Dataset:** [Electric Power Consumption - Kaggle](https://www.kaggle.com/datasets/fedesoriano/electric-power-consumption)
* **Origem:** Dados de medição de consumo na cidade de Tétouan, no Marrocos. A rede de distribuição é alimentada por três estações de zona: Quads, Smir e Boussafou.

---

## 🧠 Técnicas Utilizadas

* Análise Exploratória de Dados (EDA)
* Detecção de outliers com Isolation Forest
* Modelagem preditiva com Random Forest
* Validação cruzada e ajuste com Optuna
* Avaliação com métricas de regressão

---

## 📁 Estrutura do Projeto

```
power-demand-forecasting/
├── Data/                                 
|   ├── powerconsumption.csv              # Dados originais
|   ├── powerconsumption_after_EDA.csv    # Dados tratados
├── Notebooks/
│   ├── 00_eda.ipynb                      # Análise exploratória e tratamento
│   └── 01_training.ipynb                 # Treinamento, avaliação e tuning
├── README.md
└── requirements.txt
```

---

## 🚀 Resultados

* Mais de 95% de integridade mantida após remoção de outliers
* R² superior a 0.90 na predição de carga total

