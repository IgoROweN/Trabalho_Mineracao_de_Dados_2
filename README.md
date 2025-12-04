# Previsão de Vendas - Varejo Online (Time Series)

Trabalho referente ao 2º Bimestre da disciplina de Mineração de Dados do curso DSM (Desenvolvimento de Software Multiplataforma) da FATEC Franca. O objetivo é realizar a previsão de faturamento mensal de uma varejista online do Reino Unido utilizando técnicas de Séries Temporais.

## 🎯 Objetivos

* Realizar a limpeza e pré-processamento de dados transacionais reais (dataset "Online Retail II").
* Transformar dados brutos em uma série temporal mensal.
* Aplicar modelos de Suavização Exponencial (Holt) para prever o faturamento futuro.

## 🛠️ Tecnologias

* Python 3.10
* Pandas & NumPy
* Matplotlib & Seaborn
* Statsmodels (Modelagem Estatística)
* Scikit-learn (Métricas de Avaliação)

## 📊 Resultados

O modelo estatístico de Holt (Tendência Linear) foi aplicado para prever os últimos 6 meses da base de dados.
* **Tendência Identificada:** Queda no faturamento no período final de treino.
* **Métricas:** Consulte o notebook para ver o MAE e RMSE finais.

## 🚀 Como Executar

1.  Instale as dependências: `conda install pandas matplotlib seaborn statsmodels openpyxl`
2.  Baixe o dataset [Online Retail II](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II) e coloque na pasta `data/`.
3.  Execute o notebook `Previsao_Vendas_Retail.ipynb`.

---
**Aluno:** [Igor Owen Silva de Paula] | **R.A.:** [1091392313006]