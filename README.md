# Projeto Churn Telecom — Parceria EBAC / Semantix

## 📌 Objetivo
Prever o cancelamento (churn) de clientes em uma empresa de telecomunicações, utilizando análise exploratória e modelagem com Regressão Logística.

---

## 📂 Estrutura do repositório

- data/ → base de dados (telco_churn.csv)
- notebooks/ → notebook com código e análises
- img/ → imagens utilizadas no README
- README.md → documentação do projeto

---

## 📊 Base de dados
- Dataset público de telecom (Telco Customer Churn)
- 7043 registros e 21 colunas
- Variável alvo: `Churn` (Yes/No)

---

## 🧪 Técnicas utilizadas
- Pandas e NumPy para manipulação de dados  
- Seaborn e Matplotlib para visualização  
- One-Hot Encoding para variáveis categóricas  
- Treinamento com Regressão Logística  
- Matriz de confusão e classification report  
- Curva ROC e AUC

---

## 🧠 Principais insights (EDA)
- Contratos **Month-to-month** apresentam maior churn  
- Método de pagamento **Electronic check** está associado ao churn  
- Serviço de internet **Fiber optic** indica maior risco de saída  
- **Mensalidades elevadas** (R$ 78 a R$ 98) aumentam a chance de cancelamento  
- **Clientes recentes** (até 15 meses) têm maior probabilidade de churn  

---

## 🤖 Resultado do modelo
- **Acurácia:** 80%  
- **Recall (classe Yes):** 51%  
- **AUC:** 0.84  

O modelo apresentou bom desempenho inicial, com capacidade de prever clientes com risco de cancelamento.

---

## 🚀 Próximos passos
- Aplicar técnicas de balanceamento (SMOTE, class_weight)
- Testar modelos como Random Forest e XGBoost
- Desenvolver interface interativa com Streamlit ou Power BI

---

## 👨‍💻 Autor
Projeto desenvolvido por **Marcos José**, aluno da EBAC — Curso de Ciência de Dados.
