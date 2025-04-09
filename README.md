# 📈 Regressão Linear Aplicada a Dados de Irrigação

Este projeto aplica técnicas de **aprendizado de máquina supervisionado** utilizando **regressão linear simples** para modelar a relação entre as **horas de irrigação** e a **área irrigada por ângulo**. A análise envolve carregamento de dados, análise exploratória, construção de modelo, avaliação e predições.

---

## 📂 Estrutura do Projeto

- `dados_irrigacao.csv`: Base de dados com 39 observações.
- `main.py` ou `notebook.ipynb`: Código principal com análise e modelagem.
- `README.md`: Documentação do projeto.

---

## 🧪 Bibliotecas Utilizadas

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`
- `scipy`
- `optuna`
- `ipywidgets`
- `ipykernel`
- `nbformat`

---

## ✅ Etapas Realizadas

1. **Carregamento e Visualização dos Dados**

   - Leitura do CSV e verificação das primeiras linhas.

2. **Análise Exploratória dos Dados (EDA)**

   - Estatísticas descritivas.
   - Gráficos de dispersão com `seaborn` e `plotly`.
   - Análise de correlação com mapa de calor.

3. **Construção do Modelo de Regressão Linear**

   - Separação em dados de treino e teste.
   - Treinamento do modelo com `scikit-learn`.
   - Impressão da equação da reta ajustada.

4. **Avaliação do Modelo**

   - Cálculo das métricas: **MSE** e **MAE**.
   - Visualização dos valores reais vs preditos.

5. **Análise de Resíduos**

   - Distribuição dos resíduos.
   - Teste de normalidade com **Shapiro-Wilk**.

6. **Predições**
   - Exemplo de predição para 15 horas de irrigação.

---

## 🧠 Modelo Treinado

- **Tipo de modelo:** Regressão Linear Simples
- **Variável independente (X):** Horas de Irrigação
- **Variável dependente (Y):** Área Irrigada por Ângulo
- **Equação da reta:** `Y = aX + b` (os coeficientes são exibidos no script)

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-projeto.git
   cd nome-do-projeto
   ```
2. Instale as dependências:
   ```bash
   pipenv install
   ```
3. Execute o Jupyter Notebook
