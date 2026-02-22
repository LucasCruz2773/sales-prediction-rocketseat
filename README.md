# 📈 Sales Prediction — Previsão de Vendas

> Projeto de **regressão linear** para prever vendas mensais. Desenvolvido na trilha de IA da Rocketseat.

---

## 🎯 Sobre o projeto

Este repositório contém um modelo de **Machine Learning** que aprende a tendência de vendas ao longo dos meses e é capaz de prever o valor de um mês futuro (por exemplo, dezembro) usando apenas o número do mês como entrada.

O fluxo do notebook cobre:

- **Exploração dos dados** — correlação, heatmaps e scatter matrix
- **Treino/Teste** — dados de janeiro a novembro para treino; dezembro reservado para teste
- **Modelo** — `LinearRegression` do scikit-learn
- **Métricas** — MAE (Mean Absolute Error) e R² quando há mais de uma amostra no teste
- **Visualização** — gráfico dos pontos reais + reta da regressão

---

## 🛠 Tecnologias

| Ferramenta | Uso |
|------------|-----|
| **Python 3.11** | Linguagem |
| **pandas** | Dados em DataFrame |
| **matplotlib** & **seaborn** | Gráficos e análise exploratória |
| **scikit-learn** | Regressão linear, métricas (MAE, R²) |

---

## 🚀 Como rodar

### 1. Clonar e entrar na pasta

```bash
git clone <url-do-repo>
cd sales-prediction-rocketseat
```

### 2. Ambiente com Pipenv

```bash
pipenv install
pipenv shell
```

### 3. Abrir o notebook

```bash
jupyter notebook sales_prediction.ipynb
```

Ou abra o arquivo `sales_prediction.ipynb` direto no VS Code / Cursor.

---

## 📁 Estrutura

```
sales-prediction-rocketseat/
├── README.md
├── Pipfile
├── Pipfile.lock
└── sales_prediction.ipynb   # pipeline completo: dados → modelo → gráfico
```

---

## 📊 Dados

Os dados são **vendas mensais** (ex.: 2000 em janeiro até 3300 em dezembro). O notebook:

1. Converte o mês em número (1–12)
2. Treina a regressão em 11 meses
3. Avalia a previsão para dezembro e plota a reta do modelo

---

## 📜 Licença

Projeto de estudo. Sinta-se livre para usar e adaptar.

---

<p align="center">
  <sub>Feito na trilha de IA da <strong>Rocketseat</strong> 🚀</sub>
</p>
